---
title: "Aspose::Pdf::Text::FontCollection::Contains método"
linktitle: "Contiene"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::FontCollection::Contains método. Determina si la colección contiene un valor específico en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf.text/fontcollection/contains/
---
## FontCollection::Contains(const System::SharedPtr\<Font\>\&) const method


Determina si la colección contiene un valor específico.

```cpp
bool Aspose::Pdf::Text::FontCollection::Contains(const System::SharedPtr<Font> &item) const override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| elemento | const System::SharedPtr\<Font\>\& | El objeto a localizar en la colección |

### ReturnValue

true si el elemento se encuentra en la colección; de lo contrario, false.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [FontCollection](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## FontCollection::Contains(const System::String\&) const method


Comprueba si la fuente existe en la colección de fuentes.

```cpp
bool Aspose::Pdf::Text::FontCollection::Contains(const System::String &name) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const System::String\& | [Font](../../font/) nombre. |

### ReturnValue

Verdadero en caso de que la colección contenga la fuente con el nombre especificado.

## Ver también

* Class [String](../../../system/string/)
* Class [FontCollection](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
