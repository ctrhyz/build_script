# ROM Build Script With Telegram Notifier (Can Use in Crave)
## How to use
+ **Fork This Repo**
+ **Then, Setup Your Configuration [Here](https://github.com/ctrhyz/build_script#set-configuration)**
+ **After that, Run this command below inside your rom project folder**
```
wget https://raw.githubusercontent.com/yourUsername/build_script/main/jembod.sh
bash jembod.sh | tee hiya.txt
```

## Set Configuration
Open `jembod.sh` with your preferred IDE or text editor and change according your preference.
>**_TZ_** \
>Is your Timezone \
>eg. **Asia/Jakarta**

>**_romcuy_** \
>Type Your **Rom** that you want to build. **Dont fill** with any **symbol**, **Only Alphabet & Number** \
>eg. **Afterlife RisingOS LineageOS21**

>**_id_ch_** \
>Fill with your **Telegram channel id**, Add **_-100_** before your id. \
>eg. your channel id is **1234567890**, then it will be **-1001234567890**

>**_id_owner_** \
>Enter your **Telegram id** \
>eg. **1234569890**

>**_dcdnm_** \
>Fill with your **device codename** \
>eg. **rosemary** **garnet** **X00TD**

>**_botuname_** \
>Fill with your **bot username** without **`@`** \
>eg. **zbuild_bot**

>**_btoken_** \
>Fill with your **bot token** from **BotFather**

>**_lmfests_** \
>**GIthub link** to your **_local_manifests_** \
>eg. **`https://github.com/ctrhyz/local_manifests`**