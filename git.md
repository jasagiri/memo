# config

```
git config --global user.name "ユーザー名"
git config --global user.email "メールアドレス"

#日本語ファイル名がエスケープされないように
git config --global core.quotepath false
```

# ssh

```
mkdir ~/.ssh
cd ~/.ssh
ssh-keygen -t rsa -c 'mail_address'
```

GitHubのsettingsで公開鍵（.pub）を設定


```
git add .
git commit
git push origin master
```

