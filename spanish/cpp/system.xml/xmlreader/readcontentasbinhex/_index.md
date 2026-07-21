---
title: "System::Xml::XmlReader::ReadContentAsBinHex método"
linktitle: "ReadContentAsBinHex"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlReader::ReadContentAsBinHex método. Lee el contenido y devuelve los bytes binarios decodificados en BinHex en C++."
type: docs
weight: 4100
url: /es/cpp/system.xml/xmlreader/readcontentasbinhex/
---
## XmlReader::ReadContentAsBinHex method


Lee el contenido y devuelve los bytes binarios decodificados en **BinHex**.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
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
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
