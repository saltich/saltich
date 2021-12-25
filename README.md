
<h2>We introduce a NEW <a href="https://github.com/Surzhikov/Telegram-Site-Helper-2.0">Telegram-Site-Helper 2.0</a></h2>
<h2>Мы представляем НОВЫЙ <a href="https://github.com/Surzhikov/Telegram-Site-Helper-2.0">Telegram-Site-Helper 2.0</a></h2>

# TelegramSiteHelper
Telegram Bot and chat to create WebSite Helper (PHP+JS(JQuery2)+HTML+CSS)<br>
Телеграм бот и чат для создания Чата-помощника на сайт<br>

#Attention!
If you want new version of TelegramSiteHelper (each customet in new chatroom)
Please Twitter tweet: 
`@telegram #telegramPleaseMakeBotPossibleToCreateGroup`

#Внимание!
Друзья, если вы хотите новый более удобный чат (с разделением менеджеров по чатам)
Пожалуйста сделайте tweet в Твиттере:
`@telegram #telegramPleaseMakeBotPossibleToCreateGroup`




[How to install and setup (english)](https://github.com/Surzhikov/TelegramSiteHelper/wiki/HOW-TO-INSTALL-(English))
<br>
[Как установить и настроить (по-русски)](https://github.com/Surzhikov/TelegramSiteHelper/wiki/%D0%9A%D0%90%D0%9A-%D0%A3%D0%A1%D0%A2%D0%90%D0%9D%D0%9E%D0%92%D0%98%D0%A2%D0%AC)

<br>
<br>
Donate by <b>PayPal</b> to andrey.surzhikov@gmail.com<br>
Donate by <b>YandexMoney</b> 4100168691358<br>
Donate by <b>BTC</b> 1HKb4L5YTQjcH6HYYEk1dXsuUWWmNYRkDj<br>
Donate by <a href="https://money.yandex.ru/embed/donate.xml?account=4100168691358&quickpay=donate&payment-type-choice=on&mobile-payment-type-choice=on&default-sum=100&targets=%D0%9F%D0%BE%D0%B4%D0%B4%D0%B5%D1%80%D0%B6%D0%BA%D0%B0+%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0&target-visibility=on&project-name=Telegram+Site+Helper+2%2F0&project-site=https%3A%2F%2Fgithub.com%2FSurzhikov%2FTelegram-Site-Helper-2.0&button-text=01&successURL=https%3A%2F%2Fraw.githubusercontent.com%2FSurzhikov%2FTelegram-Site-Helper-2.0%2Fmaster%2Fthank-you.txt"><b>Visa</b>/<b>Mastercard</b></a><br><br>


The general scheme of ideas:<br>
<img src="https://habrastorage.org/files/5fa/cc9/048/5facc9048483406ab0eba3820cce44fa.png"><br>

That's how it happens: <br>
1. Online users write to chat <br>
2. Post it flies on your server <br>
3. From there Telegram-bot sends it to the correct manager <br>
4. The manager responds by Telegram <br>
5. Bot sends a message back to chat <br>
 <br>
## Screenshot:<br>
<img src="https://habrastorage.org/files/cbf/50e/458/cbf50e45825a48ce92b8eac34ba7d875.png"><br>

## Requirement:<br>
You must've Telegram Account. If you don't have make one using <a href="https://web.telegram.org">https://web.telegram.org/</a>).

## Todo:<br>
1. Download or clone this repo
2. Create a new bot. Add user <a href="http://telegram.me/botfather">@BotFather</a> and follow this step to  <a href="https://core.telegram.org/bots#create-a-new-bot">create a new bot</a><br>
<img src="https://habrastorage.org/files/6de/a35/0f7/6dea350f710b4afe9c03f94702aecf49.png"><br>
2. Edit configuration in «<B>telegramSiteHelper/tbConfig.php</B>»<br>
3. Upload everything to your hosting/server/VPS<br>
4. «<B>telegramSiteHelper/tbServer.php</B>» should run continuously, because it is a server. Add the cron job with a period of 1 every minute for this script. If the script fails, it will start again for a minute. It will be launched at the same time only one copy of the script.<br>
5. Try!<br>
6. Usage:<br>
<img src="https://habrastorage.org/files/cbf/50e/458/cbf50e45825a48ce92b8eac34ba7d875.png"><br>
* Add your bot to your contact list<br>
* Enter your manager password<br>
* Use command «/offline», «/online», «/exit»<br>

## Minuses: <br>
* Chat Who made "in haste" to start soon in the project. There are many loopholes, by which for example can be written in another chat room and peek's correspondence.
* Now, these problems do not disturb me, because chatting assistant site have been made to transfer important and sensitive information.
* When a manager and a lot of customers - can be confused whom to answer.
* ... I supplement of the comments

## Pros:<br> 
* It works!
* Free Forever and for any number of managers
* No need extra applications only telegrams, which is for all popular platforms
* You can rewrite and stylized chat as you want.
* Telegram is very fast
* ... I supplement of the comments

## What can be done: <br>
* Foolproof and work on security
* Smart distribution system communications between managers (now the bot sends a random message to the manager)
* Automatic responses from the bot when the manager was silent for a long time
* Add a name and a photo manager that is responsible chatting
* ... I supplement of the comments


## In the plans:<br>
* Admin panel with statistics 
* Work through webhook 

<br>

