---
title: "Aspose::Pdf::Operators::SetTextMatrix clase"
linktitle: "SetTextMatrix"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Operators::SetTextMatrix clase. Clase que representa el operador Tm (establecer matriz de texto) en C++."
type: docs
weight: 7200
url: /es/cpp/aspose.pdf.operators/settextmatrix/
---
## SetTextMatrix class


Clase que representa el operador Tm (establecer la matriz de texto).

```cpp
class SetTextMatrix : public Aspose::Pdf::Operators::TextPlaceOperator
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) override | Acepta un objeto visitante para procesar el operador. |
| [get_Matrix](./get_matrix/)() const | [Matrix](../../aspose.pdf/matrix/) argumento del operador. |
| [set_Matrix](./set_matrix/)(const System::SharedPtr\<Aspose::Pdf::Matrix\>\&) | [Matrix](../../aspose.pdf/matrix/) argumento del operador. |
| [SetTextMatrix](./settextmatrix/)(double, double, double, double, double, double) | Inicializa el operador. |
| [SetTextMatrix](./settextmatrix/)(const System::SharedPtr\<Aspose::Pdf::Matrix\>\&) | Inicializa el operador mediante una matriz. |
| [ToString](./tostring/)() const override | Devuelve la representación de texto del operador. |
## Ver también

* Class [TextPlaceOperator](../textplaceoperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
