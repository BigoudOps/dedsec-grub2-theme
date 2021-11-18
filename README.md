![logo](/media/logo.png)

<p align="center">
  <b>DedSec theme was created, inspired by the fictional hacker group DedSec from Watch Dogs video game developed by Ubisoft.</b>
</p>
<p align="center">
  <a href="https://raw.githubusercontent.com/vandalsoul/dedsec-grub2-theme/main/LICENSE"><img alt="undefined" src="https://img.shields.io/badge/License-GPL--3.0-blue?style=for-the-badge&logo=github">
  <a href="https://www.pling.com/p/1569525"><img alt="undefined" src="https://img.shields.io/badge/Download-Here-green?style=for-the-badge&logo=github"></a>
</p>

## 📢 UPDATE 3.0 IS HERE... 🥳🥳🥳
***With new theme-styles upgraded fonts and more... see the Changelog for more info.***

## ⚙️ Installation

### ✅ Using Installation Script

#### 1️⃣ First clone the repository, then navigate into it.
```shell
git clone https://github.com/vandalsoul/dedsec-grub2-theme.git
cd dedsec-grub2-theme
```

#### 2️⃣ Run the `install.py`
```shell
sudo python3 install.py
```

### ✅ Manual Installation
*Click to view...*
<details>
 <summary><b>Debian 💀 Ubuntu 💀 Arch</b></summary>
 
  #### 1️⃣ Download your favourite version of the theme from [**Pling**](https://www.pling.com/p/1603282/).

  Now extract your downloaded .zip file.

  Either manually extract it or use the command below. ( *Here I'm using 'brainwash' version of my theme as an example* )
  ```shell
  unzip dedsec-brainwash.zip
  ```
  *The rest of the commands are the same for all the theme styles.*

  #### 2️⃣ Copy the theme directory.
  ```shell
  sudo cp -r dedsec /boot/grub/themes/
  ```
  #### 3️⃣ Make changes to the GRUB config file.

  ```shell
  sudo nano /etc/default/grub
  ```
  Find the line `GRUB_THEME=` then change it to `GRUB_THEME="/boot/grub/themes/dedsec/theme.txt"`

  Then save the file.

  #### 4️⃣ Finally, update the grub.
  ```shell
  sudo grub-mkconfig -o /boot/grub/grub.cfg
  ```
  Now the theme should be installed successfully, enjoy !!
</details>

<details>
 <summary><b>Fedora 💀 Redhat</b></summary>
 
  #### 1️⃣ Download your favourite version of the theme from [**Pling**](https://www.pling.com/p/1569525).

  Now extract your downloaded .zip file.

  Either manually extract it or use the command below. ( *Here I'm using 'brainwash' version of my theme as an example* )
  ```shell
  unzip dedsec-brainwash.zip
  ```
  *The rest of the commands are the same for all the theme styles.*

  #### 2️⃣ Copy the theme directory.
  ```shell
  sudo cp -r dedsec /boot/grub2/themes/
  ```
  #### 3️⃣ Make changes to the GRUB config file.

  ```shell
  sudo nano /etc/default/grub
  ```
  Find the line `GRUB_THEME=` then change it to `GRUB_THEME="/boot/grub2/themes/dedsec/theme.txt"`
 
  Change the line `GRUB_TERMINAL_OUTPUT=console` to this *(comment it out)* `#GRUB_TERMINAL_OUTPUT=console`

  Then save the file.

  #### 4️⃣ Finally, update the grub.
  ```shell
  sudo grub2-mkconfig -o /boot/grub2/grub.cfg
  ```
  Now restart your computer the grub theme should be installed successfully, enjoy !!
</details>

## 💰 Donate

**Hey everyone 🙋‍♂️ if you wanna support me on my theme making campaign then feel free to buy me a cup of coffee ☕ anytime you wish...**
 
<a href="https://www.buymeacoffee.com/vandalsoul" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

## 📸 Preview

<p><b>NOTE : <i>The theme-style name tags present in the preview are not there in the actual theme...</i></b></p>
<p align="center">
  <img width="48%" src="https://raw.githubusercontent.com/vandalsoul/dedsec-grub2-theme/main/media/previews/preview-compact.png" />
  <img width="48%" src="https://raw.githubusercontent.com/vandalsoul/dedsec-grub2-theme/main/media/previews/preview-brainwash.png" />
  <img width="48%" src="https://raw.githubusercontent.com/vandalsoul/dedsec-grub2-theme/main/media/previews/preview-lovetrap.png" />
  <img width="48%" src="https://raw.githubusercontent.com/vandalsoul/dedsec-grub2-theme/main/media/previews/preview-spam.png" />
  <img width="48%" src="https://raw.githubusercontent.com/vandalsoul/dedsec-grub2-theme/main/media/previews/preview-spyware.png" />
  <img width="48%" src="https://raw.githubusercontent.com/vandalsoul/dedsec-grub2-theme/main/media/previews/preview-redskull.png" />
  <img width="48%" src="https://raw.githubusercontent.com/vandalsoul/dedsec-grub2-theme/main/media/previews/preview-firewall.png" />
  <img width="48%" src="https://raw.githubusercontent.com/vandalsoul/dedsec-grub2-theme/main/media/previews/preview-strike.png" />
  <img width="48%" src="https://raw.githubusercontent.com/vandalsoul/dedsec-grub2-theme/main/media/previews/preview-wannacry.png" />
  <img width="48%" src="https://raw.githubusercontent.com/vandalsoul/dedsec-grub2-theme/main/media/previews/preview-legion.png" />
  <img width="48%" src="https://raw.githubusercontent.com/vandalsoul/dedsec-grub2-theme/main/media/previews/preview-unite.png" />
  <img width="48%" src="https://raw.githubusercontent.com/vandalsoul/dedsec-grub2-theme/main/media/previews/preview-wrench.png" />
  <img width="48%" src="https://raw.githubusercontent.com/vandalsoul/dedsec-grub2-theme/main/media/previews/preview-hype.png" />
</p>
