### password_management
密碼管理系統

#### 客戶需求：

1. 密碼分層別類

<table>
    <tr>
        <td>網站（WEB）</td>
        <td>帳號、密碼</td>
    </tr>
    <tr>
        <td>資料庫（DB）</td>
        <td>帳號、密碼</td>
    </tr>
    <tr>
        <td>Office金鑰</td>
        <td>金鑰</td>
    </tr>
    <tr>
        <td>金流</td>
        <td>帳號、密碼</td>
    </tr>
    <tr>
        <td>設備（防火牆、NAS）</td>
        <td>帳號、密碼</td>
    </tr>
    <tr>
        <td>User電腦ID</td>
        <td>帳號、密碼</td>
    </tr>
</table>

2. 密碼需嚴謹加密

<ol>
	<il>儲存在資料庫的密碼需要經過編碼加密</il>
	<il>網頁登入的安全性</il>
</ol>

3. 使用者權限

<ol>
	<il>不同的權限，可以看到的密碼種類不同</il>
	<il>有代理人分派權限的功能</il>
</ol>

#### 開發者的建議需求：

1. 是否需要首頁，或者首頁即是登入畫面?
2. 可以新增帳號的功能?
3. 有修改使用者的權限功能?
