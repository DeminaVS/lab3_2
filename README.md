# lab3_2
# Цель: освоить работу с коллекциями dict (словарь) и set (множество) в Python, изучить их методы и операции, а также научиться выбирать подходящую структуру данных для эффективного решения задач по обработке, хранению и анализу информации.
# 3.2.9 Напишите функцию, которая находит товар с самой высокой ценой в словаре.
```
def find_most_expensive(products):
    """Найти самый дорогой продукт в словаре 'products'."""
    if not products:
        return None

    max_price = -float('inf')
    most_expensive = None

    for product, price in products.items():
        if price > max_price:
            max_price = price
            most_expensive = product

    return most_expensive


product_prices = {'Laptop': 1200, 'Mouse': 25, 'Keyboard': 75, 'Monitor': 300}
print(find_most_expensive(product_prices))
```
# Вывод
Я освоила работу с коллекциями dict (словарь) и set (множество) в Python, изучила их методы и операции, а также научилась выбирать подходящую структуру данных для эффективного решения задач по обработке, хранению и анализу информации.
