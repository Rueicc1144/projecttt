## 注音標示簡易說明
[此網站](<[http://example.com/](https://www.cmex.org.tw/phon/)>) 可以協助標示注音，提供標註後的程式碼
正常轉換後輸出程式碼如下
```
<link type="text/css" rel="stylesheet" href="http://www.cmex.org.tw/phon/phon.css" charset="utf8">
<div class="dummy2 lr h ruby"><div><idiv><ruby>意<rt>ㄧˋ</rt></ruby></idiv><idiv><ruby>見<rt>ㄐㄧㄢˋ</rt></ruby></idiv><idiv><ruby>回<rt>ㄏㄨㄟˊ</rt></ruby></idiv><idiv><ruby>饋<rt>ㄎㄨㄟˋ</rt></ruby></idiv></div></div>
```
請刪掉
```
<link type="text/css" rel="stylesheet" href="http://www.cmex.org.tw/phon/phon.css" charset="utf8">
<div class="dummy2 lr h ruby">
```
留下後面部分即可，甚至可以刪掉
```
</idiv><idiv>
```
不影響注音的標註，可以簡化程式碼可閱讀性
