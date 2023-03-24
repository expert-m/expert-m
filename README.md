```python
import world


michael_sulyak = world.people.get_or_create(
  name='Michael Sulyak',
  site='https://sulyak.info/',
  linkedin='https://www.linkedin.com/in/michael-sulyak/',
)

while True:
  try:
    michael_sulyak.create_something_cool()
  except world.exceptions.BaseException:
    pass
```
