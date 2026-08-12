---
title: "System::Xml::WriteState enum"
linktitle: "WriteState"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::WriteState enum. Especifica el estado del XmlWriter en C++."
type: docs
weight: 5700
url: /es/cpp/system.xml/writestate/
---
## WriteState enum


Especifica el estado del [XmlWriter](../xmlwriter/).

```cpp
enum class WriteState
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Start | 0 | Indica que el método XmlWriter::Write aún no ha sido llamado. |
| Prólogo | 1 | Indica que se está escribiendo el prólogo. |
| Elemento | 2 | Indica que se está escribiendo una etiqueta de inicio de elemento. |
| Atributo | 3 | Indica que se está escribiendo un valor de atributo. |
| Contenido | 4 | Indica que se está escribiendo el contenido del elemento. |
| Closed | 5 | Indica que se ha llamado al método [XmlWriter::Close](../xmlwriter/close/). |
| Error | 6 | Se ha lanzado una excepción, lo que ha dejado al [XmlWriter](../xmlwriter/) en un estado no válido. Puede llamar al método [XmlWriter::Close](../xmlwriter/close/) para colocar al [XmlWriter](../xmlwriter/) en el estado [WriteState::Closed](./). Cualquier otra llamada a un método del [XmlWriter](../xmlwriter/) produce una InvalidOperationException. |

## Ver también

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
