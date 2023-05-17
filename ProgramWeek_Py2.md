КНБ Блочный: https://app.edublocks.org/showcase/CXfN9qcqW04YiirI1qVw

КНБ Кодом:

```python
figure = input("камень/ножницы/бумага")
vibor_user = figure[0].lower()
variants = ["к", "н", "б"]
import random
vibor_comp = random.choice(variants)
if vibor_comp == vibor_user:
  print("Ничья.")
elif vibor_user == "к" and vibor_comp == "н":
  print("Победа 😎")
elif vibor_user == "б" and vibor_comp == "к":
  print("Победа 😎")
elif vibor_user == "н" and vibor_comp == "б":
  print("Победа 😎")
else:
  print("Проигрыш 😢")
```
