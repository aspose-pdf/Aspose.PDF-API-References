---
title: "System::Xml::XmlTextReader::ReadElementContentAsBase64 método"
linktitle: "ReadElementContentAsBase64"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlTextReader::ReadElementContentAsBase64 método. Lee el elemento y decodifica el contenido Base64 en C++."
type: docs
weight: 4900
url: /es/cpp/system.xml/xmltextreader/readelementcontentasbase64/
---
## XmlTextReader::ReadElementContentAsBase64 method


Lee el elemento y decodifica el contenido en Base64.

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | ArrayPtr\<uint8_t\> | El búfer en el que copiar el texto resultante. Este valor no puede ser **nullptr**. |
| índice | int32_t | El desplazamiento dentro del búfer donde comenzar a copiar el resultado. |
| count | int32_t | El número máximo de bytes a copiar en el búfer. El número real de bytes copiados se devuelve desde este método. |

### ReturnValue

El número de bytes escritos en el búfer.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
