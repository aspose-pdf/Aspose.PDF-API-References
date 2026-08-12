---
title: "Aspose::Pdf::Operators::SetColorStroke class"
linktitle: "SetColorStroke"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Operators::SetColorStroke class. Clase que representa el operador SC (establecer color para los operadores de trazo) en C++."
type: docs
weight: 5700
url: /es/cpp/aspose.pdf.operators/setcolorstroke/
---
## SetColorStroke class


Clase que representa el operador SC establece el color para operadores de color con trazo.

```cpp
class SetColorStroke : public Aspose::Pdf::Operators::BasicSetColorOperator
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) override | Acepta un objeto visitante para procesar el operador. |
| [get_B](./get_b/)() | Obtiene el componente azul. |
| [get_C](./get_c/)() | Obtiene el componente cian. |
| [get_G](./get_g/)() | Obtiene el componente verde. |
| [get_K](./get_k/)() | Obtiene el componente negro. |
| [get_M](./get_m/)() | Obtiene el componente magenta. |
| [get_R](./get_r/)() | Obtiene el componente rojo. |
| [get_Y](./get_y/)() | Obtiene el componente amarillo. |
| [getColor](./getcolor/)() override | Devuelve el color especificado por el operador. |
| [set_B](./set_b/)(double) | Establece el componente azul. |
| [set_C](./set_c/)(double) | Establece el componente cian. |
| [set_G](./set_g/)(double) | Establece el componente verde. |
| [set_K](./set_k/)(double) | Establece el componente negro. |
| [set_M](./set_m/)(double) | Establece el componente magenta. |
| [set_R](./set_r/)(double) | Establece el componente rojo. |
| [set_Y](./set_y/)(double) | Establece el componente amarillo. |
| [SetColorStroke](./setcolorstroke/)() | Inicializa el operador. |
| [SetColorStroke](./setcolorstroke/)(double) | Establece el color para los operadores de trazo para los espacios de color DeviceGray, CalGray e Indexed. |
| [SetColorStroke](./setcolorstroke/)(double, double, double) | Establece el color para el operador de trazo para los espacios de color DeviceRGB, CalRGB y Lab. |
| [SetColorStroke](./setcolorstroke/)(const System::ArrayPtr\<double\>\&) | Constructor que permite establecer los componentes de color. |
| [SetColorStroke](./setcolorstroke/)(double, double, double, double) | Establece el color para el operador de trazo para el espacio de color CMYK. |
## Ver también

* Class [BasicSetColorOperator](../basicsetcoloroperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
