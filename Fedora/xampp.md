## Запуск
```
sudo chmod 777 /opt/lampp
```
```
sudo /opt/lampp/manager-linux-x64.run
```
Для  ярлык, нужно в папке /usr/share/applications/
создать текстовым редактор с правами рута файл с именем и расширением: xampp.desktop

```
[Desktop Entry]
Version=1.0
Name=XAMPP
Comment=Менеджер управления XAMPP
Exec=gksudo /opt/lampp/manager-linux-x64.run
Icon=/opt/lampp/htdocs/dashboard/images/xampp-logo.svg
Terminal=false
Type=Application
Categories=Network;Internet;Development;
```



[XAMPP](https://www.apachefriends.org/ru/faq_linux.html)
