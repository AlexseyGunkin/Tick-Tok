# Настройка интеграции с TikTok LeadAds

## Навигация
* [Описание Виджета ](#Описание-Виджета)
* [Создание Интеграции и нюансы ](#Создание-Интеграции-и-нюансы)
* [Проверка интеграции виджета ](#Проверка-интеграции-виджета)
* [Типовые ошибки](#Типовые-ошибки)
* [Инструкция пользователя](#Инструкция-пользователя)



## Описание Виджета
Виджет обратного звонка позволяет автоматически инициировать звонки клиентам, которые заполнили форму в TikTok и оставили в ней свой номер телефона.
Для этого необходимо : 

1) Аккаунт в ТТ.
2) Настроить рекламные кампании и объявления в TikTok For Business, настроить мгновенную форму, если у Вас они еще не настроены.
3) Активный виджет в личном кабинете CallKeeper.
Подробнее о настройках рекламных кампаний и настройке TikTok Lead Generation  можно прочитать в справочном центре TikTok. [https://ads.tiktok.com/help/article?aid=10001625/](https://ads.tiktok.com/help/article?aid=10001625/)
4) Настроить интеграцию 

## Создание Интеграции и нюансы


**Есть ограничения по уровню доступа** :
- Интеграция возможна только с аккаунтом, которому предоставлен уровень доступа «Администратор».
- У Вас должен быть доступ к привилегиям: **Ads Management;Creative Management;Lead Management**.
Доступы можно проверить на **TikTok Business Centre** : [https://business.tiktok.com/](https://business.tiktok.com/)

![Рис.1](images/1.png)

Для интеграции виджета необходимо:
Зайти в личный кабинет CallKeeper. Во вкладке «Социальные Сети» выберите TikTok LeadAds.

![Рис.2](images/22.png)

В открывшейся вкладке нажмите «Подключить».

![Рис.3](images/33.png)

При подключении аккаунта в новом окне Tik-tok уточнит, под каким аккаунтом Tik-tok вы хотите войти.

После этого откроется первое окно, на котором будут отображены все страницы Tik-tok, подключенные к аккаунту, под которым вы войти.

На следующем шаге вам предложат выбрать действия, которые приложение CallKeeper сможет совершать со страницами, которые вы уже выбрали.

Обе настройки рекомендуется сделать активными.

После этого появится окно настроек страниц CallKeeper. Все страницы, выбранные в этом окне, будут привязаны к вашему аккаунту в CallKeeper.

Все созданные формы для выбранной страницы загрузятся в конструкторе, и вам останется выбрать соответствующий виджет, из которого берутся все настройки

Далее обязательный выбор поля, где содержится номер клиента, и по желанию можно добавить произвольные значения UTM-меток и текст для проговаривания.

##  Проверка интеграции виджета

После того, как вы настроили ваши кампании и добавили формы лидогенерации, вы можете их проверить до активации кампании.

**Обратите внимание!** В приложении, одним пользователем можно проверить определенную форму только один раз.


Вам необходимо перейти в список объявлений и кликнуть на свернутое меню рядом с "Просмотр данных"
После, в появившимся меню выберите пункт "Preview".

![Рис.5](images/5.png)

Откроется окно настройки предварительного просмотра на телефоне.

![Рис.6](images/6.png)

Будет доступно 2 варианта проверки:

1. Через QR-code. 

 Необходимо на вашем устройстве, где установлено приложение TikTok перейти в настройки профиля, перейти в настройки конфиденциальности и выбрать пункт QR-код. Далее в правом верхнем углу нажать на сканирование кода и отсканировать код из рекламного объявления.
После просмотра нескольких роликов, появится рекламный ролик с формой лидогенерации.

2. Через идентификатор пользователя.

 Необходимо на вашем устройстве, где установлено приложение TikTok перейти в настройки профиля, перейти в настройки конфиденциальность.
Далее надо прокрутить все настройки аккаунта до места, где написана версия вашего приложения.
После нескольких кликов на область рядом с версией приложения появятся системные данные. Нам необходимо получить UserId.
Данный UserId вводится в окне предварительного просмотра в рекламном кабинете
После просмотра нескольких роликов, появится рекламный ролик с формой лидогенерации.

## Метрики Виджета

Заходя в личный кабинет CT раздел "звонки" на экране будет предоставлена информация по обратному звонку.
Где указана информация:
- Статус звонка
- Время звонка
- Номер клиента
- Запись разговора
- Название офиса
- Теги присвоенные к звонку 
- Название компании 
- Общее количество звонков
- Номер менеджера
- Интеграция с которой был сделан переход
- Номер колтрегинга 
и тругие метрики указанные на скриншоте ниже.
Вся информация по звонку обображается в личном кабинете, её можно отфильтровать по нужным параметрам на странице ЛК СТ вкладка "звонки" - Фильтр.

![Рис.7](images/метки.png)


## Типовые ошибки

 Ошибка : Нет доступа к аккаунту пользователя или не хватает прав для работы интеграции. 

Вариант исправления : Обновите токен в настройках интеграции TikTok Leads и включите виджет.

 Ошибка : Виджет настроен неверно.

Вариант исправления : Проверить настройки виджета или повторить настройку.

 Ошибка : Удалена интеграция ID..., которая использовалась в виджете №...

Вариант исправления : Создайте новую интеграцию с TikTok Leads и выберите ее в настройках виджета.

## Инструкция пользователя

 При просмотре видео в Tik-tok у пользователя будет появляться рекламное сообщение при нажатие на которое появится форма для ввода данных.
 
Алгоритм действий пользователя:
- нажать на появившуюся рекламу.
- заполнить информацию в окне ввода.
- получить обратный звонок.


[Вернуться к оглавлению](#навигация)

[Вернуться на главную](/README.md/#documentation)