---
title: "Clase Aspose::Pdf::Operator"
linktitle: "Operador"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Operator. Clase abstracta que representa un operador en C++."
type: docs
weight: 12000
url: /es/cpp/aspose.pdf/operator/
---
## Operator class


Clase abstracta que representa al operador.

```cpp
class Operator : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) | Acepta el visitante [IOperatorSelector](../ioperatorselector/) que proporciona el procesamiento de operadores. |
| [get_Index](./get_index/)() | Índice de [Operator](./) en la lista de operadores de la página. |
| static [IsTextShowOperator](./istextshowoperator/)(const System::SharedPtr\<Operator\>\&) | Determina si el operador es el operador responsable de la salida de texto (Tj, TJ, etc) |
| [set_Index](./set_index/)(int32_t) | Índice de [Operator](./) en la lista de operadores de la página. |
| [ToString](./tostring/)() const override | Devuelve el texto del operador y sus parámetros. |
| [ValueEquals](./valueequals/)(const System::SharedPtr\<Operator\>\&) | Compara esta instancia con el objeto proporcionado. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
