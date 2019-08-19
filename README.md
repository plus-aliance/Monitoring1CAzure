# 1C in Azure + Monitoring 1C Azure Log Analytics
Мониторинг 1С с использованием Azure Monitor

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fplus-aliance%2FMonitoring1CAzure%2Fmaster%2Fazuredeploy.json%3Ftoken%3DAL4YA5T546RPE2FQSVGMU525LI7P4" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

## Обзор

Конструктивно сервис строится на аналитике событий, которые формирует 1С и систем, на которых 1С базируется. Azure Monitor позволяет отображать аналитическую информацию на заранее настроенных дашбордах. 

Решение состоит из двух модулей:
* Разворачивающаяся из шаблона область Azure Monitor на базе Log Analytics
* Модуль мониторинга 1С на базе модуля интеграции обработки 1С

## Порядок установки

Для развертывания решения необходимо выполнить следующие шаги:

1. Нажмите кнопку «Deploy to Azure» для вызова процедуры развертывания шаблона

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fplus-aliance%2FMonitoring1CAzure%2Fmaster%2Fazuredeploy.json%3Ftoken%3DAL4YA5T546RPE2FQSVGMU525LI7P4" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

2. Заполните необходимые параметры



3. После завершения установки сохраните атрибуты для настройки модуля обработки 1С



4. Скачайте и откройте в Конфигураторе 1С модуль AzureMonitor.epf.



Детальная информация по работе с модулями внешней обработки: http://v8.1c.ru/overview/Term_000000601.htm 

Для получения исходного модуля необходимо <a href="https://abilitygroup.ru/contacts/" target="_blank">обратиться к разработчикам</a>.


5. Укажите параметры соединения с развернутым шаблоном



6. Задайте расписание выполнения внешней обработки



## Дополнительная информация

Для просмотра подробной информации перейдите по ссылке:  
https://www.plus-aliance.ru/

<a href="https://www.plus-aliance.ru" target="_blank">
    <img src="https://www.plus-aliance.ru/include/logo-company.png"/>
</a>

