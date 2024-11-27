# Rime韓文（可漢諺混寫）輸入方案

譯文：[简体中文](../README.md)

## 簡介

這是一個基於[Rime](https://rime.im/)的韓文（可漢諺混寫）輸入方案。可以以形碼的方式，方便地輸入諺文和漢字。

## 特性

- 採用最常見的[두벌식鍵盤佈局](https://ko.wikipedia.org/wiki/%EB%91%90%EB%B2%8C%EC%8B%9D_%EC%9E%90%ED%8C%90)


- 支援Unicode已收錄的所有諺文音節組合

  [Hangul Syllables](https://www.unicode.org/charts/PDF/UAC00.pdf)

- 實時組合所輸入的谚文音节諺文音節

  輸入碼會實時轉換成合法的諺文音節，提高交互性。

- 單漢字的讀音全部來自[Unihan數據庫](https://www.unicode.org/charts/unihan.html)

  能輸入Unihan數據庫中有朝鮮語音讀的所有漢字。

## 安裝指南

1. 安裝好對應平台的輸入法（安裝地址見[Rime官方下載頁](https://rime.im/download/)）；
2. 將`koreanMT.schema.yaml`和`koreanMT.dict.yaml`添加到用戶文件夾；
4. 重新部署您的輸入法
5. 切換到`朝鲜文_MT`使用輸入法

## 使用說明

### 鍵盤佈局

<figure>
    <img src="../src/keyboard_layout.svg" alt="圖1. 鍵盤佈局">
    <figcaption style="text-align: center; color: rgba(0, 0, 0, 60%); font-size: 0.85em">圖1. 鍵盤佈局</figcaption>
</figure>

## 貢獻

可透過Pull Request來進行代碼貢獻和Issue來提出問題。

## 协议

以MIT協議發佈。