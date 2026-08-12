---
title: "Класс System::Reflection::MethodBase"
linktitle: "MethodBase"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Reflection::MethodBase. Базовая информация о методе. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 800
url: /ru/cpp/system.reflection/methodbase/
---
## MethodBase class


Базовая информация о методе. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class MethodBase : public System::Reflection::MemberInfo
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_MemberType](./get_membertype/)() const override | Указывает тип члена — метод, конструктор, событие и т.д. |
| static [GetCurrentMethod](./getcurrentmethod/)(const String\&) | Этот метод позволяет получить имя текущего метода. Переводчик автоматически подставляет ASPOSE_CURRENT_FUNCTION в качестве параметра автоматически. |
| [MEMBER_FUNCTION_MAKE_OBJECT](./member_function_make_object/)(MethodBase, CODEPORTING_ARGS(const String\&full_name), CODEPORTING_ARGS(full_name)) |  |
| [MethodBase](./methodbase/)() | Инициализирует новый экземпляр класса [MethodBase](./). |
## См. также

* Class [MemberInfo](../memberinfo/)
* Namespace [System::Reflection](../)
* Library [Aspose.PDF for C++](../../)
