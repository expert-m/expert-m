```python
import world


michael_sulyak = world.people.get_or_create(
  name='Michael Sulyak',
  nickname='expert_m',
  linkedin='https://www.linkedin.com/in/michael-sulyak/',
)

while True:
  try:
    michael_sulyak.create_something_cool()
  except world.exceptions.BaseException:
    pass
```
