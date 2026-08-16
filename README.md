# Wellbeing Sensing × IoT Demo

An interactive academic demonstration that combines **human-state sensing**, **AI-based state estimation**, and **smart-home IoT control**.

人の状態センシング、AIによる状態推定、スマートホームIoT制御を組み合わせたインタラクティブな研究デモです。

## Research concept / 研究コンセプト

The demo illustrates the following research flow:

1. Estimate the user's state from facial-expression and wearable HRV signals.
2. Combine multiple signals to calculate a simulated stress index.
3. Let an AI Agent select an appropriate form of support.
4. Connect the decision with lighting, music, air conditioning, and other IoT devices.

本デモでは、表情とウェアラブルHRVから利用者の状態を推定し、AI Agentが適切な支援を判断してIoT機器へつなげる流れを可視化します。

## Main features / 主な機能

- Facial-expression simulation with four selectable states
- Simulated heart rate and HRV signals
- Multimodal stress estimation
- AI Agent decision log
- Interactive smart-home floor plan
- Responsive, dependency-free static website

## Important note / 重要事項

This website is a **research and presentation demo**. The sensor readings and AI decisions are simulated. It is not a medical device and must not be used for diagnosis or treatment.

このウェブサイトは研究発表用のデモです。センサーデータとAIの判断はシミュレーションであり、医療上の診断や治療を目的としたものではありません。

## Run locally / ローカル実行

No build step or external dependency is required.

```text
stress-iot-deploy/
├─ index.html
└─ faces/
   ├─ calm.png
   ├─ happy.png
   ├─ sad.png
   └─ angry.png
```

Open `index.html` directly, or serve the folder with any static HTTP server.

## GitHub Pages

The site is designed to be published from the repository root with GitHub Pages:

1. Open **Settings → Pages**.
2. Select **Deploy from a branch**.
3. Select the `main` branch and `/(root)` folder.
4. Save and wait for deployment to complete.

The public URL will use this format:

```text
https://<github-user>.github.io/<repository-name>/
```

## Technology

Pure HTML, CSS, JavaScript, Canvas, and SVG. No external runtime dependencies are used.
