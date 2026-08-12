---
title: "System::Xml::DtdProcessing enumeración"
linktitle: "DtdProcessing"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::DtdProcessing enumeración. Especifica las opciones para procesar DTDs. La enumeración DtdProcessing es utilizada por la clase XmlReaderSettings en C++."
type: docs
weight: 4700
url: /es/cpp/system.xml/dtdprocessing/
---
## DtdProcessing enum


Especifica las opciones para procesar DTDs. La enumeración [DtdProcessing](./) es utilizada por la clase [XmlReaderSettings](../xmlreadersettings/).

```cpp
enum class DtdProcessing
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Prohibit | 0 | Especifica que cuando se encuentra un DTD, se lanza una [XmlException](../xmlexception/) con un mensaje que indica que los DTD están prohibidos. Este es el comportamiento predeterminado. |
| Ignorar | 1 | Hace que el elemento DOCTYPE sea ignorado. No se procesa DTD, y el DTD/DOCTYPE se pierde en la salida. |
| Analizar | 2 | Utilizado para analizar DTDs. |

## Ver también

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
