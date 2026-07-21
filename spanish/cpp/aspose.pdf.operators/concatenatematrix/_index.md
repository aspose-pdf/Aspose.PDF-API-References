---
title: "Clase Aspose::Pdf::Operators::ConcatenateMatrix"
linktitle: "ConcatenateMatrix"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Operators::ConcatenateMatrix. Clase que representa el operador cm (concatenar una matriz a la matriz de transformación actual) en C++."
type: docs
weight: 1400
url: /es/cpp/aspose.pdf.operators/concatenatematrix/
---
## ConcatenateMatrix class


Clase que representa el operador cm (concatenar matriz a la matriz de transformación actual).

```cpp
class ConcatenateMatrix : public Aspose::Pdf::Operator
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) override | Acepta un objeto visitante para procesar el operador. |
| [ConcatenateMatrix](./concatenatematrix/)(double, double, double, double, double, double) | Inicializa el operador. |
| [ConcatenateMatrix](./concatenatematrix/)(const System::SharedPtr\<Aspose::Pdf::Matrix\>\&) | Inicializa el operador mediante una matriz. |
| [get_Matrix](./get_matrix/)() const | [Matrix](../../aspose.pdf/matrix/) argumento del operador. |
| [set_Matrix](./set_matrix/)(const System::SharedPtr\<Aspose::Pdf::Matrix\>\&) | [Matrix](../../aspose.pdf/matrix/) argumento del operador. |
| [ToString](./tostring/)() const override | Devuelve la representación de texto del operador. |
## Ver también

* Class [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
