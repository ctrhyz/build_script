# ROM Build Script With Telegram Notifier (Can Use in Crave)
## How to use
+ **Fork This Repo**
+ **Then, Setup Your Configuration [Here](https://github.com/ctrhyz/build_script#set-configuration)**
+ **After that, Run this command below inside your rom project folder**
```bash
# Change yourUsername with your github username
wget https://raw.githubusercontent.com/yourUsername/build_script/main/jembod.sh
bash jembod.sh | tee hiya.txt
```

## Set Configuration
Open `jembod.sh` with your preferred IDE or text editor and change according your preference.
>**_TZ_** \
>Is your **Timezone** \
>eg. **Asia/Jakarta**

>**_romcuy_** \
>Is **rom** name that you want to build. **Dont fill** with any **symbol**, **Only Alphabet & Number** \
>eg. **`Afterlife` `RisingOS` `LineageOS21`** or whatever

>**_id_ch_** \
>Is your **Telegram channel id**, Add **_`-100`_** before your id. \
>eg. your channel id is **`1234567890`**, then it will be **`-1001234567890`**

>**_id_owner_** \
>Is your **Telegram id** \
>eg. **`1234569890`**

>**_dcdnm_** \
>Is your **device codename** \
>eg. **`rosemary`** **`garnet`** **`X00TD`** or whatever

>**_botuname_** \
>Is your **bot username** without **`@`** \
>eg. **`zbuild_bot`**

>**_btoken_** \
>Is your **bot token** from **BotFather**

>**_lmfests_** \
>Is **Github link** to your **_local_manifests_** \
>eg. **`https://github.com/ctrhyz/local_manifests`**

>**_blmfests_** \
>Is **branch** of your **local_manifests** \
>eg. **`main`** **`testing`** **`master`** or whatever

>**_admfests_** \
>Is link to **android_manifest** of **rom source**, can get in docs of rom \
>eg. **`https://github.com/AfterlifeOS/android_manifest.git`** **`https://github.com/RisingTechOSS/android`**

>**_badmfests_** \
>Is **branch** of **android_manifest** from **rom source** \
>eg. **`14`** **`lineage-21`** **`fourteen`** **`udc`** or whatever

>**_jembod_** \
>Is **command** to **build** rom \
>eg. **`mka bacon`** **`rise b`** **`goafterlife <device-codename>`** or whatever