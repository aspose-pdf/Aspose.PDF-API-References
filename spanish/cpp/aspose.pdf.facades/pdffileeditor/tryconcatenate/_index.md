---
title: "Método Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate"
linktitle: "TryConcatenate"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate. Concatena documentos en C++."
type: docs
weight: 6300
url: /es/cpp/aspose.pdf.facades/pdffileeditor/tryconcatenate/
---
## PdfFileEditor::TryConcatenate(const System::ArrayPtr\<System::SharedPtr\<Document\>\>\&, const System::SharedPtr\<Document\>\&) method


Concatena documentos.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(const System::ArrayPtr<System::SharedPtr<Document>> &src, const System::SharedPtr<Document> &dest)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | const System::ArrayPtr\<System::SharedPtr\<Document\>\>\& | Matriz de documentos de origen. |
| dest | const System::SharedPtr\<Document\>\& | Documento de destino. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryConcatenate es similar al método Concatenate, excepto que el método TryConcatenate no lanza una excepción si la operación falla.
## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Concatena archivos.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(const System::ArrayPtr<System::SharedPtr<System::IO::Stream>> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\& | Matriz de flujos a concatenar. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo donde se almacenará el archivo resultante. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryConcatenate es similar al método Concatenate, excepto que el método TryConcatenate no lanza una excepción si la operación falla.
## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Concatena archivos y almacena el resultado en el objeto HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(const System::ArrayPtr<System::SharedPtr<System::IO::Stream>> &inputStream, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\& | Matriz de flujos que contiene archivos para concatenar. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto de respuesta/ |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryConcatenate es similar al método Concatenate, excepto que el método TryConcatenate no lanza una excepción si la operación falla.
## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(const System::ArrayPtr\<System::String\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Concatena archivos y guarda el resultado en el objeto HttpResposnse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(const System::ArrayPtr<System::String> &inputFiles, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFiles | const System::ArrayPtr\<System::String\>\& | Matriz de archivos a concatenar. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto de respuesta. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryConcatenate es similar al método Concatenate, excepto que el método TryConcatenate no lanza una excepción si la operación falla.
## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(const System::ArrayPtr\<System::String\>\&, const System::String\&) method


Concatena archivos en un solo archivo.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(const System::ArrayPtr<System::String> &inputFiles, const System::String &outputFile)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFiles | const System::ArrayPtr\<System::String\>\& | Matriz de archivos a concatenar. |
| outputFile | const System::String\& | Nombre del archivo de salida. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryConcatenate es similar al método Concatenate, excepto que el método TryConcatenate no lanza una excepción si la operación falla.
## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Fusiona dos documentos [Pdf](../../../aspose.pdf/) en un nuevo documento [Pdf](../../../aspose.pdf/) con páginas de forma alterna y rellena los espacios en blanco con páginas en blanco. Por ejemplo: document1 tiene 5 páginas: p1, p2, p3, p4, p5. document2 tiene 3 páginas: p1', p2', p3'. Fusionar los dos documentos [Pdf](../../../aspose.pdf/) producirá el documento resultante con páginas: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(const System::SharedPtr<System::IO::Stream> &firstInputStream, const System::SharedPtr<System::IO::Stream> &secInputStream, const System::SharedPtr<System::IO::Stream> &blankPageStream, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstInputStream | const System::SharedPtr\<System::IO::Stream\>\& | El primer [Pdf](../../../aspose.pdf/) Stream. |
| secInputStream | const System::SharedPtr\<System::IO::Stream\>\& | El segundo [Pdf](../../../aspose.pdf/) Stream. |
| blankPageStream | const System::SharedPtr\<System::IO::Stream\>\& | El flujo [Pdf](../../../aspose.pdf/) con página en blanco. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Salida [Pdf](../../../aspose.pdf/) Stream. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryConcatenate es similar al método Concatenate, excepto que el método TryConcatenate no lanza una excepción si la operación falla.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(const System::String\&, const System::String\&, const System::String\&, const System::String\&) method


Fusiona dos documentos [Pdf](../../../aspose.pdf/) en un nuevo documento [Pdf](../../../aspose.pdf/) con páginas de forma alterna y rellena los espacios en blanco con páginas en blanco. Por ejemplo: document1 tiene 5 páginas: p1, p2, p3, p4, p5. document2 tiene 3 páginas: p1', p2', p3'. Fusionar los dos documentos [Pdf](../../../aspose.pdf/) producirá el documento resultante con páginas: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(const System::String &firstInputFile, const System::String &secInputFile, const System::String &blankPageFile, const System::String &outputFile)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstInputFile | const System::String\& | Primer archivo. |
| secInputFile | const System::String\& | Segundo archivo. |
| blankPageFile | const System::String\& | Archivo PDF con página en blanco. |
| outputFile | const System::String\& | Archivo de resultado. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryConcatenate es similar al método Concatenate, excepto que el método TryConcatenate no lanza una excepción si la operación falla.
## Ver también

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(const System::String\&, const System::String\&, const System::String\&) method


Concatena dos archivos.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(const System::String &firstInputFile, const System::String &secInputFile, const System::String &outputFile)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstInputFile | const System::String\& | Primer archivo a concatenar. |
| secInputFile | const System::String\& | Segundo archivo a concatenar. |
| outputFile | const System::String\& | Archivo de salida. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryConcatenate es similar al método Concatenate, excepto que el método TryConcatenate no lanza una excepción si la operación falla.
## Ver también

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
