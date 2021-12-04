# Github and ssh key

## Github
Create an account in [Github](https://github.com/)

## SSH key
1. Input the following command to ubuntu terminal to genrrate ssh key ([?](https://codecharms.me/posts/security-ssh))
```
$ ssh-keygen
```
2. Press Enter few times to use default setting
3. copy public key
```
$ cat ~/.ssh/id_rsa.pub
```
4. Go to github, `Settings > SSH and GPG keys`, and click `New SSH Key`
5. Input some `Title`(eg. `my Ubuntu`) and paste public key
6. Click `Add SSH Key`
7. Input password
8. Succses when you can see the following

![image](https://user-images.githubusercontent.com/37486266/144425967-341f24a6-48f9-412c-a98d-25370c850b4f.png)

## Github default branch
1. Go to `Settings > Repositories`
2. Under `Repository default branch` change `main` to `master`
3. Click `Update`
