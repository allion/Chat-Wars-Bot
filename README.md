# Chat-Wars-Bot
Бот для текстовой мморпг Chat Wars в Telegram

Работающие функции бота:
  - тратить всю выносливость в лес
  - арена каждый час с рандомным выбором места атаки и защиты
  - перехват корованов
  - атака/защита по приказу бота/игрока или автоматическая защита замка

Как запустить:<br />
  1) Устанавливаем telegram-cli по официальной инструкции [https://github.com/vysheng/tg]<br />
  2) Устанавливаем pip3: sudo apt-get python3-pip<br />
  2) Устанавливаем pytg для 3 питона: pip3 install pytg<br />
  3) Запускаем telegram-cli: ./telegram-cli --json -P 1338<br />
  4) Качаем этот скрипт и запускаем: `python3 ./main.py --admin "ваш ник" --order "ник игрока или бота, выдающего приказы" --castle "blue/red/black/white/yellow"`<br />
  
Команды боту от админа:<br />
    #help Список всех команд<br />
    #enable_bot - Включить бота<br />
    #disable_bot - Выключить бота<br />
    #enable_arena - Включить арену<br />
    #disable_arena - Выключить арену<br />
    #enable_les - Включить лес<br />
    #disable_les - Выключить лес<br />
    #enable_corovan - Включить корован<br />
    #disable_corovan - Выключить корован<br />
    #enable_order - Включить приказы<br />
    #disable_order - Выключить приказы<br />
    #enable_auto_def - Включить авто деф<br />
    #disable_auto_def - Выключить авто деф<br />
    #status - Получить статус<br />
    #hero - Получить информацию о герое<br />
    #push_order - Добавить приказ<br />
    #order - Дебаг, последняя команда защиты/атаки замка<br />
    #log - Дебаг, последние 30 сообщений из лога<br />
    #time - Дебаг, текущее время<br />
    #lt_arena - Дебаг, последняя битва на арене<br />
    #get_info_diff - Дебаг, последняя разница между запросами информации о герое<br />
    #ping - Дебаг, проверить жив ли бот<br />
 
Делайте с ботом что хотите, пишите в личку в телеграме @iriskin0, помогу с настройкой или допиливанием. Кидайте иссуи, может даже исправлю чего-нибудь %)
