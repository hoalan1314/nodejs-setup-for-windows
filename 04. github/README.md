# Github與ssh key

## Github
在[Github](https://github.com/)開設account

## SSH key
1. 在ubuntu terminal輸入以下指令創建ssh key ([?](https://codecharms.me/posts/security-ssh))
```
$ ssh-keygen
```
2. 並按下數下Enter使用預設數值
3. 複制public key
```
$ cat ~/.ssh/id_rsa.pub
```
4. 在github內的`Settings > SSH and GPG keys`內按`New SSH Key`
5. 輸入`Title`(如`my Ubuntu`)並貼上public key
6. 按`Add SSH Key`
7. 輸入密碼
8. 看見以下畫面即完成

![image](https://user-images.githubusercontent.com/37486266/144425967-341f24a6-48f9-412c-a98d-25370c850b4f.png)
