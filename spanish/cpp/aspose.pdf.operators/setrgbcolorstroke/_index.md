---
title: "Clase Aspose::Pdf::Operators::SetRGBColorStroke"
linktitle: "SetRGBColorStroke"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Operators::SetRGBColorStroke. Clase que representa el operador RG (establece el color RGB para los operadores de trazo) en C++."
type: docs
weight: 6900
url: /es/cpp/aspose.pdf.operators/setrgbcolorstroke/
---
## SetRGBColorStroke class


Clase que representa el operador RG (establece el color RGB para operadores con trazo).

```cpp
class SetRGBColorStroke : public Aspose::Pdf::Operators::SetColorOperator
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
| [SetRGBColorStroke](./setrgbcolorstroke/)(double, double, double) | Inicializa el operador. |
| [SetRGBColorStroke](./setrgbcolorstroke/)(System::Drawing::Color) | Inicializa el operador con color. |
| [ToString](./tostring/)() const override | Devuelve la representación de texto del operador. |
## Ver también

* Class [SetColorOperator](../setcoloroperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
