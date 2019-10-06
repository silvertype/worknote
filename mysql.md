# macOs 에서 mysql 설치

* install
```shell
brew update
brew search mysql
brew install mysql
brew list | grep mysql
```

* secure
```
mysql_secure_installation

Would you like to setup VALIDATE PASSWORD component? (복잡한 비밀번호 설정 할건가?)
Please set the password for root here.
New password:
Remove anonymous users? (Press y|Y for Yes, any other key for No) : y (익명 사용자 제거할건가?)
Disallow root login remotely? (Press y|Y for Yes, any other key for No) : y (원격에서 root 접근 막을 건가?)
Remove test database and access to it? (Press y|Y for Yes, any other key for No) : y (test DB 지울 건가?)
Reload privilege tables now? (Press y|Y for Yes, any other key for No) : y (권한 테이블 지금 리로드 할건가?)
All done!
```

* connect

`mysql -uroot -p`

* run

`brew services start mysql`
or
`mysql.server start`
