# git tip

## github repository ssh 로 접근하기

* ssh key 생성하기

```
$ ssh-keygen
$ cat ~/.ssh/id_rsa.pub
public key 내용을 복사해서 gitgub Settings > SSH keys 에 등록
```

```
alias.lg=log --graph --format=format:'%C(ul cyan)%h%C(reset) | %an |%C(auto)%d%C(reset) %C(white)%ai%C(reset) (%ar)%n''          %C(white)%s%C(reset) %C(bold black)- %an%C(reset)' --all
```
