Set up screen and install both Python3 and pip. Afterwards, proceed to install the Flask module.

```
sudo apt install screen python3 python3-pip -y
pip install flask
```

Download `web_server.py`

```
https://raw.githubusercontent.com/thecoldblooded/UI-for-Submitting-PayForBlob-Transactions-Celestia-/main/blob.sh
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

DONE!
