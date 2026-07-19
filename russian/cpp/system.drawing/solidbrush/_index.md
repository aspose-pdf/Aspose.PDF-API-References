---
title: "System::Drawing::SolidBrush класс"
linktitle: "SolidBrush"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::SolidBrush класс. Представляет кисть одного цвета. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2400
url: /ru/cpp/system.drawing/solidbrush/
---
## SolidBrush class


Представляет кисть одного цвета. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class SolidBrush : public System::Drawing::Brush
```

## Методы

| Метод | Описание |
| --- | --- |
| [Clone](./clone/)() override | Создаёт копию текущего объекта. |
| [get_Color](./get_color/)() const | Возвращает цвет этой кисти. |
| [set_Color](./set_color/)(Color) | Устанавливает цвет этой кисти. |
| [SolidBrush](./solidbrush/)(const Color\&) | Создаёт новый объект [SolidBrush](./) и инициализирует его указанным цветом. |
## См. также

* Class [Brush](../brush/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
