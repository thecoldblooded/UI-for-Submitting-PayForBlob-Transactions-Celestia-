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
cd ..
screen -S web_server
python3 web_server.py
```

![image](https://user-images.githubusercontent.com/9271266/235225719-8ce14876-7980-4bf6-952e-6edbebd730db.png)

DONE!
