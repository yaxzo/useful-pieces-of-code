# путь_к_файлу/название файла

что делает этот код

  ----

# db_session.py
код для создания сессии в БД, с помощью sqlalchemy. полезно для проектов на flask. 
ещё требуется создавать новый файл `__all_models.py`, в котором будут храниться модели. испортировать модели в формате:
```
from . import <название файла>
```

# async_ThreadPoolExecutor.py

код, который возвращает все результаты асинк функций с заданными аргументами, распределяя их по воркерам. и причем результаты отсортированные в том порядке, в котором корутины были заданы в листе coros. в общем, работает как map в ThreadPoolExecutor, только асинк. нужно чтобы сделать несколько запросов, и чтобы не очень быстро, чтобы за ддос не стопили, и не очень медленно. workers надо подбирать

а и еще там шкала прогресса есть

iter, thanks

   ----

# timer_decorator.py

декоратор, который возвращает время выполнения декорированной с его помощью функции

   ----

# cached_decorator.py

декоратор, который кэширует результат выполнения декорированной с его помощью функции

   ----

# .gitignore

шаблон .gitignore файла для Python

  ----
