---
title: "Aspose::Pdf::Operators::SetRGBColor class"
linktitle: "SetRGBColor"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Operators::SetRGBColor class. Clase que representa el operador rg (establecer color RGB para operadores que no trazan) en C++."
type: docs
weight: 6800
url: /es/cpp/aspose.pdf.operators/setrgbcolor/
---
## SetRGBColor class


Clase que representa el operador rg (establece el color RGB para operadores sin trazo).

```cpp
class SetRGBColor : public Aspose::Pdf::Operators::SetColorOperator
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) override | Acepta un objeto visitante para procesar el operador. |
| [get_B](./get_b/)() const | Obtiene el componente azul. |
| [get_G](./get_g/)() const | Obtiene el componente verde. |
| [get_R](./get_r/)() const | Obtiene el componente rojo. |
| [getColor](./getcolor/)() override | Devuelve el color especificado por el operador. |
| [set_B](./set_b/)(double) | Establece el componente azul. |
| [set_G](./set_g/)(double) | Establece el componente verde. |
| [set_R](./set_r/)(double) | Establece el componente rojo. |
| [SetRGBColor](./setrgbcolor/)(double, double, double) | Inicializa el operador. |
| [SetRGBColor](./setrgbcolor/)(System::Drawing::Color) | Inicializa el operador con color. |
| [ToString](./tostring/)() const override | Devuelve la representación textual del operador. |
## Ver también

* Class [SetColorOperator](../setcoloroperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
