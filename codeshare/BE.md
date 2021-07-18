# 後端計劃書

## 方案

1. 使用OJ session
    可以看目錄有寫關於API的設定位置，寫一個session api 嵌入原有的api
    ### 缺點
    1. 增加原session系統的負擔
    2. 不好管理session
2. 自己寫一個session管理
    自己獨立一個session管理系統
    ### 缺點
    1. 無法同步登入
3. 邪教方案
    將整個python嵌入golang裡，讓golang可以完全控制python
    ### 缺點
    1. 傷肝
    2. 不確定穩定性