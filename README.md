# TicTacToe_bot
## Це Телеграм Бот для гри хрестики-нулики.
##технології:
	Python;
	Aiogram;
	Asyncio;
	Async;
	json;
	Dictionary;
	HTML.
	
##Опис файлів:
	Через файл main.py запускається весь.
	Через файл callback_quary.py зроблено реакцію на натискання на кнопки InlineKeyboardMarkUp.
	Через файл clases.py було зроблено win_shema та у цьому файлі зроблено: self.chat_id = chat_id

self.message_id = message_id

self.shape = shape

self.username = username

Через файл	heandlers.py було зроблено реакцію на натискання кнопки Start, рейтинг.

Через файл creat_bot.py був розміщен token

Через файл keyboards.py було розміщено клавіатури.

Через файл save_data.py відбувається збереження данних.
У init.py:
	from bot_modules.heandlers import *
   from bot_modules.callback_query import *

##Структура збереження файлів у users.json:
	{
	chat.id
