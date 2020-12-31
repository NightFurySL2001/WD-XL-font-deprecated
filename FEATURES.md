**WD-XL 滑油字 | WD-XL Lubrifont**

# OpenType 功能 features

WD-XL 滑油字已经设置部分 OpenType 功能：  
WD-XL Lubrifont has set up multiple OpenType features as follow:  
WD-XL 滑油字已經設置部分 OpenType 功能：

## `vert` / `vrt2` — Vertical Alternates

本字体为直式排版设计和设置了标点转换功能，其中包括：  
This font has designed and set up vertical typesetting punctuations including:  
本字型爲直式排版設計和設置了標點轉換功能，其中包括：

SC/TC 共享：`–—―‥…〈〉《》「」『』【】〓〔〕〖〗（）－＝［］｛｝～`  
仅 SC 版：`、。‘’“”！，：；？ㄧ`

## `ccmp` — Glyph Composition/Decomposition

本字体为 [汉语拼音](https://zh.wikipedia.org/zh-cn/%E6%B1%89%E8%AF%AD%E6%8B%BC%E9%9F%B3)、[台罗拼音](https://zh.wikipedia.org/zh-cn/%E8%87%BA%E7%81%A3%E9%96%A9%E5%8D%97%E8%AA%9E%E7%BE%85%E9%A6%AC%E5%AD%97%E6%8B%BC%E9%9F%B3%E6%96%B9%E6%A1%88) 及 [白话字](https://zh.wikipedia.org/zh-cn/%E7%99%BD%E8%A9%B1%E5%AD%97) 设计了对应的拼音符号，其中台罗拼音及白话字因为部分字符并未收录于 Unicode，因此需要 `ccmp` 组字功能为对应的符号进行设置。部分汉语拼音与台罗拼音及白话字共享码位，因此 `ccmp` 功能也涵盖了汉语拼音的组字功能（例如 Ề，Ǚ 和 Ẑ）。  
This font has designed characters needed for [Hanyu Pinyin](https://en.wikipedia.org/wiki/Pinyin), [Taiwan Minnanyu Luomazi Pinyin Fang'an (or Tâi-lô)](https://en.wikipedia.org/wiki/T%C3%A2i-u%C3%A2n_L%C3%B4-m%C3%A1-j%C4%AB_Phing-im_Hong-%C3%A0n) and [Pe̍h-ōe-jī](https://en.wikipedia.org/wiki/Pe%CC%8Dh-%C5%8De-j%C4%AB). As Tâi-lô and Pe̍h-ōe-jī uses some characters that are not included in Unicode, glyph composition/decomposition `ccmp` is used to composite the characters. Hanyu Pinyin has some overlapping characters with Tâi-lô and Pe̍h-ōe-jī, thus `ccmp` feature will also cover Hanyu Pinyin characters (e.g. Ề, Ǚ, Ẑ).  
本字型为 [臺羅拼音](https://zh.wikipedia.org/zh-tw/%E8%87%BA%E7%81%A3%E9%96%A9%E5%8D%97%E8%AA%9E%E7%BE%85%E9%A6%AC%E5%AD%97%E6%8B%BC%E9%9F%B3%E6%96%B9%E6%A1%88)、[白話字](https://zh.wikipedia.org/zh-tw/%E7%99%BD%E8%A9%B1%E5%AD%97) 及 [漢語拼音](https://zh.wikipedia.org/zh-tw/%E6%B1%89%E8%AF%AD%E6%8B%BC%E9%9F%B3) 設計了對應的拼音符號，其中臺羅拼音及白話字因爲部分字符並未收錄於 Unicode，因此需要 `ccmp` 組字功能爲對應的符號進行設置。部分漢語拼音與臺羅拼音及白話字共享碼位，因此 `ccmp` 功能也涵蓋了漢語拼音的組字功能（例如 Ề，Ǚ 和 Ẑ）。

本功能将会自动开启，用户无需进行设置。  
This feature is turned on automatically, users do not need to set up the setting.  
本功能將會自動開啓，用戶無需進行設置。

## `ss01` — Stylistic Set 01 (Alternate X)

为了匹配其他字符的设计，因此本龙为该字体设计了另外一款 `X` 的字形 (glyph)。  
To match with the design of other characters, another glyph is designed for `X`.  
爲了匹配其他字符的設計，因此本龍爲該字型設計了另外一款 `X` 的字形 (glyph)。

![Sample of ss01](ss01.png)

请用户在软件内查找 `样式集` (Stylistic set) 并选择 `ss01`。  
Users are required to find “Stylistic set” and turn on `ss01`.  
請用戶在軟體內查找 `文體集` (Stylistic set) 並選擇 `ss01`。

## `ss18` — Stylistic Set 18 (Western Punctuations)

为了适配西文排版，本字体预留了 `ss18` 以储存西文式标点符号。目前此功能内置放西文省略号（靠下）及间隔号 `U+002D MIDDLE DOT`（比例宽度）。
The font has reserved `ss18` for Western punctutions. Currently, the Western ellipsis and interpunct (middle dot) is placed in `ss18`.
爲了適配西文排版，本字型預留了 `ss18` 以存儲西文式標點符號。目前此功能內置放西文省略號（靠下）及間隔號 `U+002D MIDDLE DOT`（比例寬度）。

## `ss19` — Stylistic Set 19 (Cornered/SC Punctuation)
## `ss20` — Stylistic Set 20 (Centered/TC Punctuation)

待更新 To be updated.

## `liga` — Ligatures

本字体已经设置 ⸺ `U+2E3A TWO-EM DASH` 及 ⸻ `U+2E3B THREE-EM DASH`，但是碍于一般输入法无法输入该二字符，因此在 `liga` 连字功能里面设置以下功能：  
This font has set up both  ⸺ `U+2E3A TWO-EM DASH` and ⸻ `U+2E3B THREE-EM DASH`, but due to normal imput methods could not imput both characters, thus the following features are set up in ligatures `liga`:  
本字型已經設置 ⸺ `U+2E3A TWO-EM DASH` 及 ⸻ `U+2E3B THREE-EM DASH`，但是礙於一般輸入法無法輸入該二字符，因此在 `liga` 連字功能裏面設置以下功能：

| 字符 Character | 组合 Combination 組合 |
| --- | :-- |
| ⸺ `U+2E3A TWO-EM DASH` | U+2014 U+2014 <br> U+2015 U+2015 |
| ⸻ `U+2E3B THREE-EM DASH` | U+2014 U+2014 U+2014 <br> U+2015 U+2015 U+2015 |
| 彩蛋 Special feature | WD-XLlogo; |

请用户在软件内查找并启动 `标准连字` (Standard ligatures) 功能。  
Users are required to find turn on “Standard ligatures”.  
請用戶在軟體內查找並啓動 `標準連字` (Standard ligatures) 功能。

## `dlig` — Discretionary Ligatures

本字体也准备了汉语拼音内的多项缩写，如 `ng` - ŋ `U+014B LATIN SMALL LETTER ENG`，`zh` - ẑ `U+1E91 LATIN SMALL LETTER Z WITH CIRCUMFLEX` 等，但因为避免与其他语言相撞，因此将其设置于 `dlig` 内：  
This font also prepared the short hand form of `ng`, Ŋ `U+014A LATIN CAPITAL LETTER ENG` ang ŋ `U+014B LATIN SMALL LETTER ENG`, but to avoid collision with other languages, the features are set up in discretionary ligatures:  
本字型也準備了漢語拼音內的多項縮寫，如 `ng` - ŋ `U+014B LATIN SMALL LETTER ENG`，`zh` - ẑ `U+1E91 LATIN SMALL LETTER Z WITH CIRCUMFLEX` 等，但因爲避免與其他語言相撞，因此將其設置於 `dlig` 內：

| 字符 Character | 组合 Combination 組合 |
| --- | :-- |
| Ŋ `U+014A LATIN CAPITAL LETTER ENG` | NG |
| ŋ `U+014B LATIN SMALL LETTER ENG` | ng |
| Ẑ `U+1E90 LATIN CAPITAL LETTER Z WITH CIRCUMFLEX` | ZH/Zh |
| ẑ `U+1E91 LATIN SMALL LETTER Z WITH CIRCUMFLEX` | zh |
| Ĉ `U+0108 LATIN CAPITAL LETTER C WITH CIRCUMFLEX` | CH/Ch |
| ĉ `U+0109 LATIN SMALL LETTER C WITH CIRCUMFLEX` | ch |
| Ŝ `U+015C LATIN CAPITAL LETTER S WITH CIRCUMFLEX` | SH/Sh |
| ŝ `U+015D LATIN SMALL LETTER S WITH CIRCUMFLEX` | sh |

请用户在软件内查找并启动 `历史和任意连字` (Historical and discretionary ligatures) 功能。  
Users are required to find turn on “Historical and discretionary ligatures”.  
請用戶在軟體內查找並啓動 `歷史及選擇性連字` (Historical and discretionary ligatures) 功能。

## `smpl` / `trad` — Simplified/Traditional forms

本字体进行了几项技术测试，其中包括简繁字形替换。该功能将会提供用户选择把繁体字转为简体字（`smpl`）或者把简体字转为繁体字（`trad`）。一对多的字符将不会自动替换，用户需要手动选择替换该类字符。 **注意：该功能将会替换文档内的资讯，请妥善保存原文件后才进行测试。** [（参考来源）](https://docs.microsoft.com/en-us/typography/opentype/spec/features_pt)  
This font has included a few technical tests including Simplified/Traditional form exchanging. This feature can provide user options to convert Simplified characters to Traditional characters (`trad`) or Traditional characters to Simplified characters (`simp`). One-to-many characters will not be automatically swapped, instead users are required to manually change the characters. **Warning: the feature will modify information stored in documents, please save the original file in a safe location before testing**. [(Source)](https://docs.microsoft.com/en-us/typography/opentype/spec/features_pt)  
本字型進行了幾項技術測試，其中包括繁簡字形替換。該功能將會提供用戶選擇把簡體字轉爲繁體字 (`trad`) 或者把繁體字轉爲簡體字 (`simp`)。一對多的字符將不會自動替換，用戶需要手動選擇替換該類字符。 **注意：該功能將會替換文檔内的資訊，請妥善保存原文件后才進行測試。** [（參考來源）](https://docs.microsoft.com/en-us/typography/opentype/spec/features_pt)

目前多数软件不支援该功能，仅浏览器可以通过 CSS 设置该功能。  
Most software do not support this function, only browsers are able to set this feature through CSS.  
目前多數軟體不支援該功能，僅瀏覽器可以通過 CSS 設置該功能。

## `aalt` — Access All Alternates

以上所有功能（除了 `liga` 和 `dlig`）皆可通过 `aalt` 功能使用，因此 `smpl`/`trad` 的字符替换选择也可以在 Adobe 系列软件内测试使用。  
All the features above (except `liga`) can be access through `aalt`, thus the character choice from `smpl`/`trad` can still be accessed in Adobe suite through this function.  
以上所有功能（除了 `liga` 和 `dlig`）皆可通過 `aalt` 功能使用，因此 `smpl`/`trad` 的字符替换選擇也可以在 Adobe 系列軟體內測試使用。