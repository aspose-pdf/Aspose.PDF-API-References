---
title: "Класс System::ComponentModel::PropertyChangedEventArgs"
linktitle: "PropertyChangedEventArgs"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::ComponentModel::PropertyChangedEventArgs. Аргументы события PropertyChanged. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1200
url: /ru/cpp/system.componentmodel/propertychangedeventargs/
---
## PropertyChangedEventArgs class


Аргументы события PropertyChanged. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class PropertyChangedEventArgs : public System::EventArgs
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [get_PropertyName](./get_propertyname/)() | Информация RTTI. |
| [PropertyChangedEventArgs](./propertychangedeventargs/)(const String\&) | Инициализирует аргументы события PropertyChanged. |
## Поля

| Поле | Описание |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | Статический член, представляющий "пустой" [EventArgs](../../system/eventargs/) shared pointer (null-pointer). |
## См. также

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
