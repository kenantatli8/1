import time
from requests import get

ipeski="0"
while True:
    disip = get('https://api.ipify.org').text

    if ipeski == disip:
        print("ip ayni")
    else:
        print("yeni ip var")
    ipeski=disip
    print("ipyeni:",disip)
    print("ipeski:",ipeski)
    time.sleep(3600)
