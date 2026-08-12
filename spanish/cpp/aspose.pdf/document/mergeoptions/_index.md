---
title: "Clase Aspose::Pdf::Document::MergeOptions"
linktitle: "MergeOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Document::MergeOptions. Representa las opciones para los métodos Merge en C++."
type: docs
weight: 12700
url: /es/cpp/aspose.pdf/document/mergeoptions/
---
## MergeOptions class


Representa las opciones para los métodos Merge.

```cpp
class MergeOptions : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_ConcatenationPacketSize](./get_concatenationpacketsize/)() const | Número de documentos concatenados antes de que se realice una nueva actualización incremental durante la concatenación cuando UseDiskBuffer está configurado en true. El valor predeterminado es 4. |
| [get_IsNeedPageTreeBalance](./get_isneedpagetreebalance/)() const | Obtiene y establece el requisito para el equilibrio del árbol de páginas. El árbol de páginas completo en el documento resultante será reequilibrado. Crea un árbol de páginas equilibrado para acelerar el acceso a las páginas. |
| [get_MaximumNodesInLevel](./get_maximumnodesinlevel/)() const | Obtiene y establece el número máximo de nodos en el nivel del árbol de páginas. El valor predeterminado es 10. |
| [get_UseDiskBuffer](./get_usediskbuffer/)() const | Si se usa esta opción, el documento de destino se guardará en disco periódicamente y la concatenación posterior se aplicará a él como actualizaciones incrementales. El valor predeterminado es **false**. |
| [MergeOptions](./mergeoptions/)() |  |
| [set_ConcatenationPacketSize](./set_concatenationpacketsize/)(int32_t) | Número de documentos concatenados antes de que se realice una nueva actualización incremental durante la concatenación cuando UseDiskBuffer está configurado en true. El valor predeterminado es 4. |
| [set_IsNeedPageTreeBalance](./set_isneedpagetreebalance/)(bool) | Obtiene y establece el requisito para el equilibrio del árbol de páginas. El árbol de páginas completo en el documento resultante será reequilibrado. Crea un árbol de páginas equilibrado para acelerar el acceso a las páginas. |
| [set_MaximumNodesInLevel](./set_maximumnodesinlevel/)(uint8_t) | Obtiene y establece el número máximo de nodos en el nivel del árbol de páginas. El valor predeterminado es 10. |
| [set_UseDiskBuffer](./set_usediskbuffer/)(bool) | Si se usa esta opción, el documento de destino se guardará en disco periódicamente y la concatenación posterior se aplicará a él como actualizaciones incrementales. El valor predeterminado es **false**. |
## Ver también

* Class [Object](../../../system/object/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
