# resolver
Clase para resolver nombres de host que utiliza una cache para almacenar los nombres ya resueltos.

Uso:
```
$ python
>>> from resolver import Resolver
>>> resolver = Resolver()
>>> ip = resolver('www.google.com')
>>> print(ip)
172.217.17.4
```

---

Tags: python
