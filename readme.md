Для обновления на роутере через System Shell:

    rm /var/wwwext/custom.css
    wget https://raw.githubusercontent.com/MrSTILAR/DarkTheme/master/custom.css -P /var/wwwext/

Код для WAN Up, чтобы после перезагрузки восстанавливалась тема:

    wget https://raw.githubusercontent.com/MrSTILAR/DarkTheme/master/custom.css -P /var/wwwext/

