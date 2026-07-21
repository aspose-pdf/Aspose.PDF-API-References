---
title: "Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp método"
linktitle: "TryMakeNUp"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp método. Crea un documento N-Up a partir de los flujos PDF de entrada múltiples hacia outputStream. Cada página de outputStream contendrá múltiples páginas, que son la combinación con las páginas de los flujos de entrada del mismo número de página. Las multipáginas se apilan horizontalmente si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso en C++."
type: docs
weight: 6800
url: /es/cpp/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## PdfFileEditor::TryMakeNUp(const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&, const System::SharedPtr\<System::IO::Stream\>\&, bool) method


Crea un documento N-Up a partir de varios flujos PDF de entrada a outputStream. Cada página de outputStream contendrá múltiples páginas, que son una combinación de las páginas de los flujos de entrada con el mismo número de página. Las múltiples páginas se apilan horizontalmente si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::ArrayPtr<System::SharedPtr<System::IO::Stream>> &inputStreams, const System::SharedPtr<System::IO::Stream> &outputStream, bool isSidewise)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStreams | const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\& | Flujos de entrada [Pdf](../../../aspose.pdf/). |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo pdf de salida. |
| isSidewise | bool | Modo de apilamiento, verdadero para horizontalmente y falso para verticalmente. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryMakeNUp es similar al método MakeNUp, excepto que el método TryMakeNUp no lanza una excepción si la operación falla.
## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::ArrayPtr\<System::String\>\&, const System::String\&, bool) method


Crea un documento N-Up a partir de varios archivos PDF de entrada a outputFile. Cada página de outputFile contendrá múltiples páginas, que son una combinación de las páginas de los archivos de entrada con el mismo número de página. Las múltiples páginas se apilan horizontalmente si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::ArrayPtr<System::String> &inputFiles, const System::String &outputFile, bool isSidewise)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFiles | const System::ArrayPtr\<System::String\>\& | Archivos [Pdf](../../../aspose.pdf/) de entrada. |
| outputFile | const System::String\& | Ruta y nombre del archivo pdf de salida. |
| isSidewise | bool | Modo de apilamiento, verdadero para horizontalmente y falso para verticalmente. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryMakeNUp es similar al método MakeNUp, excepto que el método TryMakeNUp no lanza una excepción si la operación falla.
## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Crea un documento N-Up a partir de los dos flujos PDF de entrada a outputStream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::SharedPtr<System::IO::Stream> &firstInputStream, const System::SharedPtr<System::IO::Stream> &secondInputStream, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstInputStream | const System::SharedPtr\<System::IO::Stream\>\& | Primer flujo de entrada. |
| secondInputStream | const System::SharedPtr\<System::IO::Stream\>\& | Segundo flujo de entrada. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo pdf de salida. |

### ReturnValue

verdadero si la operación se completó con éxito; de lo contrario, falso
## Observaciones



El método TryMakeNUp es similar al método MakeNUp, excepto que el método TryMakeNUp no lanza una excepción si la operación falla.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t) method


Crea un documento N-Up a partir del flujo de entrada y guarda el resultado en el flujo de salida.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream, int32_t x, int32_t y)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia pdf de entrada. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo pdf de salida. |
| x | int32_t | Número de columnas. |
| y | int32_t | Número de filas. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryMakeNUp es similar al método MakeNUp, excepto que el método TryMakeNUp no lanza una excepción si la operación falla.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::SharedPtr\<PageSize\>\&) method


Crea un documento N-Up desde el primer flujo de entrada al flujo de salida.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream, int32_t x, int32_t y, const System::SharedPtr<PageSize> &pageSize)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia pdf de entrada. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo pdf de salida. |
| x | int32_t | Número de columnas. |
| y | int32_t | Número de filas. |
| pageSize | const System::SharedPtr\<PageSize\>\& | El tamaño de página del archivo pdf de salida. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryMakeNUp es similar al método MakeNUp, excepto que el método TryMakeNUp no lanza una excepción si la operación falla.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Crea un documento N-up y almacena el resultado en un objeto HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t x, int32_t y, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo del documento de origen. |
| x | int32_t | Número de columnas. |
| y | int32_t | Número de filas. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Tamaño de [Page](../../../aspose.pdf/page/) en el archivo resultante. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto HttpResponse donde se almacenará el resultado. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryMakeNUp es similar al método MakeNUp, excepto que el método TryMakeNUp no lanza una excepción si la operación falla.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Crea un documento N-up y almacena el resultado en HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t x, int32_t y, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo del documento de entrada. |
| x | int32_t | Número de columnas. |
| y | int32_t | Número de filas. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse donde se almacenará el resultado. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryMakeNUp es similar al método MakeNUp, excepto que el método TryMakeNUp no lanza una excepción si la operación falla.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::String\&, const System::String\&, const System::String\&) method


Crea un documento N-Up a partir de los dos archivos PDF de entrada a outputFile. Cada página de outputFile contendrá dos páginas, una proveniente del primer archivo de entrada y otra del segundo archivo de entrada. Las dos páginas se apilan horizontalmente.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::String &firstInputFile, const System::String &secondInputFile, const System::String &outputFile)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstInputFile | const System::String\& | primer archivo de entrada. |
| secondInputFile | const System::String\& | segundo archivo de entrada. |
| outputFile | const System::String\& | Ruta y nombre del archivo pdf de salida. |

### ReturnValue

verdadero si la operación se completó con éxito; de lo contrario, falso
## Observaciones



El método TryMakeNUp es similar al método MakeNUp, excepto que el método TryMakeNUp no lanza una excepción si la operación falla.
## Ver también

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::String\&, const System::String\&, int32_t, int32_t) method


Crea un documento N-Up desde firstInputFile a outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::String &inputFile, const System::String &outputFile, int32_t x, int32_t y)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Ruta y nombre del archivo pdf de entrada. |
| outputFile | const System::String\& | Ruta y nombre del archivo pdf de salida. |
| x | int32_t | Número de columnas. |
| y | int32_t | Número de filas. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryMakeNUp es similar al método MakeNUp, excepto que el método TryMakeNUp no lanza una excepción si la operación falla.
## Ver también

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::String\&, const System::String\&, int32_t, int32_t, const System::SharedPtr\<PageSize\>\&) method


Crea un documento N-Up a partir del archivo de entrada a outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::String &inputFile, const System::String &outputFile, int32_t x, int32_t y, const System::SharedPtr<PageSize> &pageSize)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Ruta y nombre del archivo pdf de entrada. |
| outputFile | const System::String\& | Ruta y nombre del archivo pdf de salida. |
| x | int32_t | Número de columnas. |
| y | int32_t | Número de filas. |
| pageSize | const System::SharedPtr\<PageSize\>\& | El tamaño de página del archivo pdf de salida. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryMakeNUp es similar al método MakeNUp, excepto que el método TryMakeNUp no lanza una excepción si la operación falla.
## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::String\&, int32_t, int32_t, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Crea un documento N-up y almacena el resultado en un objeto HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::String &inputFile, int32_t x, int32_t y, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Ruta al archivo de origen. |
| x | int32_t | Número de columnas. |
| y | int32_t | Número de filas. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Tamaño de [Page](../../../aspose.pdf/page/) en el archivo resultante. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto HttpResponse donde se almacenará el resultado. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryMakeNUp es similar al método MakeNUp, excepto que el método TryMakeNUp no lanza una excepción si la operación falla.
## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::String\&, int32_t, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Crea un documento N-up y almacena el resultado en HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::String &inputFile, int32_t x, int32_t y, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Nombre del archivo de origen. |
| x | int32_t | Número de columnas. |
| y | int32_t | Número de filas. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto HttpResponse donde se almacenará el resultado. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryMakeNUp es similar al método MakeNUp, excepto que el método TryMakeNUp no lanza una excepción si la operación falla.
## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
