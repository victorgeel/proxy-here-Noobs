# proxy-scraper-checker

[![CI](https://github.com/monosans/proxy-scraper-checker/actions/workflows/ci.yml/badge.svg)](https://github.com/monosans/proxy-scraper-checker/actions/workflows/ci.yml)

![Screenshot](screenshot.png)

HTTP, SOCKS4, SOCKS5 proxies scraper and checker.


You can get proxies obtained using this script in [victorgeel/proxy-list](https://github.com/victorgeel/proxy-list-update).

## Termux တစ်မျိုးပဲသုံး

### Termux

To use `proxy-scraper-checker` in Termux, knowledge of the Unix command-line interface is required.

- Download Termux from [F-Droid](https://f-droid.org/en/packages/com.termux/). [Don't download it from Google Play](https://github.com/termux/termux-app#google-play-store-deprecated).
- Run the following command (it will automatically update Termux packages, install Python, and download and install `proxy-scraper-checker`):
  ```bash
  bash <(curl -fsSL 'https://raw.githubusercontent.com/victorgeel/proxy-here-Noobs/modified/install-termux.sh')
  cd ~/proxy-here-Noobs && sh start-termux.sh
  ```
- Edit `~/proxy-here-Noobs/config.ini` to your preference using a text editor (vim/nano).
- `proxy-here-Noobs`Runဖို့..............   `ပထမ cmd ` (အဆင်မပြေရင် ဒုတိယ cmd သုံး):
  ```bash
  cd ~/proxy-here-Noobs && sh start-termux.sh
  ```
- `ဒုတိယ cmd` သူက ပို အဆင်ပြေတယ်:
  ```bash
  cd /data/data/com.termux/files/home/proxy-here-Noobs && sh start-termux.sh
## 💚ရလာတဲ့ proxies ဖိုင်တွေကို ဖွင့်ဖတ်ရန်

- 💜 Socks5 proxy များ
- 🩵 proxies
   ```
   vim ~/proxy-here-Noobs/proxies/socks5.txt
- 🩵 proxies_geolocation
  ```
  vim ~/proxy-here-Noobs/proxies_geolocation/socks5.txt

- 💜 Http proxy များ
- 🩵 proxies
   ```

  vim ~/proxy-here-Noobs/proxies/http.txt

- 🩵 proxies_geolocation
   ```
  vim ~/proxy-here-Noobs/proxies_geolocation/http.txt

## အရှင်းဆုံး ရေးထားပါသည်
  
  
  
  

