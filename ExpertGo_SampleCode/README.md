https://gihyo.jp/book/2022/978-4-297-12519-6/support

文字コードが Shift_JIS なので変換

```
 sudo apt-get install nkf
 find . -type f -exec nkf -w -Lu --overwrite {} +
```
