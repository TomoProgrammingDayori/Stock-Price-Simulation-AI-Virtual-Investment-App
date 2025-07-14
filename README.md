# Stock Price Simulation & AI Virtual Investment App

---

## 📌 Overview

This is a web application for simulating stock price movements and performing AI-driven virtual investment strategies.  
Each week, the app automatically sends a report summarizing virtual investment results, while the AI re-evaluates and updates its strategy based on recent market conditions.  
Users receive notifications about buy/sell signals, making it a helpful tool for studying investment decision-making.

---

## 🔧 Key Features

- 📈 **Stock Price Simulation**  
  Simulates stock price fluctuations using methods such as random walks.

- 🧠 **AI-Driven Strategy Updates**  
  Rebuilds investment strategies weekly based on recent market trends (e.g., buy → hold → sell decisions).

- 📬 **Automated Report Delivery**  
  Sends a weekly email with virtual investment performance reports (implemented using Python’s email libraries).

- 🔔 **Buy/Sell Signal Notifications**  
  Notifies users when the AI detects buy or sell signals (via email or in-app notifications).

---

## 🛠 Tech Stack

- Python (Flask)
- pandas / numpy / scikit-learn (AI logic and calculations)
- matplotlib (graph generation)
- SMTP (email sending)
- SQLite (lightweight DB) or file-based data storage

---

## 🔒 Disclaimer

- This app is for virtual investment and simulation purposes **only**.  
- It is **not** intended for actual investment decisions.  
- Developed as a learning and experimental project.

---

> “Simulate the markets, explore strategies — all powered by AI.”


# 株価シミュレーション＆AI仮想投資アプリ

## 📌 概要
株価の変動をシミュレートし、AIによる仮想投資を行うWebアプリケーションです。週1回、仮想投資の成果をレポートとして自動送信し、戦略は毎週AIが再評価・更新。ユーザーは売買のタイミングを通知で受け取りながら、投資判断の参考にできます。

## 🔧 主な機能
- 📈 **株価のシミュレーション機能**  
  ランダムウォーク等を用いて株価変動をシミュレート

- 🧠 **AIによる投資戦略の自動更新**  
  毎週1回、直近の相場状況をもとに戦略を再構築（例：買い→ホールド→売り）

- 📬 **自動レポート配信機能**  
  仮想投資の成績を週1でメールで自動送信（Pythonのメール送信ライブラリ利用）

- 🔔 **売買通知機能**  
  売り・買いのシグナルが出た際に通知（メールまたはアプリ内）

## 🛠 使用技術
- Python（Flask）
- pandas / numpy / scikit-learn（AI処理）
- matplotlib（グラフ描画）
- SMTP（メール送信）
- SQLite（簡易DB） または ファイルベース保存



## 🔒 補足事項
本アプリはあくまで仮想投資ツールであり、実際の投資判断には使用しないでください。

実装当時は学習・検証目的で開発しました。
