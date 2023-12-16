# Linux
* tracking linux bootup time
    * [Find Out How Long Does it Take To Boot Your Linux System](https://itsfoss.com/check-boot-time-linux/)
    * `systemd-analyze`
    * `systemd-analyze blame`
    * improvements
        * `sudo systemctl disable <service-name-from-blame>`
        * Plymouth - boot splash screen
        * Network manager - internet connection
    * Detailed [analysis](https://opensource.com/article/20/9/systemd-startup-configuration)

* system setup
    ```bash
    sudo snap install code --classic
    sudo snap install flutter --classic


    enabled ufw firewall

    root has an explicit password now
    sudo -i 
    passwd
    ```

