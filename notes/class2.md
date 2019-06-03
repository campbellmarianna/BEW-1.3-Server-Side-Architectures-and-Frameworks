# Check for Understanding
1. virtualenv venv
2. source venv/bin/activate
    pip install django
3. python3 manage.py startapp <name>


```
class Topping(models.Model):
    # ...
    pass

class Pizza(models.MOdels):
    # ...
    toppings = model.ManyToManyField(Topping)

```
Source: djangoproject.com/en/2.2/topics/db/models/#many-to-many-relationships

# Pizza with 6 Topping
pizza = Pizza()
pizza.price = 3.99
pizza.save()

pizza = Pizza(price=3.99)
pizza.sauce()
