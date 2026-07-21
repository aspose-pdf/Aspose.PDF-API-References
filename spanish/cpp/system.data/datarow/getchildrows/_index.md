---
title: "Método System::Data::DataRow::GetChildRows"
linktitle: "GetChildRows"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Data::DataRow::GetChildRows. Obtiene filas que se consideran hijas mediante la relación especificada en C++."
type: docs
weight: 200
url: /es/cpp/system.data/datarow/getchildrows/
---
## DataRow::GetChildRows method


Obtiene las filas que se consideran hijas a través de la relación especificada.

```cpp
System::ArrayPtr<System::SharedPtr<System::Data::DataRow>> System::Data::DataRow::GetChildRows(const System::SharedPtr<System::Data::DataRelation> &relation)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| relation | const System::SharedPtr\<System::Data::DataRelation\>\& | Objeto de relación para especificar la relación fila padre - fila hija. |

### ReturnValue

[Array](../../../system/array/) of child rows retreived.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DataRow](../)
* Class [DataRelation](../../datarelation/)
* Class [DataRow](../)
* Namespace [System::Data](../../)
* Library [Aspose.PDF for C++](../../../)
