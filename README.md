## password_management 密碼管理系統

#### 使用者需求：

1. 密碼分層別類

| 項目              |     資料   |
| ----------------- | --------- |
| 網站（WEB）        | 帳號、密碼 |
| 資料庫（DB）       | 帳號、密碼 |
| Office金鑰         | 金鑰      |
| 金流               | 帳號、密碼 |
| 設備（防火牆、NAS） | 帳號、密碼 |
| User電腦ID         | 帳號 |

2. 密碼需嚴謹加密

	1. 儲存在資料庫的密碼需要經過編碼加密
	2. 網頁登入的安全性

3. 使用者權限

	1. 不同的權限，可以看到的密碼種類不同
	2. 有代理人分派權限的功能

#### 開發者的建議需求：

1. 是否需要首頁，或者首頁即是登入畫面?
2. 可以新增帳號的功能?
3. 有修改使用者的權限功能?
4. 網站需要https加密?

#### 系統流程圖：


