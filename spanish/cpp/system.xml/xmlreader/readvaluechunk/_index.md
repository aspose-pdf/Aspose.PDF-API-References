---
title: "System::Xml::XmlReader::ReadValueChunk método"
linktitle: "ReadValueChunk"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlReader::ReadValueChunk método. Lee grandes flujos de texto incrustados en un documento XML en C++."
type: docs
weight: 7400
url: /es/cpp/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk method


Lee grandes flujos de texto incrustados en un documento XML.

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | ArrayPtr\<char16_t\> | La matriz de caracteres que sirve como búfer al que se escribe el contenido de texto. Este valor no puede ser **nullptr**. |
| index | int32_t | El desplazamiento dentro del búfer donde [XmlReader](../) puede comenzar a copiar los resultados. |
| count | int32_t | El número máximo de caracteres a copiar en el búfer. El número real de caracteres copiados se devuelve desde este método. |

### ReturnValue

El número de caracteres leídos en el búfer. Se devuelve el valor cero cuando no hay más contenido de texto.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
