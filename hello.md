# 我的筆記

## 第一題：第一堂base64編碼
https://www.base64decode.org/
QnJlYWthbGxDVEZ7aGFwcHloYWNraW5naGlnaGhhYWhhfQo

## 第二題：Base64解碼
https://www.base64decode.org/
BreakALLCTF{53usZQ3hWW25dchZ7dXe}

## 第三題：ASCII
https://www.dcode.fr/ascii-code
BreakALLCTF{Amv0uDyervPtmVr9SSSK}
```python
a = '66 114 101 97 107 65 76 76 67 84 70 123 65 109 118 48 117 68 121 101 114 118 80 116 109 86 114 57 83 83 83 75 125'
>>> a.split()
['66', '114', '101', '97', '107', '65', '76', '76', '67', '84', '70', '123', '65', '109', '118', '48', '117', '68', '121', '101', '114', '118', '80', '116', '109', '86', '114', '57', '83', '83', '83', '75', '125']
>>> map(int, a.split())
<map object at 0x7fa5ebd08550>
>>> list(map(int, a.split()))
[66, 114, 101, 97, 107, 65, 76, 76, 67, 84, 70, 123, 65, 109, 118, 48, 117, 68, 121, 101, 114, 118, 80, 116, 109, 86, 114, 57, 83, 83, 83, 75, 125]
>>> for i in a.split():
...      print(chr(int(i)),end='')
... 
BreakALLCTF{Amv0uDyervPtmVr9SSSK}>>>
```

## 第四題：Base32
https://simplycalc.com/base32-decode.php
BreakALLCTF{9x485VS7wiitBZXUUhMe}

## 第五題：Morse code
https://morsecode.world/international/translator.html
INFOSECFLAGISMORSING

## 第六題：hello world
CTF{Hel10WorLD123}

