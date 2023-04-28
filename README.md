Set up screen and install both Python3 and pip. Afterwards, proceed to install the Flask module.

```
sudo apt install screen python3 python3-pip -y
pip install flask
```

Download `web_server.py`

```
wget https://raw.githubusercontent.com/thecoldblooded/UI-for-Submitting-PayForBlob-Transactions-Celestia-/main/web_server.py
```

Make a directory called `dashboard` and retrieve the file `index.html`.

```
mkdir dashboard
cd dashboard
wget https://raw.githubusercontent.com/thecoldblooded/UI-for-Submitting-PayForBlob-Transactions-Celestia-/main/index.html
wget https://raw.githubusercontent.com/thecoldblooded/UI-for-Submitting-PayForBlob-Transactions-Celestia-/main/blob.sh
cd ..
screen -S web_server
python3 web_server.py
```

![image](https://user-images.githubusercontent.com/9271266/235247222-2eae319a-35b7-44ae-8b39-721f92cc4929.png)

DONE!

to test it;

![image](https://user-images.githubusercontent.com/9271266/235247026-33bc879f-1711-4637-aa97-e3e45ea426b6.png)

hit "Do it now!"

![image](https://user-images.githubusercontent.com/9271266/235246801-b01d3882-177d-4d7c-a0e5-25290d442fbc.png)

RESULT;

![image](https://user-images.githubusercontent.com/9271266/235248131-d4ec5e1c-fbc1-4b02-ac9d-d5409d20995d.png)
![image](https://user-images.githubusercontent.com/9271266/235248274-06570ca0-918f-45f6-8d44-46072d1fb23d.png)

check -> https://testnet.mintscan.io/celestia-incentivized-testnet/txs/92CCD151463D2E751E1FA5F6092B50ACD60931C8A69DC5D0BDA2A3E4AC446130

![image](https://user-images.githubusercontent.com/9271266/235249185-f63ebf54-36fb-430d-932d-aa047b4c76f6.png)
