# Установка приложений для бекенд разработки (Ubuntu)
#


<div>
 <img src="https://github.com/devicons/devicon/blob/master/icons/chrome/chrome-original.svg" title="Chrome" alt="Chrome"  width="50" height="50"/>&nbsp;
</div>

### Установка Chrome 💡
### https://www.google.com/intl/ru_ru/chrome/ 
* Перейдите в папку загрузки 
* Выберите соответсвующуюю программу 
* Нажмите "Установка приложений"


#
<div>
 <img src="https://github.com/devicons/devicon/blob/master/icons/jetbrains/jetbrains-original.svg" title="jetbrains" alt="Toolbox"  width="50" height="50"/>&nbsp;
</div>

### Установка Toolbox 💡
### https://www.jetbrains.com/ru-ru/toolbox-app/download/download-thanks.html?platform=linux 
* Перейдите в папку загрузки 
* Выберите соответсвующуюю программу и нажмите "Распаковать"
* Перейдите в папку с распакованным файлом и откройте терминал
* Введите ./jetbrains-toolbox
* Выберите и скачайте нужное IDE


#
<div>
 <img src="https://github.com/devicons/devicon/blob/master/icons/docker/docker-original.svg" title="Docker" alt="Docker"  width="50" height="50"/>&nbsp;
</div>

### Установка Docker 💡
### https://docs.docker.com/engine/install/ubuntu/
##### Удалить старые версии
* `sudo apt-get remove docker docker-engine docker.io containerd runc`

#### Настройка репозитория 
* `sudo apt-get update`
* `sudo apt-get install \
  ca-certificates \
  curl \
  gnupg \
  lsb-release`

#### Добавление официального GPG-ключа Docker
* `sudo mkdir -p /etc/apt/keyrings`
* `curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg`

#### Настрока
* `echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu \
  $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null`

#### Проверка работоспособности
* `sudo docker run hello-world`


#
<div>
 <img src="https://insomnia.rest/images/insomnia-logo.svg" title="Insomnia" alt="insomnia"  width="" height="50"/>&nbsp;
</div>

### Установка Insomnia
### https://updates.insomnia.rest/downloads/ubuntu/latest?&app=com.insomnia.app&source=website
* Перейдите в папку загрузки
* Выберите соответсвующуюю программу
* Нажмите "Установка приложений"


---
#
<div>
 <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/83/Telegram_2019_Logo.svg/768px-Telegram_2019_Logo.svg.png?20220331104809" title="Insomnia" alt="insomnia"  width="60" height="60"/>&nbsp;
</div>

### Установка Telegram
### https://telegram.org/dl/desktop/linux
* Распакуйте файл telegram.tar.xz
* `sudo tar -xpf telega.tar.xz`
* Выбирете в папке файл Telegram запустите его


---
#
<div>
 <img src="https://github.com/devicons/devicon/blob/master/icons/php/php-original.svg" title="PHP" alt="PHP"  width="80" height="80"/>&nbsp;
</div>

### Установка PHP 💡
* `sudo apt update && sudo apt upgrade`
* `sudo apt install curl wget php-common php-cli php-gd php-mysql php-curl php-intl php-mbstring php-bcmath php-imap php-xml php-zip git unzip`
#### Проверка работоспособности
* `php -v`


---
#
<div>
 <img src="https://github.com/devicons/devicon/blob/master/icons/composer/composer-original.svg" title="Сomposer" alt="composer"  width="80" height="80"/>&nbsp;
</div>

### Установка Composer 💡
* `php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"`
* `php -r "if (hash_file('sha384', 'composer-setup.php') === '55ce33d7678c5a611085589f1f3ddf8b3c52d662cd01d4ba75c0ee0459970c2200a51f492d557530c71c15d8dba01eae') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"`
* `php composer-setup.php`
* `php -r "unlink('composer-setup.php');"`



---
#
<div>
 <img src="https://github.com/devicons/devicon/blob/master/icons/npm/npm-original-wordmark.svg" title="npm" alt="npm"  width="80" height="80"/>&nbsp;
</div>

### Установка npm и Node.js
##### Обновление пакетов
* `sudo apt update`
##### Установка  Node js репозитория
* `sudo apt install nodejs`
#### Установка менеджера пакетов npm
* `sudo apt install npm`
#### Проверка работоспособности 
* `nodejs -v`
* 
* `npm -v`
