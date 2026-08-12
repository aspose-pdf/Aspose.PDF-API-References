---
title: "Aspose::Pdf::Document::Save método"
linktitle: "Guardar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Document::Save método. Guarda el documento de forma incremental (p.ej., usando la técnica de actualización incremental) en C++."
type: docs
weight: 8300
url: /es/cpp/aspose.pdf/document/save/
---
## Document::Save() method


Guarda el documento de forma incremental (es decir, usando la técnica de actualización incremental).

```cpp
void Aspose::Pdf::Document::Save()
```

## Observaciones


Para guardar el documento de forma incremental debemos abrir el archivo del documento para escritura. Por lo tanto, [Document](../) debe inicializarse con un flujo de escritura como en el siguiente fragmento de código: [Document](../) doc = new [Document](../)(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // realizar algunos cambios y guardar el documento de forma incremental doc.Save();
## Ver también

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::SharedPtr\<SaveOptions\>\&) method


Guarda el documento con opciones de guardado.

```cpp
void Aspose::Pdf::Document::Save(const System::SharedPtr<SaveOptions> &options)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| opciones | const System::SharedPtr\<SaveOptions\>\& | Opciones de guardado. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::SharedPtr\<System::IO::Stream\>\&) method


Almacena el documento en un flujo.

```cpp
void Aspose::Pdf::Document::Save(const System::SharedPtr<System::IO::Stream> &output)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| output | const System::SharedPtr\<System::IO::Stream\>\& | Flujo donde se almacenará el documento. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<SaveOptions\>\&) method


Guarda el documento en un flujo con opciones de guardado.

```cpp
void Aspose::Pdf::Document::Save(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<SaveOptions> &options)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo donde se almacenará el documento. |
| opciones | const System::SharedPtr\<SaveOptions\>\& | Opciones de guardado. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::SharedPtr\<System::IO::Stream\>\&, SaveFormat) method


Guarda el documento con un nuevo nombre junto con un formato de archivo.

```cpp
void Aspose::Pdf::Document::Save(const System::SharedPtr<System::IO::Stream> &outputStream, SaveFormat format)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo donde se almacenará el documento. |
| formato | SaveFormat | Opciones de formato. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [SaveFormat](../../saveformat/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::SharedPtr\<System::Web::HttpResponse\>\&, const System::String\&, ContentDisposition, const System::SharedPtr\<SaveOptions\>\&) method


Guarda el documento en un flujo de respuesta con opciones de guardado.

```cpp
void Aspose::Pdf::Document::Save(const System::SharedPtr<System::Web::HttpResponse> &response, const System::String &outputFileName, ContentDisposition disposition, const System::SharedPtr<SaveOptions> &options)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Encapsula la información de la respuesta HTTP. |
| outputFileName | const System::String\& | Nombre de archivo simple, es decir, sin ruta. |
| disposición | ContentDisposition | Representa un encabezado Content-Disposition del protocolo MIME. |
| opciones | const System::SharedPtr\<SaveOptions\>\& | Opciones de guardado. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [String](../../../system/string/)
* Enum [ContentDisposition](../../contentdisposition/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::String\&) method


Guarda el documento en el archivo especificado.

```cpp
void Aspose::Pdf::Document::Save(const System::String &outputFileName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFileName | const System::String\& | Ruta al archivo donde se almacenará el documento. |

## Ver también

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::String\&, const System::SharedPtr\<SaveOptions\>\&) method


Guarda el documento con un nuevo nombre estableciendo sus opciones de guardado.

```cpp
void Aspose::Pdf::Document::Save(const System::String &outputFileName, const System::SharedPtr<SaveOptions> &options)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFileName | const System::String\& | Ruta al archivo donde se almacenará el documento. |
| opciones | const System::SharedPtr\<SaveOptions\>\& | Opciones de guardado. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(const System::String\&, SaveFormat) method


Guarda el documento con un nuevo nombre junto con un formato de archivo.

```cpp
void Aspose::Pdf::Document::Save(const System::String &outputFileName, SaveFormat format)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFileName | const System::String\& | Ruta al archivo donde se almacenará el documento. |
| formato | SaveFormat | Opciones de formato. |

## Ver también

* Class [String](../../../system/string/)
* Enum [SaveFormat](../../saveformat/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
