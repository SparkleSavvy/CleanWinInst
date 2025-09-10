# <img width="32" height="32" alt="ic" src="https://github.com/user-attachments/assets/bd576e3b-c712-4ae4-9a39-13a88fa83639" /> Ultimate Windows Unattended Installation & Customization Script [ENG]

Welcome to the ultimate, all-in-one solution for deploying a clean, bresh, and highly customized Windows installation — completely unattended. Forget about tedious post-installation tweaking. This script does it all for you, from disabling bloatware to optimizing system performance and personalizing your desktop experience.

Built using the powerful `unattend.xml` framework and enhanced with custom PowerShell, VBScript, and registry tweaks, this configuration turns a vanilla Windows setup into your ideal operating system — automatically.

Perfect for system administrators, IT professionals, homelab enthusiasts, or anyone who loves a clean, fast, and distraction-free Windows environment.

---

## <img width="30" height="30" alt="moon-stars" src="https://github.com/user-attachments/assets/9ac3361b-2726-425b-9cd9-4f611d35b3c7" /> Key Features

### <img width="30" height="30" alt="broom" src="https://github.com/user-attachments/assets/228b3c18-5e58-4e10-a119-3cdc9e4fba3c" /> **Bloatware Removal**
*   **Prevents installation** of dozens of unwanted built-in apps (Cortana, Copilot, Xbox, Mail, Calendar, OneDrive, Sticky Notes, Weather, etc.).
*   Removes optional Windows **Features** (Remote Desktop Connection, Recall, Snipping Tool).
*   Removes system **Capabilities** (Internet Explorer, Windows Media Player, Fax and Scan, Math Recognizer, etc.).

### <img width="30" height="30" alt="shield" src="https://github.com/user-attachments/assets/5c688a51-8a1b-4cda-8a4f-29f7664851ba" /> **Privacy & Security Hardening (Your Way)**
*   **Disables Windows Defender** during installation for maximum flexibility (use at your own risk).
*   Disables **SmartScreen**, **Fast Startup**, **System Restore**, **Device Encryption**, and **Windows Update**.
*   Blocks **Bing integration**, **app suggestions**, **news and interests**, and telemetry where possible.
*   Prevents automatic reboots after updates.

### <img width="30" height="30" alt="palette" src="https://github.com/user-attachments/assets/1478ea54-2ef9-4346-995c-854aeeae4f79" /> **Visual & UI Customization**
*   Sets a **Dark Theme** for both System and Apps.
*   Applies a custom **Accent Color** (`#8080FF` - a nice blue).
*   Configures the **Taskbar**: Left-aligned, hides search, hides Task View, shows all tray icons.
*   Creates an **empty Start Menu** with no tiles or pins.
*   Uses **Classic Context Menu** and shows **File Extensions**.
*   Launches File Explorer to **"This PC"** instead of "Quick Access".

### <img width="30" height="30" alt="gear-six" src="https://github.com/user-attachments/assets/33348173-6dac-48ea-a766-5f9c6856c77a" /> **System & Performance Optimization**
*   Enables **Long File Paths** support.
*   Allows **PowerShell Scripts** to run (`RemoteSigned` policy).
*   Disables last access timestamp for files (`DisableLastAccess`).
*   Bypasses TPM, Secure Boot, and RAM checks for installation on older or unsupported hardware.
*   Sets Active Hours to prevent disruptive updates.
*   Installs **VMware Tools** automatically if the ISO is attached.

### <img width="30" height="30" alt="user" src="https://github.com/user-attachments/assets/8c27a820-b281-42ee-880d-f3d76b71cf78" /> **User & Account Setup**
*   Creates a local administrator account named **"User"** with no password (for initial setup).
*   Enables **Auto-Logon** for the first boot only.
*   Applies all customizations to the **Default User profile**, so every new user gets the same clean setup.
*   Sets the system **Geolocation** to Russia (ID 203) and configures keyboard layouts for US and Russian.

### <img width="30" height="30" alt="planet" src="https://github.com/user-attachments/assets/a0d1e829-3dee-4347-851b-45b02336d7b7" /> **Regional & Language Settings**
*   Primary UI Language: **English (United States)**
*   Additional Keyboard Layout: **Russian**
*   System Locale: **en-US**
*   Time Zone: **Russian Standard Time**

---

## <img width="30" height="30" alt="book" src="https://github.com/user-attachments/assets/cd43411d-536e-49ab-a0ce-17931ec549af" /> How to Use

1.  **Download** the `unattend.xml` file.
2.  Place it in the root directory of your Windows installation media (USB drive or extracted ISO folder), alongside the `sources`, `boot`, etc., folders.
3.  Boot from the media. The Windows Setup will automatically detect and apply all configurations.
4.  Sit back, relax, and watch your perfectly customized Windows install itself!

> **Important**: The script includes a command to download and execute a script from `https://get.activated.win` during the first user logon. This is typically used for activation. **Use this only if you trust the source.** You can easily remove or modify this command in the XML if needed.

---

## <img width="30" height="30" alt="seal-warning" src="https://github.com/user-attachments/assets/af8ec666-e682-4600-ae22-e3b69e2f570b" /> Disclaimer

This script is provided "as is" for educational and convenience purposes. It makes significant changes to your Windows installation.

*   Always test in a virtual machine or non-critical system before deploying to production.

Use responsibly!

---

## <img width="30" height="30" alt="handshake" src="https://github.com/user-attachments/assets/89ec00de-c763-480d-8c8a-c2201c999b53" /> Contributing

Found a bug or have an idea for an awesome new feature? Feel free to open an [issue](https://github.com/SparkleSavvy/CleanWinInst/issues) or submit a pull request.

---

# <img width="30" height="30" alt="ic" src="https://github.com/user-attachments/assets/bd576e3b-c712-4ae4-9a39-13a88fa83639" /> Универсальный скрипт для автоматической установки и настройки Windows [RUS]

Добро пожаловать в универсальное, комплексное решение для развертывания чистой, свежей и глубоко кастомизированной установки Windows — полностью в автоматическом режиме. Забудьте о рутинной настройке после установки. Этот скрипт сделает всё за вас: от удаления ненужного софта до оптимизации производительности и персонализации интерфейса.

Построенный на мощной основе `unattend.xml` и дополненный кастомными скриптами PowerShell, VBScript и правками реестра, этот конфиг превращает стандартную установку Windows в вашу идеальную операционную систему — полностью автоматически.

Идеально подходит для системных администраторов, ИТ-специалистов, энтузиастов домашних лабораторий или всех, кто ценит чистую, быструю и свободную от отвлекающих элементов среду Windows.

---

## <img width="30" height="30" alt="moon-stars" src="https://github.com/user-attachments/assets/9ac3361b-2726-425b-9cd9-4f611d35b3c7" /> Ключевые Возможности

### <img width="30" height="30" alt="broom" src="https://github.com/user-attachments/assets/228b3c18-5e58-4e10-a119-3cdc9e4fba3c" /> **Удаление Ненужного Софта (Bloatware)**
*   **Предотвращает установку** десятков встроенных приложений (Cortana, Copilot, Xbox, Почта, Календарь, OneDrive, Записки, Погода и т.д.).
*   Удаляет дополнительные **Компоненты Windows** (Подключение к удаленному рабочему столу, Recall, Ножницы).
*   Удаляет системные **Возможности** (Internet Explorer, Проигрыватель Windows Media, Факс и сканирование, Распознаватель математики и т.д.).

### <img width="30" height="30" alt="shield" src="https://github.com/user-attachments/assets/5c688a51-8a1b-4cda-8a4f-29f7664851ba" /> **Приватность и Безопасность (На Ваш Вкус)**
*   **Отключает Защитник Windows** во время установки для максимальной гибкости (используйте на свой страх и риск).
*   Отключает **SmartScreen**, **Быстрый запуск**, **Восстановление системы**, **Шифрование устройства** и **Центр обновления Windows**.
*   Блокирует интеграцию с **Bing**, **предложения приложений**, **новости и интересы** и телеметрию, где это возможно.
*   Предотвращает автоматические перезагрузки после обновлений.

### <img width="30" height="30" alt="palette" src="https://github.com/user-attachments/assets/1478ea54-2ef9-4346-995c-854aeeae4f79" /> **Визуальная Настройка и Интерфейс**
*   Устанавливает **Темную тему** для системы и приложений.
*   Применяет пользовательский **Цвет акцента** (`#8080FF` - приятный синий).
*   Настраивает **Панель задач**: выравнивание по левому краю, скрытие поиска и кнопки "Представление задач", отображение всех значков в трее.
*   Создает **пустое меню "Пуск"** без плиток и закрепленных элементов.
*   Использует **Классическое контекстное меню** и показывает **расширения файлов**.
*   Запускает Проводник с открытием раздела **"Этот компьютер"**, а не "Быстрый доступ".

### <img width="30" height="30" alt="gear-six" src="https://github.com/user-attachments/assets/33348173-6dac-48ea-a766-5f9c6856c77a" /> **Оптимизация Системы и Производительности**
*   Включает поддержку **длинных путей к файлам**.
*   Разрешает выполнение **скриптов PowerShell** (политика `RemoteSigned`).
*   Отключает запись временной метки последнего доступа к файлам (`DisableLastAccess`).
*   Обходит проверки TPM, Secure Boot и ОЗУ для установки на старое или неофициально поддерживаемое оборудование.
*   Настраивает "Активные часы" для предотвращения обновлений в неудобное время.
*   Автоматически устанавливает **VMware Tools**, если образ подключен.

### <img width="30" height="30" alt="user" src="https://github.com/user-attachments/assets/8c27a820-b281-42ee-880d-f3d76b71cf78" /> **Настройка Пользователя и Аккаунта**
*   Создает локальную учетную запись администратора с именем **"User"** без пароля (для первоначальной настройки).
*   Включает **Автоматический вход** только при первой загрузке.
*   Применяет все настройки к профилю **Пользователя по умолчанию**, поэтому каждый новый пользователь получит ту же чистую конфигурацию.
*   Устанавливает **геолокацию** системы в Россию (ID 203) и настраивает раскладки клавиатуры для английского и русского языков.

### <img width="30" height="30" alt="planet" src="https://github.com/user-attachments/assets/a0d1e829-3dee-4347-851b-45b02336d7b7" /> **Региональные настройки и Язык**
*   Основной язык интерфейса: **Английский (США)**
*   Дополнительная раскладка клавиатуры: **Русская**
*   Локаль системы: **en-US**
*   Часовой пояс: **Российское стандартное время**

---

## <img width="30" height="30" alt="book" src="https://github.com/user-attachments/assets/cd43411d-536e-49ab-a0ce-17931ec549af" /> Как Использовать

1.  **Скачайте** файл `unattend.xml`.
2.  Поместите его в корневую директорию вашего установочного носителя Windows (USB-флешка или распакованная папка ISO), рядом с папками `sources`, `boot` и т.д.
3.  Загрузитесь с этого носителя. Программа установки Windows автоматически обнаружит и применит все конфигурации.
4.  Откиньтесь на спинку кресла, расслабьтесь и наблюдайте, как ваша идеально настроенная Windows устанавливается сама!

> **Важно**: Скрипт содержит команду для загрузки и выполнения скрипта с `https://get.activated.win` при первом входе пользователя. Обычно это используется для активации. **Используйте это только в том случае, если вы доверяете источнику.** Вы можете легко удалить или изменить эту команду в XML-файле, если это необходимо.

---

## <img width="30" height="30" alt="seal-warning" src="https://github.com/user-attachments/assets/af8ec666-e682-4600-ae22-e3b69e2f570b" /> Предупреждение

Этот скрипт предоставляется "как есть" в образовательных и удобных целях. Он вносит значительные изменения в вашу установку Windows.

*   Всегда тестируйте в виртуальной машине или на некритичной системе перед развертыванием в рабочей среде.

Используйте с умом!

---

## <img width="30" height="30" alt="handshake" src="https://github.com/user-attachments/assets/89ec00de-c763-480d-8c8a-c2201c999b53" /> Внесение своего вклада

Нашли ошибку или есть идея для новой функции? Не стесняйтесь открыть [issue](https://github.com/SparkleSavvy/CleanWinInst/issues) или отправить запрос на включение внесенных изменений.
