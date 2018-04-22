# Emoji

一款制作表情包的页面，让用户可以自行去设计以及二次修改表情包。并且利用虚拟货币进行交换，虚拟货币可以通过设计与评论他人获取，从而形成兴趣论坛。其次，对于表情包，有很多细化的分类，所以我们添加了标签，进而形成大众分类。

## Usage

1. Install requirements.

```python
pip install -r requirements.txt
```

2. Create database.

```python
python manage.py migrate
```

3. Run the server.

```python
python manage.py runserver
```

4. Visit http://127.0.0.1:8000/
