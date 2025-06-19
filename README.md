# mcp-1.12.2
mc coder pack for 1.12.2
1. Скачайте mcp940.zip и разархивируйте в пустую папку своего будущего проекта на рабочем столе.
2. Установите чистый майнкрафт 1.12.2 (Можно через TL, TL Legacy, оффициальный и другие лаунчеры)
3. Скопируйте все файлы из .minecraft в папку jars
4. Распакуйте mcp-1.12.2-srg.zip в папку conf
5. Редактируйте файлы так:
```conf/version.cfg
[VERSION]
MCPVersion = 9.42
ClientVersion = 1.12.2
ServerVersion = 1.12.2
```
6. Вроде готово, запустите decompile.bat
7. После декомпиляции client, извлеките содержимое Optifine C6.zip в src/minecraft/
8. Запускай eclipse ide и вставь путь до папки eclipse
Что-то вроде "C:\Users\Ivan\Desktop\PenisClient\eclipse"
И открывай проект, дальше дело за малым, настрой рабочую среду и java в eclipse
