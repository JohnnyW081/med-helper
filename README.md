<div align="center">

# 💊 用药助手 · Med Helper · お薬管理

**定时提醒服药 · 管理用药计划**  
Medication Reminder & Management PWA

[![GitHub Pages](https://img.shields.io/badge/demo-online-brightgreen?style=flat-square)](https://johnnyw081.github.io/med-helper/)
[![PWA](https://img.shields.io/badge/PWA-ready-blue?style=flat-square)](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps)
[![License](https://img.shields.io/badge/license-MIT-lightgrey?style=flat-square)](LICENSE)

</div>

---

## 🌐 Language / 语言 / 言語

| 中文 | English | 日本語 |
|:----:|:-------:|:------:|
| [🇨🇳 简体中文](#-简体中文) | [🇬🇧 English](#-english) | [🇯🇵 日本語](#-日本語) |

---

## 🇨🇳 简体中文

### 简介

用药助手是一个**纯前端**用药提醒 PWA 应用，无需后端服务器，开箱即用。

支持 **中文 · English · 日本語** 三语即时切换，适合家庭多语言场景。

### 功能亮点

| 功能 | 说明 |
|------|------|
| 📋 **药品管理** | 添加、编辑、删除药品，支持名称/时间/剂量/日期 |
| 🔔 **用药提醒** | 浏览器通知 + 震动，到点准时提醒 |
| 📊 **每日进度** | 轮播展示待服药品，今日完成进度一目了然 |
| 📸 **拍照上传** | 拍下药盒照片，方便识别 |
| 🚨 **紧急呼叫** | 一键拨打紧急联系人 |
| 🌙 **4 种主题** | 午夜青 / 日落橙 / 纯黑 / 纯白 |
| 🌐 **3 种语言** | 中文 / English / 日本語，设置页一键切换 |
| ♻️ **回收指南** | 过期药物正确处理方式 |
| 📦 **PWA 离线** | 支持添加到桌面，离线可用 |

### 快速开始

```bash
# 克隆仓库
git clone https://github.com/JohnnyW081/med-helper.git
cd med-helper

# 直接打开（无需安装）
open index.html    # macOS
start index.html   # Windows
```

或直接访问 **[在线版](https://johnnyw081.github.io/med-helper/)**

### 技术栈

- **原生 HTML/CSS/JS** — 零依赖，无需构建
- **localStorage** — 数据持久化
- **PWA** — Service Worker 离线缓存
- **i18n** — 内置国际化引擎，3 语言实时切换

### 项目结构

```
med-helper/
├── index.html      # 主应用（含所有 CSS 和 JS）
├── sw.js           # Service Worker（离线支持）
├── manifest.json   # PWA 配置
├── icon.svg        # 应用图标
└── README.md       # 本文件
```

---

## 🇬🇧 English

### Overview

**Med Helper** is a **zero-dependency, pure frontend** PWA for medication reminders. No server, no build step — just open and use.

Instant language switching between **中文 · English · 日本語** makes it ideal for multilingual households.

### Features

| Feature | Description |
|---------|-------------|
| 📋 **Medication Management** | Add, edit, delete meds with name/time/dose/date |
| 🔔 **Push Reminders** | Browser notification + vibration at scheduled times |
| 📊 **Daily Progress** | Carousel view + completion bar |
| 📸 **Photo Upload** | Snap a picture of your pill box |
| 🚨 **Emergency Call** | One-tap emergency contact dial |
| 🌙 **4 Themes** | Midnight / Sunset / Black / White |
| 🌐 **3 Languages** | 中文 / English / 日本語, switch in Settings |
| ♻️ **Disposal Guide** | How to properly dispose of expired meds |
| 📦 **PWA Offline** | Install to home screen, works offline |

### Quick Start

```bash
git clone https://github.com/JohnnyW081/med-helper.git
cd med-helper
open index.html
```

Or try the **[live demo](https://johnnyw081.github.io/med-helper/)**

### Tech Stack

- **Vanilla HTML/CSS/JS** — no frameworks, no build tools
- **localStorage** — client-side persistence
- **PWA** — Service Worker for offline caching
- **i18n Engine** — built-in, 3 languages, instant switching

---

## 🇯🇵 日本語

### 概要

**お薬管理**は、サーバー不要で動作する**純粋なフロントエンド**PWAアプリケーションです。インストール不要で、すぐにお使いいただけます。

**中文 · English · 日本語** の3ヶ国語をリアルタイム切り替え対応。多言語対応のご家族に最適です。

### 機能一覧

| 機能 | 説明 |
|------|------|
| 📋 **お薬管理** | 名前・時間・用量・日付を設定 |
| 🔔 **服用リマインダー** | ブラウザ通知＋バイブレーション |
| 📊 **今日の進捗** | カルーセル表示＋完了バー |
| 📸 **写真アップロード** | 薬箱の写真を撮影 |
| 🚨 **緊急連絡** | ワンタップで緊急連絡先に発信 |
| 🌙 **4 テーマ** | ミッドナイト / サンセット / ブラック / ホワイト |
| 🌐 **3 ヶ国語** | 中文 / English / 日本語、設定画面で切替 |
| ♻️ **廃棄ガイド** | 期限切れ薬品の正しい処分方法 |
| 📦 **PWA オフライン** | ホーム画面に追加、オフラインでも使用可能 |

### クイックスタート

```bash
git clone https://github.com/JohnnyW081/med-helper.git
cd med-helper
open index.html
```

または **[オンラインデモ](https://johnnyw081.github.io/med-helper/)** へアクセス

### 技術スタック

- **Vanilla HTML/CSS/JS** — フレームワーク不要
- **localStorage** — データ保存
- **PWA** — Service Worker オフライン対応
- **i18n** — 内蔵翻訳エンジン、3ヶ国語リアルタイム切替

---

<div align="center">

**Made with 💊 for family — 为家人而做 — 家族のために**

</div>
