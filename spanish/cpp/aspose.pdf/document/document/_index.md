---
title: "Constructor Aspose::Pdf::Document::Document"
linktitle: "Document"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Constructor Aspose::Pdf::Document::Document. Inicializa un documento vacío en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf/document/document/
---
## Document::Document() constructor


Inicializa un documento vacío.

```cpp
Aspose::Pdf::Document::Document()
```

## Ver también

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&) constructor


Inicializar una nueva instancia de [Document](../) a partir del flujo *input*.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Flujo con documento pdf. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, bool) constructor


Inicializar una nueva instancia de [Document](../) a partir del flujo *input*.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, bool isManagedStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Flujo con documento pdf. |
| isManagedStream | bool | si se establece en **true**, el flujo interno se cierra antes de salir; de lo contrario, no lo está. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&) constructor


Abre un documento existente desde un flujo proporcionando la conversión necesaria para obtener un documento pdf.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::SharedPtr<LoadOptions> &options)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Flujo de entrada para convertir en documento pdf. |
| opciones | const System::SharedPtr\<LoadOptions\>\& | Representa propiedades para convertir *entrada* en documento pdf. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [LoadOptions](../../loadoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&) constructor


Inicializar una nueva instancia de [Document](../) a partir del flujo *input*.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::SharedPtr<Security::CertificateEncryptionOptions> &certOptions)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Objeto de flujo de entrada, el pdf correspondiente está protegido con contraseña. |
| certOptions | const System::SharedPtr\<Security::CertificateEncryptionOptions\>\& | Las opciones de cifrado del certificado. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&, bool) constructor


Inicializar una nueva instancia de [Document](../) a partir del flujo *input*.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::SharedPtr<Security::CertificateEncryptionOptions> &certOptions, bool isManagedStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Flujo con documento pdf. |
| certOptions | const System::SharedPtr\<Security::CertificateEncryptionOptions\>\& | Las opciones de cifrado del certificado. |
| isManagedStream | bool | Si se establece en **true**, el flujo interno se cierra antes de salir; de lo contrario, no lo está. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) constructor


Inicializar una nueva instancia de [Document](../) a partir del flujo *input*.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::String &password)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Objeto de flujo de entrada, el pdf correspondiente está protegido con contraseña. |
| password | const System::String\& | Contraseña de usuario o propietario. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, bool) constructor


Inicializar una nueva instancia de [Document](../) a partir del flujo *input*.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::String &password, bool isManagedStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Flujo con documento pdf. |
| password | const System::String\& | Contraseña de usuario o propietario. |
| isManagedStream | bool | Si se establece en **true**, el flujo interno se cierra antes de salir; de lo contrario, no lo está. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, bool, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) constructor


Inicializar una nueva instancia de [Document](../) a partir del flujo *input*.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::String &password, bool isManagedStream, const System::SharedPtr<Security::ICustomSecurityHandler> &customSecurityHandler)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Flujo con documento pdf. |
| password | const System::String\& | Contraseña de usuario o propietario. |
| isManagedStream | bool | Si se establece en **true**, el flujo interno se cierra antes de salir; de lo contrario, no lo está. |
| customSecurityHandler | const System::SharedPtr\<Security::ICustomSecurityHandler\>\& | El controlador de seguridad personalizado. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) constructor


Inicializar una nueva instancia de [Document](../) a partir del flujo *input*.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::String &password, const System::SharedPtr<Security::ICustomSecurityHandler> &customSecurityHandler)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Objeto de flujo de entrada, el pdf correspondiente está protegido con contraseña. |
| password | const System::String\& | Contraseña de usuario o propietario. |
| customSecurityHandler | const System::SharedPtr\<Security::ICustomSecurityHandler\>\& | El controlador de seguridad personalizado. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&) constructor


Simplemente inicializa [Document](../) usando *filename*. Lo mismo que [Document(Stream)](../).

```cpp
Aspose::Pdf::Document::Document(const System::String &filename)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const System::String\& | El nombre del archivo del documento pdf. |

## Ver también

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, bool) constructor


Simplemente inicializa [Document](../) usando *filename*. Lo mismo que [Document(Stream)](../).

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, bool isManagedStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const System::String\& | El nombre del archivo del documento pdf. |
| isManagedStream | bool | Si se establece en **true**, el flujo interno se cierra antes de salir; de lo contrario, no lo está. |

## Ver también

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::SharedPtr\<LoadOptions\>\&) constructor


Abre un documento existente desde un archivo proporcionando las opciones de conversión necesarias para obtener un documento pdf.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::SharedPtr<LoadOptions> &options)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const System::String\& | Archivo de entrada para convertir en documento pdf. |
| opciones | const System::SharedPtr\<LoadOptions\>\& | Representa propiedades para convertir *nombre de archivo* en documento pdf. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LoadOptions](../../loadoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&) constructor


Inicializa una nueva instancia de la clase [Document](../) para trabajar con documentos cifrados.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::SharedPtr<Security::CertificateEncryptionOptions> &certOptions)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const System::String\& | Nombre de archivo de [Document](../). |
| certOptions | const System::SharedPtr\<Security::CertificateEncryptionOptions\>\& | Las opciones de cifrado del certificado. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&, bool) constructor


Inicializa una nueva instancia de la clase [Document](../) para trabajar con documentos cifrados.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::SharedPtr<Security::CertificateEncryptionOptions> &certOptions, bool isManagedStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const System::String\& | Nombre de archivo de [Document](../). |
| certOptions | const System::SharedPtr\<Security::CertificateEncryptionOptions\>\& | Las opciones de cifrado del certificado. |
| isManagedStream | bool | si se establece en **true**, el flujo interno se cierra antes de salir; de lo contrario, no lo está. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::String\&) constructor


Inicializa una nueva instancia de la clase [Document](../) para trabajar con documentos cifrados.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::String &password)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const System::String\& | Nombre de archivo de [Document](../). |
| password | const System::String\& | Contraseña de usuario o propietario. |

## Ver también

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::String\&, bool) constructor


Inicializa una nueva instancia de la clase [Document](../) para trabajar con documentos cifrados.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::String &password, bool isManagedStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const System::String\& | Nombre de archivo de [Document](../). |
| password | const System::String\& | Contraseña de usuario o propietario. |
| isManagedStream | bool | si se establece en **true**, el flujo interno se cierra antes de salir; de lo contrario, no lo está. |

## Ver también

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::String\&, bool, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) constructor


Inicializa una nueva instancia de la clase [Document](../) para trabajar con documentos cifrados.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::String &password, bool isManagedStream, const System::SharedPtr<Security::ICustomSecurityHandler> &customSecurityHandler)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const System::String\& | Nombre de archivo de [Document](../). |
| password | const System::String\& | Contraseña de usuario o propietario. |
| isManagedStream | bool | si se establece en **true**, el flujo interno se cierra antes de salir; de lo contrario, no lo está. |
| customSecurityHandler | const System::SharedPtr\<Security::ICustomSecurityHandler\>\& | El controlador de seguridad personalizado. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::String\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) constructor


Inicializa una nueva instancia de la clase [Document](../) para trabajar con documentos cifrados.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::String &password, const System::SharedPtr<Security::ICustomSecurityHandler> &customSecurityHandler)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const System::String\& | Nombre de archivo de [Document](../). |
| password | const System::String\& | Contraseña de usuario o propietario. |
| customSecurityHandler | const System::SharedPtr\<Security::ICustomSecurityHandler\>\& | El controlador de seguridad personalizado. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(PdfVersion) constructor


Inicializa un documento vacío por versión.

```cpp
Aspose::Pdf::Document::Document(PdfVersion version)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| versión | PdfVersion | La versión PDF. |

## Ver también

* Enum [PdfVersion](../../pdfversion/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
