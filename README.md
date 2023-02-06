# Sockets with Python

This repository contains example code for exchanging data between a client and server over Python sockets:
- `client.py`
- `server.py`

Code examples are also given for exchanging data between two Python clients directly using PubNub:
- `pn_client_1.py`
- `pn_client_2.py`

## Running the Code (Python sockets)
- [Install Python](https://www.python.org/downloads/)
- Clone this repo to your machine
- `python3 server.py`
- `python3 client.py` (in a separate terminal)

![Screenshot](https://raw.githubusercontent.com/PubNubDevelopers/python-socket-demo/master/media/python_sockets.png)

## Running the Code (PubNub)
- Install the PubNub package with pip (lastest as of Feb 2023): `pip3 install 'pubnub>=7.1.0'`
- `python3 pn_client_1.py`
- `python3 pn_client_2.py` (in a separate terminal)

![Screenshot](https://raw.githubusercontent.com/PubNubDevelopers/python-socket-demo/master/media/pubnub.png)

To run this project yourself you can also use your own PubNub keys 

### Get Your PubNub Keys

<a href="https://dashboard.pubnub.com/signup">
	<img alt="PubNub Signup" src="https://i.imgur.com/og5DDjf.png" width=260 height=97/>
</a>


1. You’ll first need to sign up for a [PubNub account](https://dashboard.pubnub.com/signup/). Once you sign up, you can get your unique PubNub keys from the [PubNub Developer Portal](https://admin.pubnub.com/).

1. Sign in to your [PubNub Dashboard](https://admin.pubnub.com/).

1. Click Apps, then **Create New App**.

1. Give your app a name, and click **Create**.

1. Click your new app to open its settings, then click its keyset.


