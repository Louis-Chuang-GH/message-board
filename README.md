# message-board

```
message-board/
├── app/                    ← 主程式碼資料夾
│   ├── main.py             ← FastAPI 入口點
│   ├── database.py         ← 資料庫連線設定
│   ├── models.py           ← SQLAlchemy 資料模型
│   ├── schemas.py          ← Pydantic 請求/回應模型
│   ├── crud.py             ← 資料庫操作邏輯
│   ├── auth.py             ← JWT 登入驗證邏輯
│   └── routers/            ← API 路由
│       ├── users.py        ← 使用者功能（註冊、登入）
│       └── comments.py     ← 留言功能（發文、回覆、刪除）
├── .gitignore
├── README.md
├── requirements.txt        ← Python 套件需求
├── .env                    ← 環境變數（不上傳 GitHub）
└── alembic/                ← 若使用 Alembic 可加上（可選）
```