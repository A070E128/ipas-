主題一：資訊安全管理概念：

#  1_1_資訊安全目標_機密性、完整性與可用性
```
保密性（Confidentiality）：
一般稱秘密，是指個人或團體的訊息不為其他不應獲得者獲得。 在電腦中，許多軟體包括郵件軟體、網路瀏覽器等，都有保密性相關的設                             定，用以維護用戶資訊的保密性，另外木馬軟體或駭客有可能會造成保密性的問題。
完整性（Integrity）：
指在傳輸、存儲信息或數據的過程中，確保信息或數據不被未授權的篡改或在篡改後能夠被迅速發現。
可用性（Availability）：
意為確保資訊、系統及服務，依需求提供授權的人員存取。
責任性（Accountability）：
組織內有許多部門與個人，當事件發生時該由誰負責處理必須明確規定。
機密性（Confidentiality）：
組織的資訊不應讓未經授權的人員存取。
```
其他資訊安全特性
```
鑑別性（Authenticity）
確保資料和交易的真實性
可歸責性（Accountability）
必須掌握的原則是每個存取資訊或系統的成員都有獨立單一的識別
不可否認性（Non-repudiation）
當事人無法否認其曾經出於本身意願執行過的行為
可靠度（Reliability）
可靠度指的是服務的穩定性
```
資訊安全的三個 P
```
人員若不遵守資訊安全程序，產品就無從發揮功效。
人員 (People)
產品 (Product)
程序 (Process)
```
CISSP的資訊安全的領域
```
資訊安全與風險管理 (Information Security and Risk Management)
存取控制 (Access Control)
應用程式安全 (Application Security)
密碼學 (Cryptography)
通訊與網路安全 (Telecommunications and Network Security)
實體安全 (Physical Security)
營運安全 (Operations Security)
安全架構與設計 (Security Architecture and Design)
業務持續與災害復原計畫 (Business Continuity and Disaster Recovery Planning)
法律、規章、遵循性與調查 (Law, Regulations, Compliance, and Investigations)

```
資訊安全的三元素
```
實體安全 Physical Security
營運安全 Operational Security
管理與政策Management and Policies
```
實體安全
```
實體安全保護你的資產與資訊，讓未經授權的人無法做實體接觸。所保護的是看得見、摸得著、並能被偷的東西。
實體安全的維護有以下三個重點：
讓你所保護的實體位置不要成為受攻擊的目標。
即時的偵測到侵入或竊盜的發生。
在損失重要資訊或系統遭侵入後，能夠快速復原。
```
營運安全
```
營運安全在於確保組織經常能夠正常運作，這是大多數資訊安全人員的主要工作範圍。營運安全包括以下重點：
電腦、網路及有線與無線通訊系統的運作。
資訊與檔案管理。
存取控制、身分認證及網路的安全結構設計。
經常性的網路維運、與其它網路的連結、備份計畫與復原計畫等。

```
營運安全
```
營運安全在於確保組織經常能夠正常運作，這是大多數資訊安全人員的主要工作範圍。營運安全包括以下重點：
電腦、網路及有線與無線通訊系統的運作。
資訊與檔案管理。
存取控制、身分認證及網路的安全結構設計。
經常性的網路維運、與其它網路的連結、備份計畫與復原計畫等。
```
管理與政策
```
資訊安全政策若要發揮作用，需要組織最高層的絕對支持。
一般組織的資訊安全政策應考慮以下項目：
行政管理政策 (administrative policies)
軟體設計要求 (software design requirements)
災害復原計畫 (disaster recovery plans, DRP)
資訊政策 (information policies)
安全政策 (security policies)
使用政策 (usage policies)
使用者管理政策 (user management policies)

```
資訊安全與管理
```
資訊安全屬於企業治理重要環節之一，必須建立一套有效的管理系統
企業應了解本身的弱點、擁有的資源、重要的資產、限制條件等，分析外部的環境、面對的威脅有哪些、威脅發生時的衝擊、可行的對策
```
資訊安全的目標
```
預防 (Prevention)：預防電腦或資訊被違規使用。
偵測 (Detection)：  事件發生時能夠即時的偵測。
反應 (Response)：  發展策略因應遭受的攻擊與損失。
```
存取控制的模式
```
存取控制 (access control) 決定使用者與系統間之溝通，以防止系統資源或資料被未授權存取。它可分為三種模式：
強制存取控制 (mandatory access control, MAC) 是由系統管理員 (administrator) 統一規定哪些人能存取哪些系統、檔案或資料。
任意存取控制 (discretionary access control, DAC) 讓每個系統、檔案或資料的所有人 (owner) 決定存取權限。
角色基準存取控制 (role-based access control, RBAC) 存取權限非因人而制定，而是以其在組織中的角色 (如職務) 決定。

```
身分認證的要素
```
身分認證 (authentication) 是資訊安全的重要環節，它讓使用者或要求存取的系統證明自己的身分。認證有以下三種要素：
所知之事 (something you know) 例如通關密碼 (password) 或是 PIN。
所持之物 (something you have) 例如智慧卡或其它身分證明裝置。
所具之形 (something you are) 例如指紋或視網膜比對。
以上三者中同時使用多者 (multi-factor authentication)，被視為較佳之身分識別系統；例如同時使用智慧卡與通關密碼。
```
身分認證的方法
```
通關密碼使用 something you know。Password Authentication Protocol (PAP) 是將使用者名稱與通關密碼以明碼形式送到伺服器上比對，這是最簡單的認證方法但並不安全。
生物特徵 (biometrics) 使用 something you are，包括手的比對 (如指紋、掌紋)，臉部特徵，視網膜 (retina) 與虹膜 (iris) 掃描等。
安全代符 (security tokens) 使用 something you have，這種隨身攜帶的元件上儲存著比人腦能記憶的通關密碼複雜許多的認證資訊，使身分認證程序更加安全。常見的安全代符包括：
一次性密碼代符 (one-time password tokens)
智慧卡 (smart cards)
記憶卡 (memory cards)
無線射頻身分證明 (RFID)
```
身分認證的方法 (II)
```
Challenge Handshake Authentication Protocol (CHAP) 是一個握手協定 (handshake)：客戶端 (client) 送一個登入要求 (logon request) 給伺服器；伺服器回應一個挑戰 (challenge)。挑戰通常是一串隨機數。客戶端以金鑰 (key) 將挑戰加密後做成回應 (response) 送給伺服器後，伺服器以對應的金鑰驗證回應之正確性，以決定是否授權客戶端開始使用伺服器的資源。
```
身分認證的方法 (III)
```
憑證 (certificates) 是另一種常用的身分認證方法。如右圖，客戶端要使用應用伺服器的資源，它先與安全伺服器完成認證 (如使用 CHAP) 後取得一張憑證，客戶端以憑證就可以存取應用伺服器。憑證可能是一串很長的數字，或一張儲存著很長數字的智慧卡。
```
身分認證的方法 (IV)
```

```
資訊安全與管理
```
資訊安全屬於企業治理重要環節之一，必須建立一套有效的管理系統
企業應了解本身的弱點、擁有的資源、重要的資產、限制條件等，分析外部的環境、面對的威脅有哪些、威脅發生時的衝擊、可行的對策
```
Kerberos 是常用的單點登錄 (single sign-on) 技術。電腦設備間 (例如客戶端與應用伺服器之間) 的對話都以較有效率的對稱式 (symmetric) 加解密來完成，而密鑰則由密鑰分派中心 (KDC) 掌控。相較之下，憑證系統因為使用非對稱式加解密，故較 Kerberos 複雜。
```
常見的網路服務與協定
```
Mail：幾乎所有使用者都需要電子郵件服務。
Web：相關的安全考量應包含網站伺服器 (web server) 及客戶端的網路瀏覽器 (web browser)。
即時通訊 (instant messaging, IM)：IM 像是兩者或多者間的即時電子郵件，它有時會受到下載惡意碼攻擊。
Telnet：Telnet 允許遠端使用者以模擬終端機的方式連上系統，這種舊式的協定沒有安全防護，應該改採用較安全的協定，如 SSH 等。
File Transfer Protocol (FTP)：FTP 在網際網路常被使用，但經由 FTP 傳輸的資訊沒有加密，登入的通關密碼也多以明碼傳送，應小心使用。
Domain Name Service (DNS)：DNS 將網路位址如 www.abc.net翻譯為TCP/IP 位址如 192.168.0.110。
```
設計網路安全的四個考量
```
1.制定設計目標：
制定目標時應考慮四項「安全組件 (security components)」。
2.切割安全區域：
將複雜的網路環境切割成安全區域，便於管理區域間的通訊權限。
3.融入新科技：
使用新科技常能有效的強化網路安全。
4.管理資訊風險： 
各種安全的設計與努力，其目的不外乎保護組織的利益，降低風險。
```
制訂設計目標
```
Confidentiality(保密性), Integrity(完整性), 與 Availability（可用性） 常被合稱為網路安全的 CIA
但 責任性（Accountability） 也經常被考慮在資訊安全的設計目標裡。我們將這四個安全組件簡述如下：
保密性 (confidentiality)：保密性的目的在防止未經授權的人或系統存取資料或訊息。
完整性 (integrity)：完整性在於確保被使用的為正確資料。
可用性 (availability)：可用性在保護資料不致流失，無法使用的資訊等於沒有資訊。
責任性 (accountability)：組織內有許多部門與個人，當事件發生時該由誰負責處理必須明確規定。

```
切割安全區域 (I)
```
Internet(網際網路): 全球網路 (global network) 連結電腦與個別的網路。
Intranet(內部網路): 公司或組織內的私人網路 (private network)。
Extranet(外部網路): Extranet 包含組織內的 Intranet 與外部和夥伴組織間的連結，夥伴可以是供應商、承包商等。它是兩個可以互相信任 (trustworthy) 的組織之間的連線，這種連線可以用專線或經由網際網路上架設 VPN 來完成。
```
切割安全區域 (II)
```
Demilitarization Zone (DMZ) 中文譯作非軍事區或安全區，是指放置公開資訊 (如網站) 的區域。可用防火牆將外部、內部、與 DMZ 分隔開。
```
融入新科技 (I)
```
Virtual Local Area Networks (VLAN)
公司組織龐大，我們將 LAN 分割為數個虛擬的 VLAN 的好處為：
降低 LAN的廣播(broadcast)流量
提高網路效能且方便管理
降低對網路實體連結的依賴
強化資訊安全管理，可以將權限相當的使用者劃分在同一個 VLAN 區域內。
```
融入新科技 (II)
```
Network Address Translation (NAT)
IP 位址有被用罄的顧慮，故部分私有 IP 位址 (如下) 被保留給內部 LAN 使用，其上所有電腦在公開網路上共用一個 IP 位址。
10.0.0.0 – 10.255.255.255
172.16.0.0 – 172.31.255.255
192.168.0.0 – 192.168.255.255
使用 NAT 的公司與外部網路只有一個接點，可以有效隱藏內部網路不為外部知曉。
NAT 伺服器可以監控進出的資料，所以除了提供 IP 位址的翻譯外，兼具部分的防火牆過濾功能。 

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```


