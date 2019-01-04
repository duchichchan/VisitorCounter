Счётчик посетителей
=====================
Однофайловый счетчик посетителей на PHP с использованием БД SQLite3. Для использования достаточно заинклюдить скрипт счетчика в любом месте страницы:

```php
require_once 'counter.php';
```

Файл базы данных вместе с содержимым будет создан автоматически при отсутствии.
***
Для отключения возврата количества посетителей за день сменить значение соответствующей константы:

```php
define('RETURN_VISITORS_OF_TODAY', true);
```