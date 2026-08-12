---
title: "Aspose::Pdf::Operators::SetCMYKColorStroke class"
linktitle: "SetCMYKColorStroke"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Operators::SetCMYKColorStroke class. Clase que representa el operador K (establecer color CMYK para operaciones de trazo) en C++."
type: docs
weight: 5100
url: /es/cpp/aspose.pdf.operators/setcmykcolorstroke/
---
## SetCMYKColorStroke class


Clase que representa el operador K (establece el color CMYK para operaciones con trazo).

```cpp
class SetCMYKColorStroke : public Aspose::Pdf::Operators::SetColorOperator
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) override | Acepta un objeto visitante para procesar el operador. |
| [get_C](./get_c/)() const | Obtiene el componente cian. |
| [get_K](./get_k/)() const | Obtiene el componente negro. |
| [get_M](./get_m/)() const | Obtiene el componente magenta. |
| [get_Y](./get_y/)() const | Obtiene el componente amarillo. |
| [getColor](./getcolor/)() override | Devuelve el color RGB. |
| [set_C](./set_c/)(double) | Establece el componente cian. |
| [set_K](./set_k/)(double) | Establece el componente negro. |
| [set_M](./set_m/)(double) | Establece el componente magenta. |
| [set_Y](./set_y/)(double) | Establece el componente amarillo. |
| [SetCMYKColorStroke](./setcmykcolorstroke/)(double, double, double, double) | Inicializa el operador. |
## Ver también

* Class [SetColorOperator](../setcoloroperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
