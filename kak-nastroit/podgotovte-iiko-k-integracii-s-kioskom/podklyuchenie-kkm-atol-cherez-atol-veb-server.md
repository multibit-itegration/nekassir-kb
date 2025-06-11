# Подключение ККМ АТОЛ через АТОЛ веб-сервер

Важно Последняя версия драйвера АТОЛ, в которой поддерживается Web-сервер - 10.9.5.0. Более новые версии драйвера содержат другой компонент - web-requests.

[Скачать драйвер ККМ АТОЛ v.10.9.5.0 с web-сервер](https://gbsmarket.ru/fls/drajver-onlajn-kass-kkm-kkt-atol-versii-10-9-5-0-s-podderzhkoj-web-server/)

Запустите скачанный файл, дважды кликнув на него.

Нажмите “Далее” и примите условия пользовательского соглашения.&#x20;

На странице параметров установки необходимо включить опцию “Web-сервер”, наименование может быть "Web-requests"

<figure><img src="../../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

Нажимайте “Далее” для продолжения установки. После успешной установки на последней странице включите опцию “Настроить Web-сервер” и нажмите “Готово”.

### Создание пользователя <a href="#nastroika-veb-servera" id="nastroika-veb-servera"></a>

Для добавления пользователя, введите в командную строку, запущенную от имени администратора следующую команду&#x20;

"C:\Program Files (x86)\ATOL\Drivers10\KKT\web\atol-fptr-web-requests-users.exe" add admin Admin0123456789 pause

Данной командой, мы создаем пользователя для настроек веб-сервера:

Логин - admin\
Пароль - Admin0123456789

### Настройка веб-сервера <a href="#nastroika-veb-servera" id="nastroika-veb-servera"></a>

После установки драйвера перейдите в браузер и введите адрес [http://127.0.0.1:16732/](http://127.0.0.1:16732/)

Если страница не открывается, нужно перейти по пути&#x20;

Program Files(x86) -> ATOL -> Drivers10 -> KKT -> web

Найти службу "restart-web-request" запустить, обновить страницу

В браузере должна открыться страница настроек Web-сервера АТОЛ. Выглядит она примерно так:

<figure><img src="../../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>

#### Добавление ККМ <a href="#dobavlenie-kkm" id="dobavlenie-kkm"></a>

Для добавления вашей ККМ нажмите кнопку “Добавить” на вкладке “Устройства”

<figure><img src="../../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>

В открывшемся окне введите идентификатор ККТ и название, могут быть любыми

<figure><img src="../../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>

После ввода информации нажмите “Добавить”. Страница обновится и на ней будет отображаться только что добавленная ККМ.

<figure><img src="../../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

В списке устройств включите необходимую ККМ

<figure><img src="../../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>
