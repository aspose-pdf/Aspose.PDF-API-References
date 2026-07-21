---
title: "Clase Aspose::Pdf::Operators::SetDash"
linktitle: "SetDash"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Operators::SetDash. Clase que representa el operador d (establecer patrón de guiones de línea) en C++."
type: docs
weight: 5800
url: /es/cpp/aspose.pdf.operators/setdash/
---
## SetDash class


Clase que representa el operador d (establece el patrón de guiones de línea).

```cpp
class SetDash : public Aspose::Pdf::Operator
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) override | Acepta un objeto visitante para procesar el operador. |
| [get_Pattern](./get_pattern/)() const | Patrón de guiones. Los elementos de la matriz deberán ser números que especifican las longitudes de los guiones y espacios alternados. En caso de una matriz de un solo elemento, las longitudes de guiones y espacios son iguales. |
| [get_Phase](./get_phase/)() const | Fase de guiones. Antes de comenzar a trazar una ruta, la matriz de guiones deberá recorrerse, sumando las longitudes de los guiones y los espacios. Cuando la longitud acumulada sea igual al valor especificado por la fase de guiones, comenzará el trazado de la ruta y la matriz de guiones se usará de forma cíclica a partir de ese punto. |
| [set_Pattern](./set_pattern/)(const System::ArrayPtr\<int32_t\>\&) | Patrón de guiones. Los elementos de la matriz deberán ser números que especifican las longitudes de los guiones y espacios alternados. En caso de una matriz de un solo elemento, las longitudes de guiones y espacios son iguales. |
| [set_Phase](./set_phase/)(int32_t) | Fase de guiones. Antes de comenzar a trazar una ruta, la matriz de guiones deberá recorrerse, sumando las longitudes de los guiones y los espacios. Cuando la longitud acumulada sea igual al valor especificado por la fase de guiones, comenzará el trazado de la ruta y la matriz de guiones se usará de forma cíclica a partir de ese punto. |
| [SetDash](./setdash/)(const System::ArrayPtr\<int32_t\>\&, int32_t) | Crea el operador de establecimiento de patrón de guiones. |
| [ToString](./tostring/)() const override | Obtiene la representación en cadena del operador. |
## Ver también

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
