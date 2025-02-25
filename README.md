# Домашнее задание к занятию "`Кеширование Redis/memcached " Зарецкий Ю.М.



### Задание 1

Приведите примеры проблем, которые может решить кеширование.

**Ответ:**
 
1) Повышение производительности  достигается за счет
складывания в кэш данных, к которым чаще всего происходит
обращение;
2) Увеличение скорости ответа;
3) Экономия ресурсов базы данных, например, применяя
кэширование тяжелых запросов;
4) Сглаживание бустов трафика. Например, во время черной
пятницы онлайн-магазины используют кэш, чтобы переживать
резкое увеличение трафика.

### Задание 2

`Установите и запустите memcached.

**Ответ:**

![Задание 2](https://github.com/daroutine/cash/blob/main/%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B52.png)`


---

### Задание 3

Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5.

Приведите скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы.


**Ответ:**

![Задание 3](https://github.com/daroutine/cash/blob/main/3%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5.png)`

### Задание 4

Запишите в Redis несколько ключей с любыми именами и значениями.

Через redis-cli достаньте все записанные ключи и значения из базы, приведите скриншот этой операции.

**Ответ:**

![Задание 4](https://github.com/daroutine/cash/blob/main/4%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5.png)`
