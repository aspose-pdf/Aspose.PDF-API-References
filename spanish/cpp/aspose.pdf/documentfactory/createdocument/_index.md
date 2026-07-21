---
title: "Aspose::Pdf::DocumentFactory::CreateDocument método"
linktitle: "CreateDocument"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::DocumentFactory::CreateDocument método. Crea un documento vacío en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf/documentfactory/createdocument/
---
## DocumentFactory::CreateDocument() method


Crear documento vacío.

```cpp
System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument()
```


### ReturnValue

Documento creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentFactory::CreateDocument(const System::SharedPtr\<System::IO::Stream\>\&) method


Cargar documento desde un flujo.

```cpp
System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument(const System::SharedPtr<System::IO::Stream> &input)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia de entrada. |

### ReturnValue

Documento creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentFactory::CreateDocument(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&) method


Crear documento.

```cpp
System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument(const System::SharedPtr<System::IO::Stream> &input, const System::SharedPtr<LoadOptions> &options)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia de entrada. |
| options | const System::SharedPtr\<LoadOptions\>\& | [Document](../../document/) opciones de carga. |

### ReturnValue

Documento creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [LoadOptions](../../loadoptions/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentFactory::CreateDocument(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) method


Cargar documento protegido con contraseña desde un flujo.

```cpp
System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument(const System::SharedPtr<System::IO::Stream> &input, const System::String &password)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Flujo de origen. |
| password | const System::String\& | Contraseña para acceder al documento. |

### ReturnValue

Documento creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentFactory::CreateDocument(const System::String\&) method


Cargar documento desde un archivo.

```cpp
System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument(const System::String &fileName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | const System::String\& | Nombre del archivo PDF. |

### ReturnValue

Documento creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [String](../../../system/string/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
