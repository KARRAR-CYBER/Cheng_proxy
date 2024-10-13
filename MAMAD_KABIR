from colorama import Fore,init
init()
print(Fore.LIGHTGREEN_EX+"  ")
name='ali'
if name=='mostafa':
    print('salam mostafa!')
elif name=='zahra':
    print('salam zahra!')
elif name=='amir':
    print('salam amir')
else:
    print('')
    print('  𝗦𝗔𝗟𝗔𝗠 𝗕𝗔𝗥 𝗬𝗢𝗨 ❤️ : ')
    print('')
    from colorama import Fore,init
init()
print(Fore.BLUE+"")



print(Fore.RED+"""

'##::::'##:'########:::'######::'########:'########:'########::
 ###::'###: ##.... ##:'##... ##:... ##..:: ##.....:: ##.... ##:
 ####'####: ##:::: ##: ##:::..::::: ##:::: ##::::::: ##:::: ##:
 ## ### ##: ########::. ######::::: ##:::: ######::: ########::
 ##. #: ##: ##.. ##::::..... ##:::: ##:::: ##...:::: ##.. ##:::
 ##:.:: ##: ##::. ##::'##::: ##:::: ##:::: ##::::::: ##::. ##::
 ##:::: ##: ##:::. ##:. ######::::: ##:::: ########: ##:::. ##:
..:::::..::..:::::..:::......::::::..:::::........::..:::::..::
⠀⠀⠀⠀⠀⠀⠀

""")
from colorama import Fore,init
init()
print(Fore.GREEN+"  ")
import requests
import time

proxies = [
    'http://proxy1:port',
    'http://proxy2:port',
    'http://proxy3:port',
]

while True:
    for proxy in proxies:
        try:
            response = requests.get('http://httpbin.org/ip', proxies={'http': proxy, 'https': proxy})
            print(f"IP : {response.json()['origin']} : {proxy}")
        except Exception as e:
            print(f" {proxy}: {e}")
        
        time.sleep(3)
