# onejav-crawler

一个基于 Python + Docker 的爬虫，用来抓取 [onejav.com](https://onejav.com) 的影片信息（番号、标题、演员、磁力链接）。

## 使用方法

### 本地运行
```bash
pip install -r requirements.txt
python app/main.py
```

数据会存储在 `onejav.db` SQLite 数据库中。

### Docker 构建
```bash
docker build -t yourname/onejav-crawler .
docker run --rm yourname/onejav-crawler
```
