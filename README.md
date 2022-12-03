# Fast API

- Qiita Advent Calender の [API設計 ハンズオン](https://qiita.com/yousuke_1112/items/5bb4b5b0c3512662d2fd) をやってみた

- デプロイ環境：[render](https://render.com/)
- Create Web Service の前の Start command は次のように設定
  ```
  gunicorn -w 4 -k uvicorn.workers.UvicornWorker main:app
  ```
