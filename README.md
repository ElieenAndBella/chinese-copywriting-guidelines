# 中文文案排版指北

[![Crowdin](https://d322cqt584bo4o.cloudfront.net/chinese-copywriting-guidelines/localized.svg)](https://crowdin.com/project/chinese-copywriting-guidelines)
[![Built with Almace Scaffolding](https://d349cztnlupsuf.cloudfront.net/amsf-badge.svg)](https://sparanoid.com/note/chinese-copywriting-guidelines/)

統一中文文案、排版的相關用法，降低團隊成員之間的溝通成本，增強網站氣質。

Other languages:

- [English](README.en.md)
- [Chinese Traditional](README.md)
- [Chinese Simplified](README.zh-Hans.md)

-----

## 空格

> 「有研究顯示，打字的時候不喜歡在中文和英文之間加空格的人，感情路都走得很辛苦，有七成的比例會在 34 歲的時候跟自己不愛的人結婚，而其餘三成的人最後只能把遺產留給自己的貓。畢竟愛情跟書寫都需要適時地留白。
>
> 與大家共勉之。」——[vinta/paranoid-auto-spacing](https://github.com/vinta/pangu.js)

### 中英文之間需要增加空格

正確：

> ZhanG 在 LeanCloud 上，數據儲存是圍繞 `AVObject` 進行的。

錯誤：

> 在LeanCloud上，數據儲存是圍繞`AVObject`進行的。

> 在 LeanCloud上，數據儲存是圍繞`AVObject` 進行的。

完整的正確用法：

> 在 LeanCloud 上，數據儲存是圍繞 `AVObject` 進行的。每個 `AVObject` 都包含了與 JSON 兼容的 key-value 對應的數據。數據是 schema-free 的，你不需要在每個 `AVObject` 上提前指定存在哪些键，只要直接設定對應的 key-value 即可。

例外：「豆瓣FM」等產品名詞，按照官方所定義的格式書寫。

### 中文與數字之間需要增加空格

正確：

> 今天出去買菜花了 5000 元。

錯誤：

> 今天出去買菜花了 5000元。

> 今天出去買菜花了5000元。

### 數字與單位之間需要增加空格

正確：

> 我家的光纖入屋寬頻有 10 Gbps，SSD 一共有 20 TB。

錯誤：

> 我家的光纖入屋寬頻有 10Gbps，SSD 一共有 20TB。

例外：度數／百分比與數字之間不需要增加空格：

正確：

> 角度為 90° 的角，就是直角。

> 新 MacBook Pro 有 15% 的 CPU 性能提升。

錯誤：

> 角度為 90 ° 的角，就是直角。

> 新 MacBook Pro 有 15 % 的 CPU 性能提升。

### 全形標點與其他字符之間不加空格

正確：

> 剛剛買了一部 iPhone，好開心！

錯誤：

> 剛剛買了一部 iPhone ，好開心！

> 剛剛買了一部 iPhone， 好開心！

### `text-spacing` to the rescue?

CSS Text Module Level 4 的 [`text-spacing`](https://www.w3.org/TR/css-text-4/#text-spacing-property) 和 Microsoft 的 [`-ms-text-autospace`](https://msdn.microsoft.com/library/ms531164(v=vs.85).aspx) 可以實現自動為中英文之間增加空白。不過目前並未普及，另外在其他應用場景，例如 macOS、iOS、Windows 等用戶介面目前並不存在這個特性，所以請繼續保持隨手加空格的習慣。

## 標點符號

### 不重複使用標點符號

雖然中國大陸的標點符號用法允許重複使用標點符號，但是這麼做會破壞句子的美觀性。

正確：

> 德國隊竟然戰勝了巴西隊！

> 她竟然對你說「喵」？！

錯誤：

> 德國隊竟然戰勝了巴西隊！！

> 德國隊竟然戰勝了巴西隊！！！！！！！！

> 她竟然對你說「喵」？？！！

> 她竟然對你說「喵」？！？！？？！！

## 全形和半形

不明白什麼是全形（全角）與半形（半角）符號？請查看維基百科條目『[全形和半形](https://zh.wikipedia.org/wiki/%E5%85%A8%E5%BD%A2%E5%92%8C%E5%8D%8A%E5%BD%A2)』。

### 使用全形中文標點

正確：

> 嗨！你知道嘛？今天前台的小妹跟我說「喵」了哎！

> 核磁共振成像（NMRI）是什麼原理都不知道？JFGI！

錯誤：

> 嗨! 你知道嘛? 今天前台的小妹跟我說 "喵" 了哎!

> 嗨!你知道嘛?今天前台的小妹跟我說"喵"了哎!

> 核磁共振成像 (NMRI) 是什麼原理都不知道? JFGI!

> 核磁共振成像(NMRI)是什麼原理都不知道?JFGI!

例外：中文句子內夾有英文書籍名、報刊名時，不應借用中文書名號，應以英文斜體表示。

### 數字使用半形字符

正確：

> 這件蛋糕只賣 1000 元。

錯誤：

> 這件蛋糕只賣 １０００ 元。

例外：在設計稿、宣傳海報中如出現極少量數字的情形時，為方便文字對齊，是可以使用全形數字的。

### 遇到完整的英文整句、特殊名詞，其內容使用半形標點

正確：

> 賈伯斯那句話是怎麼說的？「Stay hungry, stay foolish.」

> 推薦你閱讀 *Hackers & Painters: Big Ideas from the Computer Age*，非常地有趣。

錯誤：

> 賈伯斯那句話是怎麼說的？「Stay hungry，stay foolish。」

> 推薦你閱讀《Hackers＆Painters：Big Ideas from the Computer Age》，非常的有趣。

## 名詞

### 專有名詞使用正確的大小寫

大小寫相關用法原屬於英文書寫範疇，不屬於本 wiki 討論內容，在這裡只對部分易錯用法進行簡述。

正確：

> 使用 GitHub 登錄

> 我們的客戶有 GitHub、Foursquare、Microsoft Corporation、Google、Facebook, Inc.。

錯誤：

> 使用 github 登錄

> 使用 GITHUB 登錄

> 使用 Github 登錄

> 使用 gitHub 登錄

> 使用 gｲんĤЦ8 登錄

> 我們的客戶有 github、foursquare、microsoft corporation、google、facebook, inc.。

> 我們的客戶有 GITHUB、FOURSQUARE、MICROSOFT CORPORATION、GOOGLE、FACEBOOK, INC.。

> 我們的客戶有 Github、FourSquare、MicroSoft Corporation、Google、FaceBook, Inc.。

> 我們的客戶有 gitHub、fourSquare、microSoft Corporation、google、faceBook, Inc.。

> 我們的客戶有 gｲんĤЦ8、ｷouЯƧquﾑгє、๓เςг๏ร๏Ŧt ς๏гק๏гคtเ๏ภn、900913、ƒ4ᄃëв๏๏к, IПᄃ.。

注意：當網頁中需要配合整體視覺風格而出現全部大寫／小寫的情形，HTML 中請使用標準的大小寫規範進行書寫；並通過 `text-transform: uppercase;`／`text-transform: lowercase;` 對表現形式進行定義。

### 不要使用不道地的縮寫

正確：

> 我們需要一位熟悉 TypeScript、HTML5，至少理解一種框架（如 React、Next.js）的前端開發者。

錯誤：

> 我們需要一位熟悉 Ts、h5，至少理解一種框架（如 RJS、nextjs）的 FED。

## 爭議

以下用法略帶有個人色彩，即：無論是否遵循下述規則，從語法的角度來講都是**正確**的。

### 超連結之間增加空格

用法：

> 請 [提交一個 issue](#) 並分配给相關同事。

> 訪問我們網站的最新動態，請 [點擊這裡](#) 進行訂閱！

對比用法：

> 請[提交一個 issue](#) 並分配给相關同事。

> 訪問我們網站的最新動態，請[點擊這裡](#)進行訂閱！

### 簡體中文使用直角引號

用法：

> 「老师，『有条不紊』的『紊』是什么意思？」

對比用法：

> “老师，‘有条不紊’的‘紊’是什么意思？”

## 工具

倉庫 | 系列 | 語言
--- | -- | ---
[pangu.js](https://github.com/vinta/pangu.js) | pangu | JavaScript
[pangu-go](https://github.com/vinta/pangu) | pangu | Go
[pangu.java](https://github.com/vinta/pangu.java) | pangu | Java
[pangu.py](https://github.com/vinta/pangu.py) | pangu | Python
[pangu.rb](https://github.com/dlackty/pangu.rb) | pangu | Ruby
[pangu.php](https://github.com/cchlorine/pangu.php) | pangu | PHP
[pangu.vim](https://github.com/hotoo/pangu.vim) | pangu | Vim
[vue-pangu](https://github.com/serkodev/vue-pangu) | pangu | Vue.js (Web Converter)
[intellij-pangu](https://plugins.jetbrains.com/plugin/19665-pangu) | pangu | Intellij Platform Plugin
[autocorrect](https://github.com/huacnlee/autocorrect) | autocorrect | Rust, WASM, CLI tool
[autocorrect-node](https://github.com/huacnlee/autocorrect/tree/main/autocorrect-node) | autocorrect | Node.js
[autocorrect-py](https://github.com/huacnlee/autocorrect/tree/main/autocorrect-py) | autocorrect | Python
[autocorrect-rb](https://github.com/huacnlee/autocorrect/tree/main/autocorrect-rb) | autocorrect | Ruby
[autocorrect-java](https://github.com/huacnlee/autocorrect/tree/main/autocorrect-java) | autocorrect | Java
[autocorrect-go](https://github.com/longbridgeapp/autocorrect) | autocorrect | Go
[autocorrect-php](https://github.com/NauxLiu/auto-correct) | autocorrect | PHP
[autocorrect-vscode](https://marketplace.visualstudio.com/items?itemName=huacnlee.autocorrect) | autocorrect | VS Code Extension
[autocorrect-idea-plugin](https://plugins.jetbrains.com/plugin/20244-autocorrect) | autocorrect | Intellij Platform Plugin
[jxlwqq/chinese-typesetting](https://github.com/jxlwqq/chinese-typesetting) | other | PHP
[sparanoid/space-lover](https://github.com/sparanoid/space-lover) | other | PHP (WordPress)
[sparanoid/grunt-auto-spacing](https://github.com/sparanoid/grunt-auto-spacing) | other | Node.js (Grunt)
[hjiang/scripts/add-space-between-latin-and-cjk](https://github.com/hjiang/scripts/blob/master/add-space-between-latin-and-cjk) | other | Python
[hustcc/hint](https://github.com/hustcc/hint) | other | Python
[n0vad3v/Tekorrect](https://github.com/n0vad3v/Tekorrect) | other | Python

## 誰在這樣做？

網站 | 文案 | UGC
--- | --- | ---
[Apple 中國](https://www.apple.com/cn/) | Yes | N/A
[Apple 香港](https://www.apple.com/hk/) | Yes | N/A
[Apple 台灣](https://www.apple.com/tw/) | Yes | N/A
[Microsoft 中國](https://www.microsoft.com/zh-cn/) | Yes | N/A
[Microsoft 香港](https://www.microsoft.com/zh-hk/) | Yes | N/A
[Microsoft 台灣](https://www.microsoft.com/zh-tw/) | Yes | N/A
[LeanCloud](https://leancloud.cn/) | Yes | N/A
[V2EX](https://www.v2ex.com/) | Yes | Yes
[Apple4us](https://apple4us.com/) | Yes | N/A
[Ruby China](https://ruby-china.org/) | Yes | Yes
[少數派](https://sspai.com/) | Yes | N/A

## 參考文獻

- [Guidelines for Using Capital Letters - ThoughtCo.](https://www.thoughtco.com/guidelines-for-using-capital-letters-1691724)
- [Letter case - Wikipedia](https://en.wikipedia.org/wiki/Letter_case)
- [Punctuation - Oxford Dictionaries](https://en.oxforddictionaries.com/grammar/punctuation)
- [Punctuation - The Purdue OWL](https://owl.english.purdue.edu/owl/section/1/6/)
- [How to Use English Punctuation Correctly - wikiHow](https://www.wikihow.com/Use-English-Punctuation-Correctly)
- [格式 - openSUSE](https://zh.opensuse.org/index.php?title=Help:%E6%A0%BC%E5%BC%8F)
- [全形和半形 - 維基百科](https://zh.wikipedia.org/wiki/%E5%85%A8%E5%BD%A2%E5%92%8C%E5%8D%8A%E5%BD%A2)
- [引號 - 維基百科](https://zh.wikipedia.org/wiki/%E5%BC%95%E8%99%9F)
- [疑問驚嘆號 - 維基百科](https://zh.wikipedia.org/wiki/%E7%96%91%E5%95%8F%E9%A9%9A%E5%98%86%E8%99%9F)

## Forks

衍生專案的用法可能與本專案存在差異。

- [mzlogin/chinese-copywriting-guidelines](https://github.com/mzlogin/chinese-copywriting-guidelines)
