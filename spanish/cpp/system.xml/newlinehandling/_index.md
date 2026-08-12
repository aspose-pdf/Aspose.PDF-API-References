---
title: "Enum System::Xml::NewLineHandling"
linktitle: "NewLineHandling"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Enum System::Xml::NewLineHandling. Especifica cómo manejar los saltos de línea en C++."
type: docs
weight: 5200
url: /es/cpp/system.xml/newlinehandling/
---
## NewLineHandling enum


Especifica cómo manejar los saltos de línea.

```cpp
enum class NewLineHandling
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Replace | 0 | Los caracteres de nueva línea se reemplazan para coincidir con el carácter especificado en el valor de [XmlWriterSettings::set_NewLineChars](../xmlwritersettings/set_newlinechars/). |
| Entitize | 1 | Los caracteres de nueva línea se convierten en entidades. Esta configuración conserva todos los caracteres cuando la salida es leída por un [XmlReader](../xmlreader/) que normaliza. |
| Ninguno | 2 | Los caracteres de nueva línea permanecen sin cambios. La salida es la misma que la entrada. |

## Ver también

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
