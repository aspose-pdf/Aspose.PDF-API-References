---
title: "System::Xml::ReadState enum"
linktitle: "ReadState"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::ReadState enum. Especifica el estado del lector en C++."
type: docs
weight: 5300
url: /es/cpp/system.xml/readstate/
---
## ReadState enum


Especifica el estado del lector.

```cpp
enum class ReadState
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Initial | 0 | El método [XmlReader::Read](../xmlreader/read/) no ha sido llamado. |
| Interactive | 1 | El método [XmlReader::Read](../xmlreader/read/) ha sido llamado. Se pueden llamar métodos adicionales en el lector. |
| Error | 2 | Ocurrió un error que impide que la operación de lectura continúe. |
| EndOfFile | 3 | Se ha alcanzado el final del archivo con éxito. |
| Closed | 4 | El método [XmlReader::Close](../xmlreader/close/) ha sido llamado. |

## Ver también

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
