---
title: "System::MulticastDelegate< ReturnType(ArgumentTypes...)> класс"
linktitle: "MulticastDelegate< ReturnType(ArgumentTypes...)>"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::MulticastDelegate< ReturnType(ArgumentTypes...)> класс. Представляет коллекцию делегатов. Этот тип должен быть выделен в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа в C++."
type: docs
weight: 4700
url: /ru/cpp/system/multicastdelegate_returntype(argumenttypes...)_/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> class


Представляет коллекцию делегатов. Этот тип должен быть выделен в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](../smartptr/) для управления объектами этого типа.

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


| Параметр | Описание |
| --- | --- |
| ReturnType | Тип возвращаемого значения вызываемых сущностей, на которые указывает каждый делегат в коллекции |
| ArgumentTypes | Список аргументов вызываемых сущностей, на которые указывает каждый делегат в коллекции |
## Методы

| Метод | Описание |
| --- | --- |
| [BeginInvoke](./begininvoke/)(ArgumentTypes..., const AsyncCallback\&, const CallbackArgumentType\&) | НЕ РЕАЛИЗОВАНО. |
| [connect](./connect/)(Callback) | Добавляет указанный делегат в коллекцию. |
| [connect](./connect/)(std::function\<R(Args...)>) | Добавляет указанный объект функции в коллекцию делегатов. Объект функции преобразуется в тип делегата [Callback](./callback/) перед добавлением в коллекцию. |
| [connect](./connect/)(MulticastDelegate\&) | Добавляет указанный объект MulticastDelegate в коллекцию делегатов. |
| [connect](./connect/)(MemberType ClassType::*, ClassType *) | Добавляет указанный нестатический метод указанного объекта в коллекцию делегатов. |
| [connect](./connect/)(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) | Добавляет указанный нестатический метод указанного объекта в коллекцию делегатов. |
| [disconnect](./disconnect/)(Callback) | Удаляет указанный делегат из коллекции делегатов. |
| [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | Удаляет указанный нестатический метод указанного объекта из коллекции делегатов. |
| [disconnect](./disconnect/)(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) | Удаляет указанный нестатический метод указанного объекта из коллекции делегатов. |
| [disconnect](./disconnect/)(MulticastDelegate\&) | Удаляет указанный объект MulticastDelegate из коллекции делегатов. |
| [disconnect_all_slots](./disconnect_all_slots/)() | Удаляет все делегаты из коллекции делегатов. |
| [empty](./empty/)() const | Определяет, пуста ли коллекция делегатов. |
| [EndInvoke](./endinvoke/)(const SharedPtr\<IAsyncResult\>\&) | НЕ РЕАЛИЗОВАНО. |
| [Equals](./equals/)(const MulticastDelegate\&) |  |
| [GetHashCode](./gethashcode/)() const |  |
| [GetType](./gettype/)() const |  |
| [invoke](./invoke/)(ArgumentTypes...) const | Вызывает все делегаты, находящиеся в текущий момент в коллекции делегатов. Делегаты вызываются в том же порядке, в котором они были добавлены в коллекцию. Метод блокируется, пока делегаты выполняются. |
| [IsNull](./isnull/)() const | Определяет, пуста ли коллекция делегатов. |
| [MulticastDelegate](./multicastdelegate/)() | Создаёт пустую коллекцию. |
| [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | Эквивалентно конструктору по умолчанию. |
| [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | Выполняет поверхностное копирование коллекции делегатов. |
| [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | Конструктор перемещения. |
| [MulticastDelegate](./multicastdelegate/)(Callback\&&) | Создаёт экземпляр и помещает указанный делегат в коллекцию делегатов. |
| [MulticastDelegate](./multicastdelegate/)(T) | Создаёт экземпляр и помещает указанное значение в коллекцию делегатов. |
| [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | Создаёт экземпляр и помещает указанное значение в коллекцию делегатов. |
| [operator!=](./operator!=/)(const std::nullptr_t\&) const | Определяет, не пуста ли коллекция делегатов. |
| [operator!=](./operator!=/)(const MulticastDelegate\&) const | Определяет, не равны ли два экземпляра MulticastDelegate — текущий объект и указанный объект. |
| [operator()](./operator()/)(ArgumentTypes...) const | Вызывает все делегаты, находящиеся в текущий момент в коллекции делегатов. Делегаты вызываются в том же порядке, в котором они были добавлены в коллекцию. Оператор блокируется, пока делегаты выполняются. |
| [operator+=](./operator+=/)(Callback) | Добавляет указанный делегат в коллекцию. |
| [operator-=](./operator-=/)(Callback) | Удаляет указанный делегат из коллекции делегатов. |
| [operator=](./operator=/)(const MulticastDelegate\&) | Назначает коллекцию делегатов, представленную указанным объектом, текущему объекту. В результате оба объекта указывают на одну и ту же коллекцию делегатов. |
| [operator=](./operator=/)(MulticastDelegate\&&) | Оператор перемещения присваивания. |
| [operator==](./operator==/)(const std::nullptr_t\&) const | Определяет, пуста ли коллекция делегатов. |
| [operator==](./operator==/)(const MulticastDelegate\&) const | Определяет, равны ли два экземпляра MulticastDelegate — текущий объект и указанный объект. |
| [remove_empty_callbacks](./remove_empty_callbacks/)() const | Очищает содержащиеся обратные вызовы, которые пусты (не вызывают ничего). |
| [ToString](./tostring/)() const |  |
| static [Type](./type/)() | Возвращает ссылку на объект [TypeInfo](../typeinfo/), представляющий информацию о типе класса MulticastDelegate. |
| [~MulticastDelegate](./~multicastdelegate/)() | Деструктор. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Callback](./callback/) | Тип делегатов, представленных классом MulticastDelegate. |
| [Function](./function/) | Тип функции, связанной с сигнатурой делегата. |

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
