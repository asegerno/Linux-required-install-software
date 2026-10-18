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

## ⚖️ 許可證說明 (License)

本專案採用 **[The Unlicense](https://unlicense.org/)** 授權協議，釋入公有領域（Public Domain）。
