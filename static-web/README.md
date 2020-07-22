# Belajar Docker

## Build Image

```console
#Untuk build image static-web, jalankan perintah berikut :

docker build -t static-web .

```

## Run Kontainer

```console
#Untuk menjalankan kontainer, jalankan perintah berikut :
docker container run -d -p 80:80 --name myweb static-web
```

## Melihat list kontainer

```console
#Untuk melihat semua list kontainer (yang berjalan dan yang dihentikan), jalankan perintah berikut :
docker container ps -a

#Untuk menghentikan (stop) kontainer yang berjalan, jalankan perintah berikut
docker container stop myweb

#Untuk menjalankan kembali
docker container start myweb

#Untuk menghapus kontainer
docker container stop myweb
docker container rm myweb

#Atau
docker container rm myweb -f
```
