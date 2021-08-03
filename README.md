「何某手寫體」是基於[おつとめフォント](http://rooms.webcrow.jp/)的開放原始碼中文字型。與原作者的主要差異是調整部件寫法、新增中文字、增加為5個字重、增加一些符號。可以免費商用，歡迎大家自由應用、自由優化、自由改作！

![何某手寫體](https://github.com/max32002/nanifont/raw/master/preview/welcome.png)

何某手寫體與原作者的差異：
* 從原作者的 2020-11-21 Ver3.10 (RC) 複製出來修改。
* Max修改前，符號＋文字數：8,784個。
* Max修改後，符號＋文字數：23,739個。
* Max中文補字：10,676個。完整的補字清單，請參考[更新記錄](https://github.com/max32002/nanifont/blob/master/change_log.md)。
* 與原作者重覆造字，考慮文字部件在地區用法不同，所以沒有使用原作者字有：凊婧楂癤祅祜祹稹腧薌迁迨迮逈逭靚饘鱁

## 字體特色

### 特色1：彌補繁體中文常用字缺字缺憾

解決常用的中文口語用詞缺字問題，Max目前補上了10,676個中文字，應該可以滿足大部份的需求，例如：喵嗝屌粿璀摳摀憨尪孬憋。

* 附註1：由於是「非原作者」的補字，新加入的字在風格上，雖然盡力求一致，難免會與原作者會有一些不同。
* 附註2：Max修改的版本，大約有 1/10 的補出來的字是長的很醜的，不過聊勝於無。

### 特色2：5種字重(Style)
![5種字重](https://github.com/max32002/nanifont/raw/master/preview/compare_styles.png)

* Light
* DemiLight
* Regular (原作者的字重)
* Medium
* SemiBold

原本的おつとめフォント放在Regular 字重裡，透過程式自動產生Light、DemiLight、Medium、SemiBold 新的字重。

在ExtraLight和Light字重是把原本的Otsutome Font微微調細一點點。在Light的字重裡，可能會因為筆劃太細造成某些筆畫消失。

在Medium和SemiBold的字重裡，可能會因為筆劃太粗造成某些筆畫重疊難以識別，有粗體字的需求，可以先挑戰使用SemiBold字重看看，如果發現效果不如預期，再改用Medium字重。

不能確定自動產生出來的字重裡每一個都是完整的字，畢盡程式會誤判是常有的事情，所以「不是在Regular字重」裡的筆劃可能會消失。

### 特色3：調整標點符號位置

おつとめフォント的全形標點符號針對日本做設計，調整為台灣常見的置中用法。

### 特色4：調整部件寫法

* 真、真、俞、尃，修改為台灣常見寫法。
* 食、辶、礻部，部份字修改為台灣常見寫法。
* 「豬」、「箸」日文漢字中的「者」有多一點，大多應該都被Max刪掉了。
* 「戶」部件，目前大多沿用日文寫法「戸」，沒有改成台灣用法「戶」。
* 「龍」部件，調整為三條橫線。
* 「囱」部件，調整為台標的「囪」。更新清單：窗聰總蔥傯璁。
* 「眾」部件調整清單：潀眾聚鄹驟。
* 修改原作者的錯字：嘲。


## 更新日誌
[點擊此處](https://github.com/max32002/nanifont/blob/master/change_log.md) 查看更新記錄。

## 下載字型

請點選GitHub此畫面右上綠色「Clone or download」按鈕，並選擇「Download ZIP」，或點進想下載的ttf字型檔案，再點「Download」的按鈕進行下載。

## 網頁字型(Web Font)服務

網頁字型用於網頁上的字型顯示，訪客不需預先安裝字型檔，一樣能夠看到特殊的字型效果。不只是電腦，在智慧型手機和平板裝置的瀏覽器上也可正常顯示。實現該功能的原理是在瀏覽時才下載字型檔。

WebFont可以服用下面的css:
```
@font-face {
  font-family: nanifont;
  src: url(https://cdn.jsdelivr.net/gh/max32002/nanifont@1.036/webfont/NaniFont-Regular.woff2) format("woff2")
  , url(https://cdn.jsdelivr.net/gh/max32002/nanifont@1.036/webfont/NaniFont-Regular.woff) format("woff");
}
```
附註：Regular換成其他的值，可以調整粗細。

## 附註

* 補的缺字，效果差強人意，聊勝於無。
* 原作者有回我信，而且他的中文好像滿好的。
![歡迎自由改作](https://github.com/max32002/nanifont/raw/master/preview/email_reply_sleepcows.png)

## 著作權與授權

* 本字型是基於 SIL Open Font License 1.1 改造何某亭所開發、發表的「[Otsutome Font (おつとめフォント)](http://rooms.webcrow.jp/)」字型。
* 本字型亦基於 SIL Open Font License 1.1 授權條款免費公開，關於授權合約的內容、免責事項等細節，請詳讀 License 文件。
    * 可自由商用 不需付費、知會或標明作者，即可自由使用此字型，亦可做商業應用。
    * 可自由傳布 可自由分享檔案、將檔案安裝於任何軟硬體中。
    * 可自由改作為其他字型 將字型檔案修改重製為其他字型檔案，改作後的字型檔案須同樣依 Open Font License 釋出。

字體授權小提示：本字型採用 SIL Open Font License 1.1 授權發表，可以免費商用。在 github 上有附上 SIL Open Font License 1.1 的授權文件，如甲方或公司需要出示授權文件，直接使用此文件即可。
    
## 相關網頁

花園家族：
* B2花園 B2 Hana
https://max-everyday.com/2020/08/b2-hana-font/
* 花園肉丸 Hana Meatball
https://max-everyday.com/2020/08/hana-meatball/

簡體/繁體轉換家族：
* 獅尾簡腿黑體 Swei Jay Leg
https://max-everyday.com/2020/11/swei-jay-leg/
* 獅尾簡中黑體 Swei Jay Sans
https://max-everyday.com/2020/11/swei-jay-sans/
* 獅尾簡中宋體 Swei Jay Serif
https://max-everyday.com/2020/11/swei-jay-serif/
* 獅尾繁腿黑體 Swei Fan Leg
https://max-everyday.com/2020/11/swei-fan-leg/
* 獅尾繁中黑體 Swei Fan Sans
https://max-everyday.com/2020/11/swei-fan-sans/
* 獅尾繁中宋體 Swei Fan Serif
https://max-everyday.com/2020/11/swei-fan-serif/

獅尾黑體家族：
* 獅尾右下腿黑體 Swei Right Bottom Leg
https://max-everyday.com/2021/08/swei-right-bottom-leg/
* 獅尾右下圓黑體 Swei Right Bottom Sans
https://max-everyday.com/2021/08/swei-right-bottom-sans/
* 獅尾飛腿黑體 Swei Dart Leg
https://max-everyday.com/2020/11/swei-dart-leg/
* 獅尾飛鏢黑體 Swei Dart Sans
https://max-everyday.com/2020/11/swei-dart-sans/
* 獅尾火腿黑體 Swei Match Leg
https://max-everyday.com/2020/11/swei-match-leg/
* 獅尾火柴黑體 Swei Match Sans
https://max-everyday.com/2020/11/swei-match-sans/
* 獅尾骨腿黑體 Swei Bone Leg
https://max-everyday.com/2020/11/swei-bone-leg/
* 獅尾骨頭黑體 Swei Bone Sans
https://max-everyday.com/2020/11/swei-bone-sans/
* 獅尾斧腿黑體 Swei Ax Leg
https://max-everyday.com/2020/11/swei-ax-leg/
* 獅尾斧頭黑體 Swei Ax Sans
https://max-everyday.com/2020/11/swei-ax-sans/
* 獅尾喇腿黑體 Swei Bell Leg
https://max-everyday.com/2020/11/swei-bell-leg/
* 獅尾喇叭黑體 Swei Bell Sans
https://max-everyday.com/2020/11/swei-bell-sans/
* 獅尾惡腿黑體 Swei Devil Leg
https://max-everyday.com/2020/11/swei-devil-leg/
* 獅尾惡魔黑體 Swei Devil Sans
https://max-everyday.com/2020/11/swei-devil-sans/
* 獅尾麥腿黑體 Swei Marker Leg
https://max-everyday.com/2020/10/swei-marker-leg/
* 獅尾麥克黑體 Swei Marker Sans
https://max-everyday.com/2020/10/swei-marker-sans/
* 獅尾詠腿黑體 Swei Fist Leg
https://max-everyday.com/2020/10/swei-fist-leg/
* 獅尾詠春黑體 Swei Fist Sans
https://max-everyday.com/2020/10/swei-fist-sans/
* 獅尾鋸腿黑體 Swei Alias Leg
https://max-everyday.com/2020/10/swei-alias-leg/
* 獅尾鋸齒黑體 Swei Alias Sans
https://max-everyday.com/2020/10/swei-alias-sans/
* 獅尾尖腿黑體 Swei Spike Leg
https://max-everyday.com/2020/10/swei-spike-leg/
* 獅尾尖刺黑體 Swei Spike Sans
https://max-everyday.com/2020/10/swei-spike-sans/
* 獅尾快腿黑體 Swei Shear Leg
https://max-everyday.com/2020/09/swei-shear-leg/
* 獅尾快剪黑體 Swei Shear Sans
https://max-everyday.com/2020/09/swei-shear-sans/
* 獅尾福腿黑體 Swei Gospel Leg
https://max-everyday.com/2020/09/swei-gospel-leg/
* 獅尾福音黑體 Swei Gospel Sans
https://max-everyday.com/2020/09/swei-gospel-sans/
* 獅尾D滷腿黑體 Swei Del Luna Leg
https://max-everyday.com/2020/09/swei-del-luna-leg/
* 獅尾德魯納黑體 Swei Del Luna Sans
https://max-everyday.com/2020/09/swei-del-luna-sans/
* 獅尾彎腿黑體 Swei Curve Leg
https://max-everyday.com/2020/09/swei-curve-leg/
* 獅尾彎黑體 Swei Curve Sans
https://max-everyday.com/2020/09/swei-curve-sans/
* 獅尾霓腿黑體 Swei Bow Leg
https://max-everyday.com/2020/09/swei-bow-leg/
* 獅尾霓黑體 Swei Bow Sans
https://max-everyday.com/2020/09/swei-bow-sans/
* 獅尾蝙蝠圓體 Swei Bat Sans
https://max-everyday.com/2020/09/swei-bat-sans/
* 獅尾牙膏圓體 Swei Toothpaste
https://max-everyday.com/2020/09/swei-toothpaste/
* 獅尾三腿黑體 Swei 3T Leg
https://max-everyday.com/2020/09/swei-3t-leg/
* 獅尾三角黑體 Swei 3T Sans
https://max-everyday.com/2020/08/swei-3t-sans/
* 獅尾螺帽腿黑體 Swei Nut Leg
https://max-everyday.com/2020/08/swei-nut-leg/
* 獅尾螺帽黑體 Swei Nut Sans
https://max-everyday.com/2020/08/swei-nut-sans/
* 獅尾B2腿黑體 Swei B2 Leg
https://max-everyday.com/2020/07/swei-b2-leg/
* 獅尾B2黑體 Swei B2 Sans
https://max-everyday.com/2020/07/swei-b2-sans/
* 獅尾腿圓 Swei Gothic Leg
https://max-everyday.com/2020/08/swei-gothic-leg/
* 獅尾彩虹腿 Swei Rainbow Leg
https://max-everyday.com/2020/08/swei-rainbow-leg/
* 獅尾XD珍珠 Swei XD Pearl
https://max-everyday.com/2020/07/swei-xd-pearl/
* 獅尾D露西 Swei D Lucy
https://max-everyday.com/2020/07/swei-d-lucy/
* 獅尾半月字體 Swei Gothic
https://max-everyday.com/2020/04/swei-half-moon/
* 台灣圓體 TaiwanPearl
https://max-everyday.com/2020/06/taiwanpearl/
* 獅尾圓體 Swei Gothic
https://max-everyday.com/2020/04/swei-gothic/
* 獅尾黑體 Swei Sans
https://max-everyday.com/2020/03/swei-sans/

獅尾宋體家族：
* 獅尾B2加糖宋體 Swei B2 Sugar
https://max-everyday.com/2020/11/swei-b2-sugar/
* 獅尾加糖宋體 Swei Sugar
https://max-everyday.com/2020/11/swei-sugar/
* 獅尾B2宋朝 Swei B2 Serif
https://max-everyday.com/2020/07/swei-b2-serif/
* 獅尾肉丸 Swei Meatball
https://max-everyday.com/2020/06/swei-meatball/
* 獅尾四季春字體 Swei Spring
https://max-everyday.com/2020/04/swei-spring/

其他字體：
* 馬路口圓體 Maruko Gothic
https://max-everyday.com/2021/07/maruko-gothic/
* 苦累蛙圓體 Kurewa Gothic
https://max-everyday.com/2021/06/kurewa-gothic/
* 何某手寫體 Nani Font
https://max-everyday.com/2020/09/nanifont/
* 內海字體  Naikai Font
https://max-everyday.com/2020/03/naikaifont/
* 莫大毛筆字體 Bakudai Font
https://max-everyday.com/2020/03/bakudaifont/
* 正風毛筆字體 Masa Font
https://max-everyday.com/2020/05/masafont/
* 假粉圓體 Fake Pearl 
https://max-everyday.com/2020/03/open-huninn-font/
* 俊羽圓體 Yu Pearl 
https://max-everyday.com/2020/03/yupearl/

其他網站：
* 清松手寫體 JasonHandWriting
https://jasonfonts.max-everyday.com/
* Max學習字體相關的筆記
https://codereview.max-everyday.com/font-readme/

## 贊助Max

很高興可以替中華民國美學盡一分心力、讓台灣擁有更好的文字風景，希望能提供另一種美學讓大家選擇。

如果你想支持或打賞Max，贊助方式如下：
https://max-everyday.com/about/#donate
