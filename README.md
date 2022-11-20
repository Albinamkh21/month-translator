# Month name translator

## Требования
- PHP 7.4

## Установка

```bash
$ composer require albinamkh/month-translator
```

## Использование

```php
$monthName = new MonthTranslator();
echo $monthName->translate(2,'ru'); // Февраль