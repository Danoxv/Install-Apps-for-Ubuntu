# Установка приложений для бекенд разработки (Ubuntu)
#


<div>
 <img src="https://github.com/devicons/devicon/blob/master/icons/chrome/chrome-original.svg" style="text-align: center" title="Chrome" alt="Chrome"  width="80" height="80"/>&nbsp;
</div>

### https://www.google.com/intl/ru_ru/chrome/ 
* Перейдите в папку загрузки 
* Выберите соответсвующуюю программу 
* Нажмите "Установка приложений"


#
<div style="text-align: center">
 <img src="https://github.com/devicons/devicon/blob/master/icons/jetbrains/jetbrains-original.svg" title="jetbrains" alt="Toolbox"  width="80" height="80"/>&nbsp;
</div>

### https://www.jetbrains.com/ru-ru/toolbox-app/download/download-thanks.html?platform=linux 
* Перейдите в папку загрузки 
* Выберите соответсвующуюю программу и нажмите "Распаковать"
* Перейдите в папку с распакованным файлом и откройте терминал
* Введите ./jetbrains-toolbox
* Выберите и скачайте нужное IDE


#
<div style="text-align: center">
 <img src="https://github.com/devicons/devicon/blob/master/icons/docker/docker-original.svg" title="Docker" alt="Docker"  width="80" height="80"/>&nbsp;
</div>

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

#### Настройка
* `echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu \
  $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null`

#### Проверка работоспособности
* `sudo docker run hello-world`


#
<div style="text-align: center">
 <img src="https://insomnia.rest/images/insomnia-logo.svg" title="Insomnia" alt="insomnia"  width="" height="60"/>&nbsp;
</div>

### https://updates.insomnia.rest/downloads/ubuntu/latest?&app=com.insomnia.app&source=website
* Перейдите в папку загрузки
* Выберите соответсвующуюю программу
* Нажмите "Установка приложений"


#
<div style="text-align: center">
 <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/83/Telegram_2019_Logo.svg/768px-Telegram_2019_Logo.svg.png?20220331104809" title="Insomnia" alt="insomnia"  width="70" height="70"/>&nbsp;
</div>

### https://telegram.org/dl/desktop/linux
#### Распакуйте файл telegram.tar.xz
* `sudo tar -xpf telega.tar.xz`
* Выбирете в папке файл Telegram запустите его
