---
title: "Aspose::Pdf::Operators::SetCMYKColor class"
linktitle: "SetCMYKColor"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Operators::SetCMYKColor class. Класс, представляющий оператор k (установка CMYK‑цвета для операций без обводки) в C++."
type: docs
weight: 5000
url: /ru/cpp/aspose.pdf.operators/setcmykcolor/
---
## SetCMYKColor class


Класс, представляющий оператор k (устанавливает CMYK‑цвет для операций без обводки).

```cpp
class SetCMYKColor : public Aspose::Pdf::Operators::SetColorOperator
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) override | Принимает объект посетителя для обработки оператора. |
| [get_C](./get_c/)() const | Получает циановый компонент. |
| [get_K](./get_k/)() const | Получает черный компонент. |
| [get_M](./get_m/)() const | Получает пурпурный компонент. |
| [get_Y](./get_y/)() const | Получает желтый компонент. |
| [getColor](./getcolor/)() override | Возвращает цвет. |
| [set_C](./set_c/)(double) | Устанавливает циановый компонент. |
| [set_K](./set_k/)(double) | Устанавливает черный компонент. |
| [set_M](./set_m/)(double) | Устанавливает пурпурный компонент. |
| [set_Y](./set_y/)(double) | Устанавливает желтый компонент. |
| [SetCMYKColor](./setcmykcolor/)(double, double, double, double) | Инициализирует оператор. |
## См. также

* Class [SetColorOperator](../setcoloroperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
