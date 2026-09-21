# Hi, I'm Ryu 👋

Pythonを中心に、機械学習・生成AI・データ分析を活用したアプリケーションを開発しています。  
TypeScript / Next.jsによるWeb開発にも取り組んでいます。

コードによる処理と生成AIの役割分担、外部APIとの連携、データ分析の検証方法を意識して制作しています。

## Featured Projects

### [ML Experiment Diff Agent](https://github.com/ruy00803/ml-diff-agent)

機械学習実験のPython・Notebookを比較し、変更点と確認事項をGeminiで日本語に整理するアプリです。  
差分抽出はPython、意味の整理はLLMが担当。送信前の差分確認と、APIを模擬した自動テストを実装しています。  
`Python` `Streamlit` `Gemini API` `pytest` `GitHub Actions`

### [Activity Tracker](https://github.com/ruy00803/activity-tracker-v2)

Google Calendar・Google Tasksと連携し、予定・タスク・実際の活動時間を一元管理する個人用Webアプリです。  
OAuth認証、サーバー側でのAPI連携、活動時間の記録・可視化を実装しています。  
`TypeScript` `Next.js` `Google APIs` `Supabase` `Recharts`

[アプリ](https://activity-tracker-v2.vercel.app/) — 本人限定ログインのため、画面はリポジトリのスクリーンショットでも紹介しています。

### [Multilingual Restaurant Website](https://github.com/ruy00803/parmenara-tokoname)

パルメナーラ イオンモール常滑店向けに制作した、4言語対応の店舗Webサイトです。  
日本語・英語・韓国語・中国語（簡体字）の言語切替と、スマートフォン・PCでの店舗情報・メニュー表示に対応しています。  
`TypeScript` `Next.js` `next-intl` `Tailwind CSS`

[Webサイト](https://parmenara-tokoname.vercel.app/)

### [Baseball Draft Prediction](https://github.com/ruy00803/baseball-draft-prediction)

課題で提供された架空の野球選手データを使った、ドラフト指名有無の予測プロジェクトです。  
特徴量設計と勾配ブースティングを比較し、Target Encodingを学習fold内で処理する評価コードを整備しています。修正後の元データによる再評価は未実施です。  
`Python` `scikit-learn` `LightGBM` `XGBoost` `Optuna`

## Analysis & Learning

### [Employee Attrition Analysis](https://github.com/ruy00803/Employee-Attrition-Analysis-HR-Strategy-Proposal)

東京大学GCIの最終課題として取り組んだ、架空企業の人事データ分析の学習記録です。  
EDA・LightGBMによる離職予測と施策仮説の検討を、Notebookと当時の提出資料にまとめています。元データ・最終コードが未収録のため、掲載数値は当時の記録として扱っています。  
`Python` `Pandas` `LightGBM` `Jupyter Notebook`

## Tech Stack

- Languages: Python, TypeScript, JavaScript, HTML, CSS
- Data & ML: Pandas, NumPy, scikit-learn, LightGBM, XGBoost, Optuna
- Apps & Web: Streamlit, Next.js, Tailwind CSS, Supabase
- Tools: Git, GitHub, pytest, GitHub Actions
