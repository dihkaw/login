# Halaman login nodejs dengan AWS Cognito
## Konfigurasi Environment
Buat file **.env** untuk menghubungkan antara aplikasi dengan AWS Cognito
```java
AWS_REGION=us-west-2                  # Region tempat Pool dibuat
AWS_USER_POOL_ID=your_user_pool_id    # ID user pool milik Anda
AWS_CLIENT_ID=your_client_id          # ID Client AWS
```
## Instalasi Dependency
Jalankan perintah berikut untuk menginstal library yang dibutuhkan:
```
npm install express body-parser aws-sdk dotenv ejs
```
## Struktur proyek
```
project/
├── views/
│   └── login.ejs
├── public/
│   └── styles.css
├── app.js
└── .env
```

