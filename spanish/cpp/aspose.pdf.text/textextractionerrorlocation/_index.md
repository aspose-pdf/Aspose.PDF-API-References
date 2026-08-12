---
title: "Clase Aspose::Pdf::Text::TextExtractionErrorLocation"
linktitle: "TextExtractionErrorLocation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Text::TextExtractionErrorLocation. Representa la ubicación en el documento PDF donde se ha producido un error de extracción de texto en C++."
type: docs
weight: 4000
url: /es/cpp/aspose.pdf.text/textextractionerrorlocation/
---
## TextExtractionErrorLocation class


Representa la ubicación en el documento PDF donde se ha producido el error de extracción de texto.

```cpp
class TextExtractionErrorLocation : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_FontUsedKey](./get_fontusedkey/)() const | Clave (nombre) del objeto PDF [Font](../font/) que se utiliza para mostrar el operador que causa el error de extracción de texto. |
| [get_FormKey](./get_formkey/)() const | Clave (nombre) del PDF Form XObject en el que se ha localizado el error de extracción de texto del flujo de contenido. No está vacío si ObjectType == 'xForm'. |
| [get_ObjectType](./get_objecttype/)() const | Tipo del objeto PDF ([Page](../../aspose.pdf/page/) o xForm) en el que se ha localizado el error de extracción de texto del flujo de contenido. |
| [get_OperatorIndex](./get_operatorindex/)() const | Índice del operador que muestra texto en el flujo de contenido (colección de operadores) que causa el error de extracción de texto. |
| [get_OperatorString](./get_operatorstring/)() const | Operador de [Text](../) que muestra texto y causa el error de extracción de texto. |
| [get_PageNumber](./get_pagenumber/)() const | Número de la página del documento donde se ha localizado el error de extracción de texto. |
| [get_Path](./get_path/)() const | Ubicación del documento PDF donde ha aparecido el error de extracción de texto. |
| [get_TextStartPoint](./get_textstartpoint/)() const | Clave (nombre) del objeto PDF [Font](../font/) que se utiliza para mostrar el operador que causa el error de extracción de texto. |
| [ToString](./tostring/)() const override | Devuelve la representación en cadena. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
