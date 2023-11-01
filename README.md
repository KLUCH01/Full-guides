def create_array_list(elements):
    # Создаем пустой список, аналогичный ArrayList
    array_list = []

    # Добавляем элементы в ArrayList
    for element in elements:
        array_list.append(element)

    return array_list

Пример использования
elements = [42, "Hello", 3.14]
result = create_array_list(elements)
print(result)
