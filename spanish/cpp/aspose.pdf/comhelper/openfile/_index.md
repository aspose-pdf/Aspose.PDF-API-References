---
title: "Método Aspose::Pdf::ComHelper::OpenFile"
linktitle: "OpenFile"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::ComHelper::OpenFile. Simplemente crea y devuelve Document usando el nombre de archivo. Lo mismo que Document(Stream) en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf/comhelper/openfile/
---
## ComHelper::OpenFile(const System::String\&) method


Simplemente crea y devuelve [Document](../../document/) usando *nombre de archivo*. Lo mismo que [Document(Stream)](../).

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenFile(const System::String &filename)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const System::String\& | El nombre del archivo del documento pdf. |

### ReturnValue

[Document](../../document/) object

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [String](../../../system/string/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenFile(const System::String\&, const System::SharedPtr\<LoadOptions\>\&) method


Abra un documento existente desde un archivo proporcionando las opciones de conversión necesarias para obtener un documento PDF.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenFile(const System::String &filename, const System::SharedPtr<LoadOptions> &options)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const System::String\& | Archivo de entrada para convertir en documento pdf. |
| opciones | const System::SharedPtr\<LoadOptions\>\& | Representa propiedades para convertir *nombre de archivo* en documento pdf. |

### ReturnValue

[Document](../../document/) object

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [String](../../../system/string/)
* Class [LoadOptions](../../loadoptions/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenFile(const System::String\&, const System::String\&) method


Inicializa y devuelve una nueva instancia de la clase [Document](../../document/) para trabajar con documentos encriptados.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenFile(const System::String &filename, const System::String &password)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const System::String\& | Nombre de archivo de [Document](../../document/). |
| password | const System::String\& | Contraseña de usuario o propietario. |

### ReturnValue

[Document](../../document/) object

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [String](../../../system/string/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenFile(const System::String\&, const System::String\&, bool) method


Inicializa una nueva instancia de la clase [Document](../../document/) para trabajar con documentos encriptados.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenFile(const System::String &filename, const System::String &password, bool isManagedStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const System::String\& | Nombre de archivo de [Document](../../document/). |
| password | const System::String\& | Contraseña de usuario o propietario. |
| isManagedStream | bool | si se establece en **true**, el flujo interno se cierra antes de salir; de lo contrario, no lo está. |

### ReturnValue

[Document](../../document/) object

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [String](../../../system/string/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
