# 简易博客搭建教程


------更新中-------

## 附录
### Django配置mysql

```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'temage',
        'USER': 'root',
        'PASSWORD': '',
        'HOST': '127.0.0.1',
        'PORT': '3306',
    }
}
```

在__init__.py中添加：

```python
import pymysql

pymysql.install_as_MySQLdb()
```