# How to write a WhatsApp chatbot for free
^^September 10, 2020^^

![Как бесплатно написать чатбота WhatsApp](assets/kak-besplatno-napisat-chatbota-whatsapp.png)

Here we will consider what options there are for writing a chatbot for the WhatsApp messenger, compare the options, and also discuss how to write and use a WhatsApp chatbot for free.

Nowadays, the issue of developing WhatsApp chatbots is of current interest. WhatsApp chatbots are widespread and in good demand. Businesses are ready to pay for the development of chatbots because, on the one hand, chatbots reduce costs by automating some of the everyday processes; on the other hand, chatbots significantly contribute to increasing sales, because they allow you to retain customers, as well as let you return your lost customers.

It’s obvious that to write a WhatsApp chatbot, you need a gateway, a messenger API. Not that long ago, Facebook released its official gateway - [WhatsApp Business API](https://developers.facebook.com/docs/whatsapp/). However, not everyone can access the WhatsApp Business API gateway. Access to the WhatsApp Business API is available only via official Facebook partners published on the company's [website](https://www.facebook.com/business/partner-directory/search?platforms=whatsapp&solution_type=messaging&ref=wa2019t1).


## WhatsApp Business API limitations

1. You must have a legal entity, such as an LLC, or to be an individual entrepreneur, to use the WhatsApp Business API.
2. You have to pay a monthly subscription fee of about 30.000 RUR/month.
3. You have to go through a long bureaucratic procedure for approval of the company’s account with Facebook – for about 3-4 weeks.
4. You can’t send whatever you want first, but only a template message, which is also to be pre-agreed with Facebook.
5. You have to pay for each outgoing template message apart at a price of approximately 4 RUR per message.

The above limitations ``shut the door`` on the use of the official WhatsApp Business API gateway for writing chatbots by individual programmers and startuppers. A programmer, as a rule, does not have his own legal entity, moreover he doesn’t’ even have an opportunity to pay a subscription fee of ``30.000 RUR/month``. And if one calculates the cost of sending each template message, then the total cost will be for about ``50.000 RUR/month`` at an average chatbot load. Such costs are beyond means for startuppers and entry-level programmers.

## What are alternatives to WhatsApp Business API

Можно поискать на github различные реализации WhatsApp API. Но к недостаткам такого решения можно отнести то, что придется разбираться в дебрях кода, который собственно не относиться к чатботу. Дополнительно потребуется оплачивать хостинг, чтобы модуль WhatsApp API работал и был доступен через Интернет.

Также надо понимать, что facebook постоянно вносит изменения в WhatsApp, поэтому библиотеки с github со временем перестают работать. Есть некоторый промежуток времени - день-два, в течение которого библиотека будет в нерабочем состоянии. Иными словами, ваш чатбот не будет работать до тех пор, пока автор кода не выпустит новый патч на github. И такие обновления случаются по три-четыре раза в год и как правило внезапно. Приходится с нетерпением ждать патч в течение нескольких дней. А что, если патч не выйдет?

Хорошим решением будет использовать сервис GREEN-API для доступа к стабильному и быстрому WhatsApp API. Наш сервис предлагает ``бесплатный тариф для разработчиков``. Можно писать своего чатбота сколь угодно долго и при этом не платить ни копейки. А когда чатбот будет готов, то продать бот клиенту, а клиент уже заплатит.

Оба перечисленных выше способа использования WhatsApp API являются неофициальными. Иными словами, facebook не одобряет такое использование своего продукта и борется с подобного рода сервисами и реализациями.

## Какие риски при использовании неофициального шлюза WhatsApp API

``Риск один`` - аккаунт воцап будет заблокирован без возможности восстановления. При этом номер телефона останется, можно будет по-прежнему совершать звонки и отправлять SMS, однако использовать воцап на данном номере будет невозможно.

Однако, если вы пишите чатбота, то в этом случае все риски снимаются. Клиент пишет боту первым. Тем самым клиент косвенно соглашается вступить в диалог с ботом. Если клиент пишет вам первым, то вы никогда не получите бана. Также можно писать первым и самому, но в разумных пределах разумеется.

За всё время работы, начиная с 2017 года, у нас не было ``ни одного бана``, т.к. сервис используется преимущественно для чатботов и для интеграции с различными CRM (1С, Битрикс24, amoCRM и др). Также в нашем сервисе предусмотрен механизм защиты номера от бана. Вы можете быть уверены в том, что ваш номер никогда не заблокируют. Система остановит отправку сообщений и отправит уведомление (вебхук) при первых признаках вероятности бана.

## Вывод

Писать чат-ботов на официальном WhatsApp Business API могут позволить себе только большие ИТ-компании, которые работают с крупными заказчиками, для которых средний чек для чат-бота в ``50.000 руб/мес`` не составляет проблем. Для мелкого и среднего бизнеса решением будет использовать неофициальный WhatsApp API с риском блокировки аккаунта, но по цене в десять раз ниже. По мере того, как бизнес начнет понимать эффективность чат-бота можно говорить о переходе с неофициального канала на официальный.
Для индивидуальных разработчиков и стартап-команд, однозначно, лучшим решением является использование неофициальных поставщиков WhatsApp API, тем более риски блокировки номера в нашем сервисе GREEN-API полностью исключены. 
