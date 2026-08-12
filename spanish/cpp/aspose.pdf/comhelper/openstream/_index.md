---
title: "Aspose::Pdf::ComHelper::OpenStream método"
linktitle: "OpenStream"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::ComHelper::OpenStream. Inicializa y devuelve una nueva instancia de Document a partir del flujo de entrada en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf/comhelper/openstream/
---
## ComHelper::OpenStream(const System::SharedPtr\<System::IO::Stream\>\&) method


Inicializa y devuelve una nueva instancia de [Document](../../document/) a partir del flujo *entrada*.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(const System::SharedPtr<System::IO::Stream> &input)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Flujo con documento pdf. |

### ReturnValue

[Document](../../document/) object

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenStream(const System::SharedPtr\<System::IO::Stream\>\&, bool) method


Inicializa y devuelve una nueva instancia de [Document](../../document/) a partir del flujo *entrada*.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(const System::SharedPtr<System::IO::Stream> &input, bool isManagedStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Flujo con documento pdf. |
| isManagedStream | bool | si se establece en **true**, el flujo interno se cierra antes de salir; de lo contrario, no lo está. |

### ReturnValue

[Document](../../document/) object

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenStream(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&) method


Abra y devuelva un documento existente desde un flujo proporcionando la conversión necesaria para obtener un documento PDF.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(const System::SharedPtr<System::IO::Stream> &input, const System::SharedPtr<LoadOptions> &options)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Flujo de entrada para convertir en documento pdf. |
| opciones | const System::SharedPtr\<LoadOptions\>\& | Representa propiedades para convertir *entrada* en documento pdf. |

### ReturnValue

[Document](../../document/) object

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [LoadOptions](../../loadoptions/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenStream(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) method


Inicializa y devuelve una nueva instancia de [Document](../../document/) a partir del flujo *entrada*.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(const System::SharedPtr<System::IO::Stream> &input, const System::String &password)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Objeto de flujo de entrada, el pdf correspondiente está protegido con contraseña. |
| password | const System::String\& | Contraseña de usuario o propietario. |

### ReturnValue

[Document](../../document/) object

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenStream(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, bool) method


Inicializa y devuelve una nueva instancia de [Document](../../document/) a partir del flujo *entrada*.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(const System::SharedPtr<System::IO::Stream> &input, const System::String &password, bool isManagedStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Flujo con documento pdf. |
| password | const System::String\& | Contraseña de usuario o propietario. |
| isManagedStream | bool | si se establece en **true**, el flujo interno se cierra antes de salir; de lo contrario, no lo está. |

### ReturnValue

[Document](../../document/) object

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
