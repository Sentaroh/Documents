## 1.Собранные данные
### 1.1.Данные, предоставленные пользователем в SMBSync3

Данные, предоставленные пользователем для использования SMBSync3, будут храниться в области хранения в приложении.
Однако имя учетной записи SMB, пароль учетной записи SMB, пароль ZIP и пароль приложения будут зашифрованы и сохранены.
<span style="color: red;"><u>Данные не будут отправлены вовне, пока не будет выполнена операция "1.4.Отправка или запись данных за пределы SMBSync3".</u></span>.

- Информация о файле (имя каталога, имя файла)
- Информация о сервере SMB (имя хоста/IP-адрес, номер порта, имя учетной записи, пароль учетной записи)
- Информация о файле ZIP (метод сжатия, метод шифрования, пароль шифрования)
- Параметры настройки приложений (предупреждающие сообщения, язык и размер шрифта и т.д.)
- Пароль приложения (пароль, используемый для аутентификации при запуске приложения, аутентификации при изменении настроек безопасности и т.д.)

### 1.2.Результат выполнения SMBSync3

Сохраните данные в области хранения в приложении, чтобы пользователь мог проверить результат выполнения SMBSync3.
<span style="color: red;"><u>Данные не будут отправлены вовне, пока не будет выполнена операция "1.4.Отправка или запись данных за пределы SMBSync3".</u></span>.

- Имя каталога, имя файла, статус выполнения
- Размер синхронизированных файлов, дата и время обновления файлов
- Информация об ошибках

### 1.3.Запись активности SMBSync3

Сохраните данные в область хранения в приложении, чтобы проверить результат выполнения SMBSync3 и задать вопрос разработчику.
<span style="color: red;"><u>Данные не будут отправлены вовне, пока не будет выполнена операция "1.4.Отправка или запись данных за пределы SMBSync3".</u></span>.

- Информация об устройстве (название производителя, название модели, версия ОС, точка монтирования, каталог для приложений, StorageAccessFramework, менеджер хранения, IP-адрес, включение/выключение WiFi, скорость соединения WiFi)
- Версия SMBSync3, параметры выполнения SMBSync3
- Имя каталога, имя файла, статус выполнения
- Размер синхронизированных файлов, дата и время обновления файлов
- Информация об отладке
- Информация об ошибках

### 1.4.Отправка или запись данных за пределы SMBSync3

Данные SMBSync3 не могут быть отправлены или записаны наружу, если пользователь не управляет ими.

- Нажмите кнопку [Share button] на вкладке History.
- Нажмите кнопку "Отправить разработчику" в разделе "Информация о системе".
- Нажмите кнопку "Отправить разработчику" в управлении журналом.
- Нажмите кнопку "Экспорт файла журнала" в управлении журналом для экспорта во внешнее хранилище.
- Выполнив команду "Экспорт списка задач" из меню, "1.1.Данные, предоставленные пользователем в SMBSync3" будут экспортированы.

### 1.5.Удалить данные, хранящиеся в SMBSync3

При удалении SMBSync3 сохраненные данные ("1.1.Данные, предоставленные пользователем в SMBSync3", "1.2.Результат выполнения SMBSync3", "1.3.Запись активности SMBSync3") будут удалены с устройства.
<span style="color: red;"><u>Однако данные, сохраненные во внешнем хранилище в результате взаимодействия с пользователем, не будут удалены.</u></span>

### 2.Разрешения, необходимые для запуска приложения

### 2.1.Фотографии, медиа, файлы
**прочитайте содержимое вашего USB-накопителя**.
**изменять или удалять содержимое USB-накопителя**.
Используется для синхронизации файлов и чтения/записи файлов управления.

### 2.2.Xранение

### 2.2.1.Android11 или более поздней версии.
**Весь доступ к файлам**.

Весь доступ к файлам** Используется для синхронизации файлов и чтения/записи файлов управления.

### 2.2.2.Android 10 или ранее
**прочитайте содержимое вашего USB-накопителя**.
**изменять или удалять содержимое USB-накопителя**.
Используется для синхронизации файлов и чтения/записи файлов управления.

### 2.3.Информация о подключении Wi-Fi
**просмотр подключений Wi-Fi**.
Используется для проверки состояния Wi-Fi, когда начинается синхронизация.

### 2.4.Другие
### 2.4.1.View network connections
Используйте этот параметр для проверки сетевых соединений при запуске синхронизации.
### 2.4.2.connect and disconnect from Wi-Fi
Эта функция используется для включения/выключения Wi-Fi для синхронизации по расписанию на Andoid 8/9.
### 2.4.3.Full network access
Используется для синхронизации по протоколу SMB через сеть.
### 2.4.4.Run at startup
Используется для выполнения синхронизации по расписанию.
### 2.4.5.Control vibration
Используется для уведомления пользователя о завершении синхронизации.
### 2.4.6.Prevent device from sleeping
Используется для запуска синхронизации из расписания или внешнего приложения.
### 2.4.7.Install shortcuts
Используется для добавления ярлыка запуска синхронизации на рабочий стол.