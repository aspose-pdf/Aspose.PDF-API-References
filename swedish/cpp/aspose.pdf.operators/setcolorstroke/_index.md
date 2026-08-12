---
title: "Aspose::Pdf::Operators::SetColorStroke class"
linktitle: "SetColorStroke"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Operators::SetColorStroke class. Klass som representerar SC-operatorn som sätter färg för streckningsfärgsoperatorer i C++."
type: docs
weight: 5700
url: /sv/cpp/aspose.pdf.operators/setcolorstroke/
---
## SetColorStroke class


Klass som representerar SC-operatorn (ställer in färg för strokande färgoperatorer).

```cpp
class SetColorStroke : public Aspose::Pdf::Operators::BasicSetColorOperator
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) override | Accepterar besöksobjekt för att bearbeta operatorn. |
| [get_B](./get_b/)() | Hämtar den blå komponenten. |
| [get_C](./get_c/)() | Hämtar den cyan-komponenten. |
| [get_G](./get_g/)() | Hämtar den gröna komponenten. |
| [get_K](./get_k/)() | Hämtar den svarta komponenten. |
| [get_M](./get_m/)() | Hämtar den magenta komponenten. |
| [get_R](./get_r/)() | Hämtar den röda komponenten. |
| [get_Y](./get_y/)() | Hämtar den gula komponenten. |
| [getColor](./getcolor/)() override | Returnerar färg som specificeras av operatorn. |
| [set_B](./set_b/)(double) | Ställer in den blå komponenten. |
| [set_C](./set_c/)(double) | Ställer in den cyan‑komponenten. |
| [set_G](./set_g/)(double) | Ställer in den gröna komponenten. |
| [set_K](./set_k/)(double) | Ställer in den svarta komponenten. |
| [set_M](./set_m/)(double) | Ställer in den magenta komponenten. |
| [set_R](./set_r/)(double) | Ställer in den röda komponenten. |
| [set_Y](./set_y/)(double) | Ställer in den gula komponenten. |
| [SetColorStroke](./setcolorstroke/)() | Initierar operatorn. |
| [SetColorStroke](./setcolorstroke/)(double) | Ställ färg för streckningsoperatorer för färgrymden DeviceGray, CalGray och Indexed. |
| [SetColorStroke](./setcolorstroke/)(double, double, double) | Ställ färg för streckningsoperator för färgrymden DeviceRGB, CalRGB och Lab. |
| [SetColorStroke](./setcolorstroke/)(const System::ArrayPtr\<double\>\&) | Konstruktor som tillåter att sätta färgkomponenter. |
| [SetColorStroke](./setcolorstroke/)(double, double, double, double) | Ställ färg för streckningsoperator för CMYK-färgrymden. |
## Se även

* Class [BasicSetColorOperator](../basicsetcoloroperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
