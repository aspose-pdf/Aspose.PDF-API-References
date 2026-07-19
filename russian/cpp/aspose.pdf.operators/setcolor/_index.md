---
title: "Aspose::Pdf::Operators::SetColor класс"
linktitle: "SetColor"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Operators::SetColor класс. Представляет класс для оператора sc (установить цвет для операций без обводки) в C++."
type: docs
weight: 5200
url: /ru/cpp/aspose.pdf.operators/setcolor/
---
## SetColor class


Представляет класс для оператора sc (устанавливает цвет для операций без обводки).

```cpp
class SetColor : public Aspose::Pdf::Operators::BasicSetColorOperator
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) override | Принимает объект посетителя для обработки оператора. |
| [get_B](./get_b/)() | Получает синий компонент. |
| [get_C](./get_c/)() | Получает циановый компонент. |
| [get_G](./get_g/)() | Получает зеленый компонент. |
| [get_K](./get_k/)() | Получает черный компонент. |
| [get_M](./get_m/)() | Получает пурпурный компонент. |
| [get_R](./get_r/)() | Получает красный компонент. |
| [get_Y](./get_y/)() | Получает желтый компонент. |
| [getColor](./getcolor/)() override | Возвращает цвет, указанный оператором. |
| [set_B](./set_b/)(double) | Устанавливает синий компонент. |
| [set_C](./set_c/)(double) | Устанавливает циановый компонент. |
| [set_G](./set_g/)(double) | Устанавливает зеленый компонент. |
| [set_K](./set_k/)(double) | Устанавливает черный компонент. |
| [set_M](./set_m/)(double) | Устанавливает пурпурный компонент. |
| [set_R](./set_r/)(double) | Устанавливает красный компонент. |
| [set_Y](./set_y/)(double) | Устанавливает желтый компонент. |
| [SetColor](./setcolor/)() | Инициализирует оператор. |
| [SetColor](./setcolor/)(double) | Установить цвет для операторов обводки для пространств цветов DeviceGray, CalGray и Indexed. |
| [SetColor](./setcolor/)(double, double, double) | Установить цвет для оператора обводки для пространств цветов DeviceRGB, CalRGB и Lab. |
| [SetColor](./setcolor/)(double, double, double, double) | Установить цвет для оператора без обводки в цветовом пространстве CMYK. |
| [SetColor](./setcolor/)(const System::ArrayPtr\<double\>\&) | Конструктор, позволяющий задавать компоненты цвета. |
| [ToString](./tostring/)() const override | Возвращает строковое представление цвета. |
## См. также

* Class [BasicSetColorOperator](../basicsetcoloroperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
