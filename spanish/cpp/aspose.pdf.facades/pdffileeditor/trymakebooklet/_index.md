---
title: "Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet método"
linktitle: "TryMakeBooklet"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet método. Crea un folleto a partir de un archivo PDF y lo almacena en HttpResponse en C++."
type: docs
weight: 6700
url: /es/cpp/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## PdfFileEditor::TryMakeBooklet(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Crea un folleto a partir de un archivo PDF y lo almacena en HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<PageSize> &pageSize, const System::ArrayPtr<int32_t> &leftPages, const System::ArrayPtr<int32_t> &rightPages, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia de documento de entrada. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Tamaño de página deseado. |
| leftPages | const System::ArrayPtr\<int32_t\>\& | Arreglo de números de página que se colocarán a la izquierda. |
| rightPages | const System::ArrayPtr\<int32_t\>\& | Arreglo de números de página que se colocarán a la derecha. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto HttpResponse. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryMakeBooklet es similar al método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Crea un folleto a partir del archivo fuente y almacena el resultado en HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia de documento de entrada. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Tamaño de página deseado en el archivo de salida. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto Response donde se guardará el resultado. |

### ReturnValue

true si el folleto se construyó correctamente.
## Observaciones



El método TryMakeBooklet es similar al método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Crea un folleto a partir del InputStream hacia el outputStream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia pdf de entrada. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia pdf de salida. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryMakeBooklet es similar al método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<int32_t\>\&) method


Crea un folleto personalizado desde firstInputStream a outputStream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream, const System::ArrayPtr<int32_t> &leftPages, const System::ArrayPtr<int32_t> &rightPages)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | La secuencia de entrada. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia pdf de salida. |
| leftPages | const System::ArrayPtr\<int32_t\>\& | Las páginas de la izquierda. |
| rightPages | const System::ArrayPtr\<int32_t\>\& | Las páginas de la derecha. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryMakeBooklet es similar al método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&) method


Crea un folleto a partir del flujo de entrada y guarda el resultado en el flujo de salida.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<PageSize> &pageSize)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia de entrada PDF. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia pdf de salida. |
| pageSize | const System::SharedPtr\<PageSize\>\& | El tamaño de página del archivo pdf de salida. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryMakeBooklet es similar al método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<int32_t\>\&) method


Crea un folleto desde firstInputStream a outputStream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<PageSize> &pageSize, const System::ArrayPtr<int32_t> &leftPages, const System::ArrayPtr<int32_t> &rightPages)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | La secuencia de entrada. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia pdf de salida. |
| pageSize | const System::SharedPtr\<PageSize\>\& | El tamaño de página del archivo pdf de salida. |
| leftPages | const System::ArrayPtr\<int32_t\>\& | Las páginas de la izquierda. |
| rightPages | const System::ArrayPtr\<int32_t\>\& | Las páginas de la derecha. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryMakeBooklet es similar al método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Crea un folleto a partir del archivo fuente y almacena el resultado en objetos HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(const System::String &inputFile, const System::SharedPtr<PageSize> &pageSize, const System::ArrayPtr<int32_t> &leftPages, const System::ArrayPtr<int32_t> &rightPages, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Ruta del archivo fuente. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Tamaño de página deseado. |
| leftPages | const System::ArrayPtr\<int32_t\>\& | Matriz de números de página que se colocarán a la izquierda. |
| rightPages | const System::ArrayPtr\<int32_t\>\& | Matriz de números de página que se colocarán a la derecha. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto HttpResponse donde se almacenará el resultado. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryMakeBooklet es similar al método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.
## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Crea un folleto a partir del archivo fuente y almacena el resultado en objetos HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(const System::String &inputFile, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Ruta del archivo fuente. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Tamaño de página deseado en el archivo de salida. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto HttpResponse donde se almacenará el resultado. |

### ReturnValue

Verdadero si la operación se completó con éxito.
## Observaciones



El método TryMakeBooklet es similar al método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.
## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(const System::String\&, const System::String\&) method


Crea un folleto a partir del archivo de entrada hacia el archivo de salida.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(const System::String &inputFile, const System::String &outputFile)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Ruta y nombre del archivo pdf de entrada. |
| outputFile | const System::String\& | Ruta y nombre del archivo pdf de salida. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryMakeBooklet es similar al método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.
## Ver también

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(const System::String\&, const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<int32_t\>\&) method


Crea un folleto personalizado desde firstInputFile a outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(const System::String &inputFile, const System::String &outputFile, const System::ArrayPtr<int32_t> &leftPages, const System::ArrayPtr<int32_t> &rightPages)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | El archivo de entrada. |
| outputFile | const System::String\& | Ruta y nombre del archivo pdf de salida. |
| leftPages | const System::ArrayPtr\<int32_t\>\& | Las páginas izquierdas del folleto. |
| rightPages | const System::ArrayPtr\<int32_t\>\& | Las páginas derechas del folleto. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryMakeBooklet es similar al método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.
## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(const System::String\&, const System::String\&, const System::SharedPtr\<PageSize\>\&) method


Crea un folleto a partir del inputFile hacia el outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(const System::String &inputFile, const System::String &outputFile, const System::SharedPtr<PageSize> &pageSize)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Ruta y nombre del archivo pdf de entrada. |
| outputFile | const System::String\& | Ruta y nombre del archivo pdf de salida. |
| pageSize | const System::SharedPtr\<PageSize\>\& | El tamaño de página del archivo pdf de salida. |

### ReturnValue

Verdadero si la operación se completó con éxito.
## Observaciones



El método TryMakeBooklet es similar al método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.
## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(const System::String\&, const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<int32_t\>\&) method


Crea un folleto personalizado desde firstInputFile a outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(const System::String &inputFile, const System::String &outputFile, const System::SharedPtr<PageSize> &pageSize, const System::ArrayPtr<int32_t> &leftPages, const System::ArrayPtr<int32_t> &rightPages)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | El archivo de entrada. |
| outputFile | const System::String\& | Ruta y nombre del archivo pdf de salida. |
| pageSize | const System::SharedPtr\<PageSize\>\& | El tamaño de página del archivo pdf de salida. |
| leftPages | const System::ArrayPtr\<int32_t\>\& | Las páginas de la izquierda. |
| rightPages | const System::ArrayPtr\<int32_t\>\& | Las páginas de la derecha. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryMakeBooklet es similar al método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.
## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
