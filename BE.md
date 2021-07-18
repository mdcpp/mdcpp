# 這是後端目前已知的程式碼

## 重點程式碼
- [API 網址](https://github.com/QingdaoU/OnlineJudge/blob/c0219912d1c4ebc48cf2a8a44e03be92705c40f1/account/views/oj.py#L333)
- [django起點](https://github.com/QingdaoU/OnlineJudge)

## 已知漏洞

### OJ
- [可以上傳任意檔案(未確認檔案類型)](https://github.com/QingdaoU/OnlineJudge/blob/c0219912d1c4ebc48cf2a8a44e03be92705c40f1/account/views/oj.py#L76)
- [session 資源消耗過大](https://github.com/QingdaoU/OnlineJudge/blob/c0219912d1c4ebc48cf2a8a44e03be92705c40f1/account/views/oj.py#L333)
- CSRF