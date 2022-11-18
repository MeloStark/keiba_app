# Withdrow data from netkeiba on RPi4
## setup
1. install chromium-chromedriver to raspberry pi 4
`pi@raspberrypi:~/workspace/keiba $ sudo apt-get install chromium-chromedriver`

要望=(U)不明/(I)インストール/(R)削除/(P)完全削除/(H)保持
| 状態=(N)無/(I)インストール済/(C)設定/(U)展開/(F)設定失敗/(H)半インストール/(W)トリガ待ち/(T)トリガ保留
|/ エラー?=(空欄)無/(R)要再インストール (状態,エラーの大文字=異常)
||/ 名前                         バージョン          アーキテクチ 説明
+++-============================-===================-============-===================================================
un  chromium                     <なし>              <なし>       (説明 (description) がありません)
ii  chromium-browser             104.0.5112.105-rpt2 arm64        Chromium web browser, open-source version of Chrome
un  chromium-browser-inspector   <なし>              <なし>       (説明 (description) がありません)
ii  chromium-browser-l10n        104.0.5112.105-rpt2 all          chromium-browser language packages
ii  chromium-chromedriver        104.0.5112.105-rpt2 arm64        WebDriver driver for the Chromium Browser
un  chromium-codecs-ffmpeg       <なし>              <なし>       (説明 (description) がありません)
ii  chromium-codecs-ffmpeg-extra 104.0.5112.105-rpt2 arm64        Extra ffmpeg codecs for the Chromium Browser
un  chromium-driver              <なし>              <なし>       (説明 (description) がありません)

2. install serenuum to raspberry pi 4
`pi@raspberrypi:~/workspace/keiba $ pip --version`
pip 20.3.4 from /usr/lib/python3/dist-packages/pip (python 3.9)

`pi@raspberrypi:~/workspace/keiba $ pip install selenium`

`pi@raspberrypi:~/workspace/keiba $ pip show selenium`
Name: selenium
Version: 4.6.0
Summary: None
Home-page: https://www.selenium.dev
Author: None
Author-email: None
License: Apache 2.0
Location: /home/pi/.local/lib/python3.9/site-packages
Requires: trio-websocket, certifi, urllib3, trio
Required-by:

