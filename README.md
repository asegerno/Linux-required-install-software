# Linux-required-install-software

Linux 伺服器與工作站環境裝機必備套件、基礎工具與企業端點安全軟體 (Essential Software & Enterprise Endpoint for Linux).

---

## 📌 簡介 (Introduction)
本倉庫收集適用於 Linux 發行版（Debian, Ubuntu, RHEL, CentOS）之基礎維護套件與企業級終端安全防護方案。

---

## 🛡️ 企業級 Linux 安全端點 (Kaspersky Endpoint Security for Linux)
* **KESL GUI 12.5.0-1569 (AMD64 / x86_64 Debian 安裝包)**:
  [https://products.s.kaspersky-labs.com/endpoints/keslinux10/12.5.0.1569/multilanguage-INT-12.5.0.1569/7f741f26a4be485a826b08c33e060373/kesl-gui_12.5.0-1569_amd64.deb](https://products.s.kaspersky-labs.com/endpoints/keslinux10/12.5.0.1569/multilanguage-INT-12.5.0.1569/7f741f26a4be485a826b08c33e060373/kesl-gui_12.5.0-1569_amd64.deb)

### 快速安裝範例 (Ubuntu / Debian)
```bash
# 下載並安裝
wget https://products.s.kaspersky-labs.com/endpoints/keslinux10/12.5.0.1569/multilanguage-INT-12.5.0.1569/7f741f26a4be485a826b08c33e060373/kesl-gui_12.5.0-1569_amd64.deb
sudo dpkg -i kesl-gui_12.5.0-1569_amd64.deb
sudo apt-get install -f
```

---

## ⚖️ 專有軟體授權與許可證說明 (Proprietary Software Licensing & EULA)

### 1. 卡巴斯基專有商業授權 (Kaspersky Proprietary EULA)
* **Kaspersky Endpoint Security for Linux (KESL)** 為 **AO Kaspersky Lab** 之商業專有企業產品 (Proprietary Commercial Software)。
* 軟體之安裝、運行與維護完全受 [Kaspersky B2B 終端使用者授權協議 (EULA)](https://www.kaspersky.com/end-user-license-agreement) 規範。

### 2. 授權啟用與使用規範 (Usage & Licensing)
* **非公有領域**：KESL 安裝套件與驅動組件非公有領域、非開源軟體。
* **合法授權需求**：部署此企業防護端點必須配備有效之商業許可證金鑰。使用者須確保已自卡巴斯基官方取得合法授權。

### 3. 本倉庫文檔授權 (Documentation License)
本倉庫之 Bash 腳本範例與文檔說明採用 **[The Unlicense](https://unlicense.org/)** 釋入公有領域（Public Domain）。
