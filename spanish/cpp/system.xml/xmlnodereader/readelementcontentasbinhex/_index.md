---
title: "System::Xml::XmlNodeReader::ReadElementContentAsBinHex método"
linktitle: "ReadElementContentAsBinHex"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlNodeReader::ReadElementContentAsBinHex método. Lee el elemento y decodifica el contenido BinHex en C++."
type: docs
weight: 3500
url: /es/cpp/system.xml/xmlnodereader/readelementcontentasbinhex/
---
## XmlNodeReader::ReadElementContentAsBinHex method


Lee el elemento y decodifica el contenido en BinHex.

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
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
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
