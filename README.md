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

![image](https://user-images.githubusercontent.com/9271266/235225719-8ce14876-7980-4bf6-952e-6edbebd730db.png)

DONE!

to test it;

![image](https://user-images.githubusercontent.com/9271266/235225952-8faa8f3d-ce9e-4bcf-ae18-ea23e87ee772.png)

hit "Do it now!"

![image](https://user-images.githubusercontent.com/9271266/235226058-158f0235-92c4-44ed-a2a5-a916ab7e4586.png)
