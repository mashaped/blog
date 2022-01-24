# Compare Green API and official API
^^September 17, 2020^^

![Сравниваем Green API и официальный API](assets/sravnivaem-green-api-i-officialnij-api.png)

In this article, we will talk about how to connect for free the WhatsApp messenger to your account system and start sending messages to your clients, what options of integration with the messenger exist, pros and cons of each option.

The popularity of the WhatsApp messenger is increasing, along with that the need for business communications with their clients is also going up. A bit earlier we have already discussed how to use WhatsApp for [chatbots](kak-besplatno-napisat-chatbota-whatsapp.md) implementation. This article will cover what methods of integration with the messenger exist, their pros and cons.

Your company is growing, and sending messages to each client manually becomes cost prohibitive. You do already use CRM to automate part of your business processes, let us say, "1C", but you still interact with your clients in manual mode. Firstly, manual mode takes a lot of time, and secondly, it prevents you from systematizing and saving dialogues with a certain client in relation to a service, order, or product. After a while, the gazillion of chats becomes difficult to navigate.

The proper solution would be to integrate your account system with the WhatsApp messenger. After customizing the integration, all correspondence with clients will be available from the program. It will be well-ordered, and each dialogue will be linked to a contract, product, or order. It will become possible to send newsletters to clients directly from the database in automatic mode.

## How to customize the integration with WhatsApp?

At the moment, there are two ways to integrate with the messenger: the ``official`` way and the ``unofficial`` one. Below we will cover the pluses and minuses of each way. The issue of comparing official and unofficial WhatsApp has also been considered in the article [How to write a WhatsApp chatbot for free](kak-besplatno-napisat-chatbota-whatsapp.md).

## WhatsApp Business API (official way of integration)

In 2019, Facebook released the [WhatsApp Business API](https://developers.facebook.com/docs/whatsapp/) for integration with its messenger. However, it is impossible to connect to the gateway directly. You can do it only via agents. The list of official Facebook partners has been published on the [company's website](https://www.facebook.com/business/partner-directory/search?platforms=whatsapp&solution_type=messaging&ref=wa2019t1). To get access, you will have to pay a monthly subscription fee, additionally pay for each outgoing template message, go through a bureaucratic approval procedure which will take for about 2 months. One more principal restriction is the prohibition on sending user-defined messages. You may only send a pre-agreed template message. Template messages cannot contain advertising, and you may not use them for promotion. Nevertheless, there are benefits of the official WhatsApp channel that include the high speed of sending and receiving messages, an unlimited number of messages per day, the removal of all risks of account ban, as well as the opportunity to carry on a dialogue with a client for free within 24 hours from the moment of the last incoming message from this client.

## Green-API (unofficial way of integration)

Before the release of the official WhatsApp Business API gateway, businesses were badly in need of integration with the messenger. . Therefore, the [Green-API](https://green-api.com/) service was developed. С. It allows you to integrate with WhatsApp and supports all the scenarios that are provided in the official channel and offers even more than these scenarios. The main benefit of [Green-API](https://green-api.com/) is the absolute removal of all restrictions:

* you may send any message first and forget about templates
* subscription fee is 30 times lower than that of the official channel
* messages are not charged, so you don't have to pay anything extra in excess of the subscription fee
* there is no long bureaucratic account approval procedure
* you may send informational and advertising newsletters to clients from your database

At the same time, using an unofficial gateway has its weaknesses. Since the gateway is unofficial, there is always a risk of losing the option to use WhatsApp on your phone number - in other words, getting banned. The phone number can still be used for making calls and sending SMS, but it won’t be possible anymore to use the number for the WhatsApp application, as it will be blocked.

Losing contact via WhatsApp with clients is impermissible for any business, that is why, we have developed a system of various filters in our service that protect your number from ban. [Green-API](https://green-api.com/) will not let you perform actions that could lead to the risk of getting blocked. At the first sign of potential blocking, the system will suspend sending messages and notify your system (will send a webhook).

It should be noted that for the entire period of work, since 2017, we have ``not had a single ban`` of a client number!

To summarize the above:

### WhatsApp Business API

* You may send only ``templates`` first
* Цена каждого исходящего сообщения по шаблону около ``4 руб``
* Отправлять сообщения бесплатно разрешено только в ``течение 24х часов`` с момента крайнего входящего сообщения от клиента
* Нельзя отправлять ``маркетинговые`` сообщения даже за плату
* Цена подписки около ``30к руб/мес``
* Итоговая цена с учетом трафика около ``80к руб/мес``
* Оформление документов и подключение ``2 месяца``
* ``Безлимитное`` количество сообщений в сутки
* Вероятность бана ``отсутствует``

### Green-API

* Можно отправлять первым ``любое сообщение``
* Все исходящие сообщения ``бесплатные``
* Можно отправлять ``маркетинговые`` сообщения
* Цена подписки ``1к руб/мес``
* Итоговая цена с учетом трафика ``1к руб/мес``
* Подключение ``за 1 минуту``
* Не более ``5000`` сообщений в сутки
* Вероятность бана ``отсутствует``, за счет системы умных ``фильтров``

## Выводы

Официальный канал WhatsApp Business API хорош и скоростью отправки/приёма сообщений, и безлимитным количеством сообщений в сутки, и красивым названием, и статусом, однако позволить его себе могут далеко не все. Из сравнительного анализа видно, что стоимость обслуживания официального канала суммарно обойдется организации порядка ``80.000 руб/мес``. При этом не будет возможности отправлять своим клиентам маркетинговую информацию. Иными словами, официальный канал WhatsApp использовать для продвижения своих услуг и увеличения продаж не получиться, даже за ``80.000 руб/мес``. Поэтому для небольших организаций, у которых каждый рубль на счету, отличным решением будет использовать сервис Green-API. За абонентскую плату ``690 руб/мес`` вы получаете возможность интегрировать сервисы своей компании с мессенджером WhatsApp, а наша система заботится о стабильности и безопасности интеграции и ``защищает ваш номер`` от блокировки.
