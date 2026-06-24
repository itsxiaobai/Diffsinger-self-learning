# 自製 Diffsinger 虛擬歌手

**這是一個自主學習專案，無法保證能完成或成品擁有專業級品質，但歡迎提出建議或提供協助**

**部份失敗聲音庫已設為 pre-release 並發布在 release 頁面**

新歌手庫 Xe 發布啦！

## 檔案說明

- ~~DiffSinger_colab_translate_ver.ipynb：適用於 Google Colab 的 Diffsinger 虛擬歌手訓練程式，已經完成繁體中文化。~~ 檔案已拋棄
[原始來源](https://github.com/MLo7Ghinsan/DiffSinger_colab_notebook_MLo7/blob/main/DiffSinger_colab_notebook.ipy)
- SVS-Singing-Voice-Database-Tutorial-gpttranslate.txt：使用 ChatGPT 中文翻譯的 "SVS Singing Voice Database - Tutorial" 純文字版（不建議直接參考）。[原始來源](https://docs.google.com/document/d/1uMsepxbdUW65PfIWL1pt2OM6ZKa5ybTTJOpZ733Ht6s/view)
- train_files：存放錄製樣本的資料夾。
- phonemes.md：標記中文樣本用的對照表（雖然最後其實沒有用到）。[原始來源](https://github.com/2xxbin/diffsinger-chinese-support/blob/main/phonemes.md)
- sumi_DiffSinger_colab_notebook_translated.ipynb：由 [Sumi](https://github.com/usamireko) 製作的 Diffsinger 修正版本，已經完成大部分繁體中文化。[原始來源](https://github.com/usamireko/DiffSinger4Colab/blob/main/DiffSinger_colab_notebook.ipynb)

## 範例

Gabriel: 見[此連結](https://odysee.com/@itsxiaobaibackupchannel:d/output:d0e?r=14jXQtjTESfN1aJK6reBREAq9421Lz6v)

Xe: 見[此連結](https://odysee.com/@itsxiaobaibackupchannel:d/virtual-singer-self-learning-xe:0)

## 安裝＆使用說明

1. 下載[官方 OpenUTAU]((https://github.com/openutau/OpenUtau))、[聲音庫](https://github.com/itsxiaobai/Diffsinger-self-learning/releases/download/Xe_v0.1/Xe.zip)及 [Diffsinger 引擎依賴套件](https://github.com/openvpi/vocoders/releases/download/pc-nsf-hifigan-44.1k-hop512-128bin-2025.02/pc_nsf_hifigan_44.1k_hop512_128bin_2025.02.oudep)
2. 啟動 OpenUTAU，在標籤列「工具」 → 「安裝歌手...」，選擇聲音庫檔案[^1]
3. 在 Archive Flie Encoding 中，選擇 "Unicode (UTF-8)" 後，點選「下一步」
4. 點選「安裝」
5. 在標籤列「工具」 → 「安裝依賴性（.oudep）...」，選擇依賴套件檔案，等待安裝完成[^2]
6. 在新音軌中的「選取歌手」，選擇剛安裝好的歌手（Xe）
7. 開始使用！

 （等待影片說明）

## 感謝名單

- 育群老師：提供麥克風設備
- 創崴：提供算力額度
- Ray Pan：提供算力額度
- Eo：標記樣本
- 子佑：標記樣本
- David：提供錄音環境

## 參考來源

- [SOFA AI 自動標記](https://github.com/qiuqiao/SOFA)
- [Diffsinger 官網](https://diffsinger.com/)

[^1]: 如果您是 Windows 用戶，可直接將檔案拖入視窗安裝
[^2]: 如果您是 Windows 用戶，可直接將檔案拖入視窗安裝[^3]
[^3]: 至於 MacOS ... 我不知道🙃

Made with ❤️
