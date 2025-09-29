# 概念
## git

git 目的為追蹤專案下的檔案異動 (加入、刪除、修改)。

是一種版本控制系統 (Version Control System，VCS)，進一步分類，他屬於 **分散式** 版本控制系統 (Distributed Version Control System，DVCS)。

## 版本控制系統分類

分為兩類:
- **集中式** 版本控制系統 (Centralized Version Control System，CVCS)
- **分散式** 版本控制系統 (Distributed Version Control System，DVCS)

| 項目     | 集中式版本控制系統（Centralized VCS） | 分散式版本控制系統（Distributed VCS） |
| ------ | -------------------------- | -------------------------- |
| 結構     | 所有版本集中在中央伺服器               | 每個開發者有完整的版本庫               |
| 代表工具   | SVN、CVS                    | Git、Mercurial              |
| 網路需求   | 操作多需連線中央伺服器                | 大多數操作可離線進行，不時再更新同步             |
| 效能     | 操作需聯網               | 本地操作                  |
| 單點故障風險 | 伺服器掛掉可能失資料               | 每人都有備份                   |
| 架構圖 | ![CVCS 架構圖](./images/CVCS.jpg)               | ![DVCS 架構圖](./images/DVCS.jpg)                   |

## git / github

