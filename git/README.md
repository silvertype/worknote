# git tip

## github repository ssh 로 접근하기

* ssh key 생성하기

```
$ ssh-keygen
$ cat ~/.ssh/id_rsa.pub
public key 내용을 복사해서 gitgub Settings > SSH keys 에 등록
```

```
~/.gitconfig 에 추가
[alias]
  lg=log --graph --format=format:'%C(ul cyan)%h%C(reset) | %an |%C(auto)%d%C(reset) %C(white)%ai%C(reset) (%ar)%n''          %C(white)%s%C(reset) %C(bold black)- %an%C(reset)' --all
  
  lg = log --graph --abbrev-commit --decorate --format=format:'%C(cyan)%h%C(reset) - %C(green)(%ai)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(auto)%d%C(reset)' --all
```
