---
title: "Aspose::Pdf::Facades::PdfFileEditor::TryInsert method"
linktitle: "TryInsert"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::TryInsert method. Inserta páginas de otro archivo en el archivo Pdf de entrada en C++."
type: docs
weight: 6600
url: /es/cpp/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## PdfFileEditor::TryInsert(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Inserta páginas de otro archivo en el archivo [Pdf](../../../aspose.pdf/) de entrada.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryInsert(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t insertLocation, const System::SharedPtr<System::IO::Stream> &portStream, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia de entrada del archivo [Pdf](../../../aspose.pdf/). |
| insertLocation | int32_t | Posición de inserción en el archivo de entrada. |
| portStream | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia del archivo [Pdf](../../../aspose.pdf/) para páginas. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | El número de página del portado en portFile. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia de salida. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryInsert es similar al método Insert, excepto que el método TryInsert no lanza una excepción si la operación falla.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryInsert(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Inserta el documento en otro documento y almacena el resultado en un objeto de respuesta.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryInsert(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t insertLocation, const System::SharedPtr<System::IO::Stream> &portStream, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo con documento fuente |
| insertLocation | int32_t | Ubicación donde se insertará el otro documento. |
| portStream | const System::SharedPtr\<System::IO::Stream\>\& | [Document](../../../aspose.pdf/document/) para ser insertado. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Matriz de números de página en el segundo documento que se insertará. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto de respuesta donde se almacenará el resultado. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryInsert es similar al método Insert, excepto que el método TryInsert no lanza una excepción si la operación falla.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryInsert(const System::String\&, int32_t, const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Inserta el contenido del archivo en el archivo fuente y almacena el resultado en un objeto HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryInsert(const System::String &inputFile, int32_t insertLocation, const System::String &portFile, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Nombre del archivo de origen. |
| insertLocation | int32_t | número de [Page](../../../aspose.pdf/page/) donde se insertará el segundo archivo. |
| portFile | const System::String\& | Ruta al archivo que se insertará. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Matriz de números de página en el archivo fuente que se insertará. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto de respuesta donde se almacenará el resultado. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryInsert es similar al método Insert, excepto que el método TryInsert no lanza una excepción si la operación falla.
## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryInsert(const System::String\&, int32_t, const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::String\&) method


Inserta páginas de otro archivo en el archivo [Pdf](../../../aspose.pdf/) de entrada.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryInsert(const System::String &inputFile, int32_t insertLocation, const System::String &portFile, const System::ArrayPtr<int32_t> &pageNumber, const System::String &outputFile)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Archivo [Pdf](../../../aspose.pdf/) de entrada. |
| insertLocation | int32_t | Posición de inserción en el archivo de entrada. |
| portFile | const System::String\& | Páginas del archivo [Pdf](../../../aspose.pdf/). |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | El número de página del portado en portFile. |
| outputFile | const System::String\& | Salida [Pdf](../../../aspose.pdf/) archivo. |

### ReturnValue

True para éxito, o false.
## Observaciones



El método TryInsert es similar al método Insert, excepto que el método TryInsert no lanza una excepción si la operación falla.
## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
