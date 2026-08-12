---
title: "Aspose::Pdf::Facades::PdfFileEditor::SplitToEnd método"
linktitle: "SplitToEnd"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::SplitToEnd método. Divide desde la ubicación especificada y guarda la parte posterior como un nuevo Stream de archivo en C++."
type: docs
weight: 6000
url: /es/cpp/aspose.pdf.facades/pdffileeditor/splittoend/
---
## PdfFileEditor::SplitToEnd(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, const System::SharedPtr\<System::IO::Stream\>\&) method


Divide desde la ubicación especificada y guarda la parte posterior como un nuevo Stream de archivo.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::SplitToEnd(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t location, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Stream de archivo [Pdf](../../../aspose.pdf/) de origen. |
| location | int32_t | La posición de división. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo de archivo de salida [Pdf](../../../aspose.pdf/). |

### ReturnValue

True para éxito, o false.
## Observaciones



Los flujos NO se cierran después de esta operación a menos que se especifique CloseConcatedStreams.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToEnd(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Divide desde la ubicación especificada y guarda la parte posterior en un objeto HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::SplitToEnd(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t location, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Stream del documento de origen. |
| location | int32_t | Punto de división. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto HttpResponse. |

### ReturnValue

verdadero si la división fue exitosa.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToEnd(const System::String\&, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Divide desde la ubicación especificada y guarda la parte posterior en un objeto HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::SplitToEnd(const System::String &inputFile, int32_t location, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | nombre del archivo de origen. |
| location | int32_t | Punto de división. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objetos HttpResponse. |

### ReturnValue

Verdadero si la operación se completó con éxito.

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToEnd(const System::String\&, int32_t, const System::String\&) method


Divide desde la ubicación y guarda la parte posterior como un archivo nuevo.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::SplitToEnd(const System::String &inputFile, int32_t location, const System::String &outputFile)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Archivo [Pdf](../../../aspose.pdf/) de origen. |
| location | int32_t | La posición de división. |
| outputFile | const System::String\& | Ruta del archivo [Pdf](../../../aspose.pdf/) de salida. |

### ReturnValue

True para éxito, o false.

## Ver también

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
