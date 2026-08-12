---
title: "System::Delegate< ReturnType(ArgumentTypes...)> класс"
linktitle: "Delegate< ReturnType(ArgumentTypes...)>"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Delegate< ReturnType(ArgumentTypes...)> класс. Представляет указатель на функцию, метод или объект‑функцию. Этот тип следует выделять в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа в C++."
type: docs
weight: 2200
url: /ru/cpp/system/delegate_returntype(argumenttypes...)_/
---
## Delegate< ReturnType(ArgumentTypes...)> class


Представляет указатель на функцию, метод или объект‑функцию. Этот тип следует выделять в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](../smartptr/) для управления объектами этого типа.

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


| Параметр | Описание |
| --- | --- |
| ReturnType | Тип возвращаемого значения функции, метода или указателя на объект‑функцию, который представлен классом. |
| ArgumentTypes | Список аргументов функции, метода или указателя на объект‑функцию, который представлен классом. |
## Методы

| Метод | Описание |
| --- | --- |
| [Delegate](./delegate/)() | Конструктор по умолчанию. Создаёт объект делегата, который не указывает ни на что. |
| [Delegate](./delegate/)(const Delegate\&) |  |
| [Delegate](./delegate/)(Delegate\&&) | Конструктор перемещения копии. Перехватывает владение сущностью, на которую указывает указанный делегат. |
| [Delegate](./delegate/)(T, typename std::enable_if<!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | Конструктор. Создаёт объект делегата из указанного указателя на свободную функцию или статический метод. |
| [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | Конструктор. Создаёт делегат из указанного указателя на объект‑функцию, созданный с помощью std::bind(). |
| [Delegate](./delegate/)(int, T\&) | Конструктор. Создаёт делегат из указанного объекта‑функции. |
| [Delegate](./delegate/)(long, T\&&) | Конструктор перемещения. Создаёт делегат из указанного объекта‑функции. |
| [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | Конструктор. Создаёт делегат, указывающий на указанный нестатический метод указанного объекта. |
| [Delegate](./delegate/)(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) | Конструктор. Создаёт делегат, указывающий на указанный нестатический метод указанного объекта. |
| [Delegate](./delegate/)(std::function\<R(Args...)>) | Создаёт объект делегата, указывающий на объект функции std::function. |
| [Empty](./empty/)() const | Определяет, пустой ли текущий объект делегата, т.е. не указывает ни на какую сущность. |
| [operator()](./operator()/)(ArgumentTypes...) const | Вызывает функцию, метод или объект‑функцию, на которые указывает текущий объект делегата. |
| [operator=](./operator=/)(const Delegate\&) |  |
| [operator=](./operator=/)(Delegate\&&) | Оператор перемещения присваивания. Перехватывает владение сущностью, на которую указывает указанный делегат. |
| [operator==](./operator==/)(const Delegate\&) const | Сравнивает два объекта делегата, чтобы проверить, указывают ли они на одну и ту же сущность. |
## Примечания



```cpp
#include "system/delegate.h"
#include <iostream>

// Объявите делегат.
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // Присвойте переменной адрес функции PrintMessage.
  Message mes = Message(&PrintMessage);

  // Вызовите функцию.
  mes();

  return 0;
}
/*
This code example produces the following output:
Hello, world!
*/
```

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
