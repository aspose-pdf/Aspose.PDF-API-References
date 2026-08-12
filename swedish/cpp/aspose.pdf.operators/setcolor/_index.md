---
title: "Aspose::Pdf::Operators::SetColor-klass"
linktitle: "SetColor"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Operators::SetColor-klass. Representerar klass för sc-operatorn (sätt färg för icke‑kontureringsoperationer) i C++."
type: docs
weight: 5200
url: /sv/cpp/aspose.pdf.operators/setcolor/
---
## SetColor class


Representerar klass för sc-operatorn (ställer in färg för icke‑strokande operationer).

```cpp
class SetColor : public Aspose::Pdf::Operators::BasicSetColorOperator
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
| [getColor](./getcolor/)() override | Returnerar färg som specificerats av operatorn. |
| [set_B](./set_b/)(double) | Ställer in den blå komponenten. |
| [set_C](./set_c/)(double) | Ställer in den cyan‑komponenten. |
| [set_G](./set_g/)(double) | Ställer in den gröna komponenten. |
| [set_K](./set_k/)(double) | Ställer in den svarta komponenten. |
| [set_M](./set_m/)(double) | Ställer in den magenta komponenten. |
| [set_R](./set_r/)(double) | Ställer in den röda komponenten. |
| [set_Y](./set_y/)(double) | Ställer in den gula komponenten. |
| [SetColor](./setcolor/)() | Initierar operatorn. |
| [SetColor](./setcolor/)(double) | Ställ färg för streckningsoperatorer för färgrymden DeviceGray, CalGray och Indexed. |
| [SetColor](./setcolor/)(double, double, double) | Ställ färg för streckningsoperator för färgrymden DeviceRGB, CalRGB och Lab. |
| [SetColor](./setcolor/)(double, double, double, double) | Sätt färg för icke‑kontureringsoperator för CMYK-färgrymden. |
| [SetColor](./setcolor/)(const System::ArrayPtr\<double\>\&) | Konstruktor som tillåter att specificera färgkomponenter. |
| [ToString](./tostring/)() const override | Returnerar färgens strängrepresentation. |
## Se även

* Class [BasicSetColorOperator](../basicsetcoloroperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
