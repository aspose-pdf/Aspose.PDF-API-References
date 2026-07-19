---
title: "Класс System::DynamicWeakPtr"
linktitle: "DynamicWeakPtr"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::DynamicWeakPtr. Класс умного указателя, который отслеживает режимы указателей шаблонных аргументов хранимого объекта и обновляет их после каждого присваивания. Этот тип является указателем для управления удалением другого объекта. Его следует размещать в стеке и передавать в функции либо по значению, либо по константной ссылке в C++."
type: docs
weight: 2300
url: /ru/cpp/system/dynamicweakptr/
---
## DynamicWeakPtr class


Класс умного указателя, который отслеживает режимы указателей шаблонных аргументов хранимого объекта и обновляет их после каждого присваивания. Этот тип является указателем для управления удалением другого объекта. Его следует размещать в стеке и передавать в функции либо по значению, либо по константной ссылке.

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```


| Параметр | Описание |
| --- | --- |
| Pointee | тип. |
| trunkMode | Режим самого умного указателя, shared или weak. |
| weakLeafs | Индексы шаблонных аргументов хранимого типа, которые должны быть установлены в режим weak pointer. |
## Nested classes

* Class [Reference](./reference/)
## Методы

| Метод | Описание |
| --- | --- |
| [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | Создаёт нулевой умный указатель. |
| [DynamicWeakPtr](./dynamicweakptr/)(Pointee_ *) | Создаёт умный указатель, указывающий на заданный объект. |
| [DynamicWeakPtr](./dynamicweakptr/)(const SmartPtr_\&) | Создаёт копию умного указателя. |
| [DynamicWeakPtr](./dynamicweakptr/)(const SmartPtr\<Q\>\&) | Создаёт копию умного указателя. |
| [DynamicWeakPtr](./dynamicweakptr/)(const DynamicWeakPtr_\&) | Создаёт копию умного указателя. |
| [DynamicWeakPtr](./dynamicweakptr/)(SmartPtr_\&&) | Создаёт умный указатель перемещением. |
| [operator=](./operator=/)(SmartPtr_\&&) | Перемещающее присваивание умного указателя. |
| [operator=](./operator=/)(const SmartPtr_\&) | Копирующее присваивание умного указателя. |
| [operator=](./operator=/)(const SmartPtr\<Q\>\&) | Копирующее присваивание умного указателя. |
| [operator=](./operator=/)(typename SmartPtr_::Pointee_ *) | Назначает умный указатель. |
| [operator=](./operator=/)(std::nullptr_t) | Устанавливает умный указатель в null. |
| [operator==](./operator==/)(std::nullptr_t) const | Проверяет, является ли умный указатель null. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [DynamicWeakPtr_](./dynamicweakptr_/) | Собственный псевдоним типа. |
| [Pointee_](./pointee_/) | Тип, на который указывает. |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) псевдоним базового класса. |

## См. также

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
