# LaraWOW
Fast and easy step for Laravel develop beginner (laravel + ftp + database)

Pre-installation : git clone and config docker-compose.yml
```
$ sudo apt update
$ git clone https://github.com/NattanonDev/LaraWOW.git larawow
$ cd larawow && nano docker-compose.yml
```

run docker-compose
```
$ docker-compose up -d
```
Ports used
| Service  | Port |
| ------------- | :---: |
| http  | 80  |
| ftp  | 21  |
| vftpd | 30000-30009 |
| database  | 3306  |
