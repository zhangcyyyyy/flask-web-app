# flask-web-app

Flask 示例项目，通过 GitHub Actions 实现自动化测试与部署到头歌服务器。

## 项目结构

```
flask-web-app/
├── src/
│   ├── app.py          # Flask 应用，返回 Hello, NEU!
│   └── __init__.py
├── tests/
│   └── test_app.py     # 单元测试
├── requirements.txt    # Python 依赖
└── .github/
    └── workflows/
        └── cicd.yml    # CI/CD 工作流
```

## 本地运行

```bash
pip install -r requirements.txt
python src/app.py
```

## 测试

```bash
pytest tests/ -v
```
