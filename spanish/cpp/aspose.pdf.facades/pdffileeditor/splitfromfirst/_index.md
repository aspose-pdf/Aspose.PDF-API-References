---
title: "Aspose::Pdf::Facades::PdfFileEditor::SplitFromFirst método"
linktitle: "SplitFromFirst"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::SplitFromFirst método. Divide desde el inicio hasta la ubicación especificada y guarda la parte frontal en el Stream de salida en C++."
type: docs
weight: 5800
url: /es/cpp/aspose.pdf.facades/pdffileeditor/splitfromfirst/
---
## PdfFileEditor::SplitFromFirst(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, const System::SharedPtr\<System::IO::Stream\>\&) method


Divide desde el inicio hasta la ubicación especificada y guarda la parte frontal en el Stream de salida.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::SplitFromFirst(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t location, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Stream de archivo [Pdf](../../../aspose.pdf/) de origen. |
| location | int32_t | El punto de división. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo de archivo de salida. |

### ReturnValue

True para éxito, o false.
## Observaciones



Los flujos NO se cierran después de esta operación.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitFromFirst(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Divide el documento desde el inicio hasta la ubicación especificada y almacena el resultado en un objeto HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::SplitFromFirst(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t location, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo del documento de origen. |
| location | int32_t | El punto de división. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto HttpResponse donde se almacenará el resultado. |

### ReturnValue

Verdadero si la operación se completó con éxito.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitFromFirst(const System::String\&, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Divide el documento desde la primera página hasta la ubicación y guarda el resultado en objetos HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::SplitFromFirst(const System::String &inputFile, int32_t location, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Nombre del archivo de origen. |
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
## PdfFileEditor::SplitFromFirst(const System::String\&, int32_t, const System::String\&) method


Divide el archivo [Pdf](../../../aspose.pdf/) desde la primera página hasta la ubicación especificada y guarda la parte frontal como un nuevo archivo.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::SplitFromFirst(const System::String &inputFile, int32_t location, const System::String &outputFile)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Archivo [Pdf](../../../aspose.pdf/) de origen. |
| location | int32_t | El punto de división. |
| outputFile | const System::String\& | Salida [Pdf](../../../aspose.pdf/) archivo. |

### ReturnValue

True para éxito, o false.

## Ver también

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
