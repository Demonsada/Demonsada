from .. import loader
from asyncio import sleep 

def register(cb):
	cb(LoveMod()) 
	
class LoveMod(loader.Module):
	"""love"""
	strings = {'name': 'love'}
        
	async def lovecmd(self, message):
		"""Используй .love"""
		await message.edit('Пожалуйста прочти до конца🥺')
		await sleep(0.90)
		await message.edit('Я хочу тебе сказать что ты самая🥰')
		await sleep(0.90)
		await message.edit('Красивая😍')
		await sleep(0.90)
		await message.edit('Милая☺️')
		await sleep(0.90)
		await message.edit('В этом мире 😊')
		await sleep(0.90)
		await message.edit('С любовью😘') 
		await sleep(0.90)
                essage.edit('Твой любимый человек ❤️') 
		
