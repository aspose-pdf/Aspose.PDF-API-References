---
title: "Método Aspose::Pdf::Text::FontRepository::OpenFont"
linktitle: "OpenFont"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::Text::FontRepository::OpenFont. Abre la fuente con el flujo de fuente especificado en C++."
type: docs
weight: 500
url: /es/cpp/aspose.pdf.text/fontrepository/openfont/
---
## FontRepository::OpenFont(const System::SharedPtr\<System::IO::Stream\>\&, const FontTypes\&) method


Abre la fuente con el flujo de fuente especificado.

```cpp
static System::SharedPtr<Font> Aspose::Pdf::Text::FontRepository::OpenFont(const System::SharedPtr<System::IO::Stream> &fontStream, const FontTypes &fontType)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontStream | const System::SharedPtr\<System::IO::Stream\>\& | [Font](../../font/) flujo. |
| fontType | const FontTypes\& | [Font](../../font/) valor de tipo. |

### ReturnValue

[Font](../../font/) object.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [Stream](../../../system.io/stream/)
* Enum [FontTypes](../../fonttypes/)
* Class [FontRepository](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## FontRepository::OpenFont(const System::String\&) method


Abre la fuente con la ruta de archivo de fuente especificada.

```cpp
static System::SharedPtr<Font> Aspose::Pdf::Text::FontRepository::OpenFont(const System::String &fontFilePath)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontFilePath | const System::String\& | [Font](../../font/) ruta del archivo. |

### ReturnValue

[Font](../../font/) object.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [String](../../../system/string/)
* Class [FontRepository](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## FontRepository::OpenFont(const System::String\&, const System::String\&) method


Abre la fuente con la ruta de archivo de fuente y la ruta de archivo de métricas especificadas.

```cpp
static System::SharedPtr<Font> Aspose::Pdf::Text::FontRepository::OpenFont(const System::String &fontFilePath, const System::String &metricsFilePath)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontFilePath | const System::String\& | [Font](../../font/) ruta del archivo. |
| metricsFilePath | const System::String\& | [Font](../../font/) ruta del archivo de métricas. |

### ReturnValue

[Font](../../font/) object.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [String](../../../system/string/)
* Class [FontRepository](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
