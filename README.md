# instagram-unfollowers-tracker
Telegram bot written in node typescript for GFPGAN Real-world Face Restoration tool

## Install GFPGAN

### Clone repo
```
git clone https://github.com/TencentARC/GFPGAN.git
cd GFPGAN
```
### Install dependent packages
```
# Install basicsr - https://github.com/xinntao/BasicSR
# We use BasicSR for both training and inference
pip install basicsr

# Install facexlib - https://github.com/xinntao/facexlib
# We use face detection and face restoration helper in the facexlib package
pip install facexlib

pip install -r requirements.txt
python setup.py develop

# If you want to enhance the background (non-face) regions with Real-ESRGAN,
# you also need to install the realesrgan package
pip install realesrgan
```

## Install our bot
```
# clone this repo
```

## install dependencies
```
nvm use
npm i
```

## .env
```
touch .env
```

### in .env:

```
TELEGRAM_BOT_TOKEN="your_telegram_bot_token"
GFPGAN_PROJECT_PATH="/path/to/GFPGAN"
DATA_PATH="/path/to/data"
```

## Usage
```
$ npm i
$ npm run start:dev
```