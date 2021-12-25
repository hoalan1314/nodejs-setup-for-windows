# Install nvm

1. Go to [nvm github page](https://github.com/nvm-sh/nvm)
2. Run `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash` in wsl

![image](https://user-images.githubusercontent.com/37486266/143883682-cd1a66c3-0a70-436a-bd82-5ea9597caae2.png)

4. copy
```
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion
```
5. Run `nano ~/.bash_profile` ([?](https://www.thegeekdiary.com/what-is-the-purpose-of-bash_profile-file-under-user-home-directory-in-linux/#:~:text=bash_profile%20file%20is%20a%20personal,the%20system%20to%20initiate%20applications))
6. Paste step `4`
7. Run `ctrl + x`, `y`, `Enter` to save
8. Run `source ~/.bash_profile` ([?](https://stackoverflow.com/questions/4608187/how-to-reload-bash-profile-from-the-command-line))
9. Run `nvm install 16` to install [current LTS version of nodejs](https://nodejs.org/en/about/releases/)
10. Run `node -v` to verify node version
