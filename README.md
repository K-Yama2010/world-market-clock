# world-market-clock　

輸出入企業の社員または経営者、そして貿易事務系の仕事をされてる方向けの24時間世界時計です。

 アナログ時計はグリニッジの標準時、デジタル時計は世界の主要な3市場、NY、London、東京を示します。
 時計盤（背景）には各国市場の取引時間帯と北極点を中心とした地図を表示しています。
 （時間針（短針）は太陽の位置を示すことになります）
 これら４つの要素を統合して表示する世界時計は少なくとも世の中にはまだないようですが、
 複雑さは一切なくむしろ直感的な見易さと理解しやすさがあり、あなたが世界各国各市場の現地時間と取引状況をイメージすることを大きく手助けします。<br>
<br>
 <br>
  It is a 24-hour world clock for employees or managers of import/export companies, 
 and those who work in trade clerical work.

  The analog clock shows Greenwich Mean Time and the digital clock shows the three major markets of the world: New York, London and Tokyo.
  The clock face (background) displays the trading hours of each country's market and a map centered on the North Pole.
  (The hour hand (short hand) indicates the position of the sun.)

  It seems that there is still no world clock that integrates these four elements and displays them.
  There is no complexity at all, rather it is intuitive to see and understand, 
 and it greatly helps you to imagine the local time and trading situation of each market around the world.<br>
<br>
<br>
<br>
<br>
 時計盤の上部にローカル時間、右側に主要4通貨（３通貨ペア）のレートをリアルタイムで表示します。

 側面のLEDは相場の変動に応じて色が変わります（緑→オレンジ→赤）。常時レートの数字を注視していなくても凡その相場のムードを把握することが可能です。


 また、世界時計では標準時とサマーターム、各国市場の取引時間表示切替はすべて自動で行われ、以下の条件によって行われます。


    3 月の第 2 日曜日: ニューヨーク、トロント、シカゴ、　夏時間への移行。
    3 月最後の日曜日: ロンドン、チューリッヒ、フランクフルト、　夏時間への移行。
    4 月の第 1 日曜日: シドニー、ウェリントン、　標準時間に移行します。
    9月最後の日曜日：ウェリントン、　夏時間への移行。
    10月の第一日曜日：シドニー、　夏時間への移行。
    10月最後の日曜日：ロンドン、チューリッヒ、フランクフルト、　標準時間に移行します。
    11 月の第 1 日曜日: ニューヨーク、トロント、シカゴ、　標準時間に移行します。



 通貨レートを表示させない通常の世界時計モード、ローカル時間表示モードもあります（ローカル時間設定時に使用）。<br>
<br>
<br>
<br>
Local time is displayed at the right of the clock face, and rates of 4 major currencies (3 currency pairs) are displayed in real time.

 The LED on the side changes color according to market fluctuations (green → orange → red). Even if you don't pay attention to the rate numbers all the time, it is possible to grasp the mood of the market.

  In addition, the world clock automatically switches between standard time, daylight saving time, 
 and trading time display for each country's market under the following conditions.



    Second Sunday in March: New York, Toronto, Chicago. Transition to daylight saving time.
    Last Sunday in March: London, Zurich, Frankfurt. Transition to daylight saving time.
    First Sunday in April: Wellington, Sydney. Transition to standard time.
    Last Sunday in September: Wellington. Transition to daylight saving time.
    First Sunday in October: Sydney. Transition to daylight saving time.
    Last Sunday in October: London, Zurich, Frankfurt. Transition to standard time.
    First Sunday in November: New York, Toronto, Chicago. Transition to standard time.
<br>
  There is also a normal world clock mode that does not display currency rates, and a local time display mode (used when setting local time).
<br>
<br>

![時計盤２](https://github.com/K-Yama2010/world-market-clock/assets/141997302/0057fc19-78ef-45b9-83e5-fb532547150c)
<br>
<br>

![WMK１０](https://github.com/K-Yama2010/world-market-clock/assets/141997302/e50f1cef-c35a-4891-97e2-8a16f973088b)

<br>
   開発経緯<br>
  development process<br>

![世界時計説明１１](https://github.com/K-Yama2010/world-market-clock/assets/141997302/d3cca64b-a4a7-4d6e-9008-2d47101c1758)
<br>
<br>
その世界時計の弱点を上記でデザインした24時間アナログ時計に地域と時間を書き込むことによって解決。どの地域が日の出、日没、日中、深夜が即座に分かります。同時に経済活動が活発な時間帯の地域も分かることを意味します。<br>
We solved the weakness of the world clock by writing the region and time to the 24-hour analog clock designed above. So you can instantly see which area is sunrise, sunset, day, or midnight. At the same time, it means that you can also see the areas where economic activity is active.


<br>
<br>
<br>
　　 設定方法 <br>
 <br>
　プログラム本体はM5Burnerでダウンロードし、
    SDカードに以下のファイルとフォルダを作成してください。<br>
<br>
    1. wifi.txtファイル：<br>
    ファイル名は"wifi.txt"で、中身は次の通りで１行目にID,２行目にパスワードを記入してください。<br>
    <br>
    YOUR_WIFI_SSID<br>
    YOUR_WIFI_PASS<br>
 <br>
    2.時計盤の画像フォルダ：<br>
    フォルダ名は"world clock"で、Code→DownloadZIPよりダウンロードし、SDカードにフォルダごと保存してください。<br>
<br>
<br>
<br>
How to set <br>
 <br>
　Please download the main program with M5Burner.<br>
    Create the following files and folders on your SD card.<br>
<br>
    1.wifi.txt file: <br>
    The file name is "wifi.txt", and the content is as follows. Enter your ID on the first line and the password on the second line. <br>
    YOUR_WIFI_SSID<br>
    YOUR_WIFI_PASS<br>
 <br>
    2. Clock face image folder: The folder name is "world clock", download it from Code→DownloadZIP, and save it in the folder on the SD card.<br>
<br>
<br>
<br>
　　 使い方 <br>
 <br>
A&Cボタン：ローカル時間の設定（リセット後もローカル時間の設定は記憶されます。）<br>
Bボタン：　為替レートの表示　ON/OFF　（レートは約１０秒間隔で更新されます。またレート表示中は秒針は表示されません）<br>
<br>
<br>
　　Usage <br>
 <br>
A&C button: Local time setting (Local time setting is memorized even after reset.)<br>
B button: Exchange rate display ON/OFF　(The rate is updated at intervals of about 10 seconds.The second hand is not displayed while the rate is being displayed)<br>
<br>

    
