---
title: "System::Drawing::Drawing2D::Blend class"
linktitle: "Blend"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Drawing2D::Blend class. Представляет шаблон смешивания для объекта LinearGradientBrush. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 200
url: /ru/cpp/system.drawing.drawing2d/blend/
---
## Blend class


Представляет шаблон смешивания для объекта [LinearGradientBrush](../lineargradientbrush/). Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class Blend : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Blend](./blend/)() | Создаёт новый экземпляр класса [Blend](./). |
| [Blend](./blend/)(int) | Создаёт новый экземпляр класса [Blend](./). |
| [get_Factors](./get_factors/)() const | Возвращает массив коэффициентов смешивания градиента. |
| [get_Positions](./get_positions/)() const | Возвращает массив позиций смешивания градиента. |
| [set_Factors](./set_factors/)(const ArrayPtr\<float\>\&) | Устанавливает массив коэффициентов смешивания градиента. |
| [set_Positions](./set_positions/)(const ArrayPtr\<float\>\&) | Устанавливает массив позиций смешивания градиента. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
