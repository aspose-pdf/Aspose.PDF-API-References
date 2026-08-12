---
title: "Constructor de Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached"
linktitle: "PKCS7Detached"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "constructor de Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached. Inicializa una nueva instancia de la clase PKCS7Detached en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.forms/pkcs7detached/pkcs7detached/
---
## PKCS7Detached::PKCS7Detached() constructor


Inicializa una nueva instancia de la clase [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached()
```

## Ver también

* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7Detached::PKCS7Detached(const System::SharedPtr\<Aspose::Pdf::TimestampSettings\>\&) constructor


Inicializa una nueva instancia de la clase [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached(const System::SharedPtr<Aspose::Pdf::TimestampSettings> &timestampSettings)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| timestampSettings | const System::SharedPtr\<Aspose::Pdf::TimestampSettings\>\& | La configuración de marca de tiempo para la firma. |
## Observaciones



La configuración de marca de tiempo se usa para crear la firma de marca de tiempo sin necesidad de proporcionar un certificado. Puede establecer la marca de tiempo para un documento como una firma separada.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TimestampSettings](../../../aspose.pdf/timestampsettings/)
* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7Detached::PKCS7Detached(const System::SharedPtr\<System::IO::Stream\>\&) constructor


Inicializa una nueva instancia de la clase [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached(const System::SharedPtr<System::IO::Stream> &image)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imagen | const System::SharedPtr\<System::IO::Stream\>\& | Esta imagen definirá la apariencia de la firma en la página. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7Detached::PKCS7Detached(const System::SharedPtr\<System::IO::Stream\>\&, DigestHashAlgorithm) constructor


Inicializa una nueva instancia de la clase [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached(const System::SharedPtr<System::IO::Stream> &image, DigestHashAlgorithm digestHashAlgorithm)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imagen | const System::SharedPtr\<System::IO::Stream\>\& | Esta imagen definirá la apariencia de la firma en la página. |
| digestHashAlgorithm | DigestHashAlgorithm | El algoritmo de resumen para firmar un documento. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7Detached::PKCS7Detached(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) constructor


Inicializa una nueva instancia de la clase [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached(const System::SharedPtr<System::IO::Stream> &pfx, const System::String &password)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pfx | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia con datos del certificado organizados como pfx. |
| password | const System::String\& | Contraseña para obtener acceso a la clave privada del certificado. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7Detached::PKCS7Detached(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, DigestHashAlgorithm) constructor


Inicializa una nueva instancia de la clase [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached(const System::SharedPtr<System::IO::Stream> &pfx, const System::String &password, DigestHashAlgorithm digestHashAlgorithm)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pfx | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia con datos del certificado organizados como pfx. |
| password | const System::String\& | Contraseña para obtener acceso a la clave privada del certificado. |
| digestHashAlgorithm | DigestHashAlgorithm | El algoritmo de resumen para firmar un documento. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7Detached::PKCS7Detached(const System::String\&, const System::String\&) constructor


Inicializa una nueva instancia de la clase [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached(const System::String &pfx, const System::String &password)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pfx | const System::String\& | Archivo pfx que contiene el certificado para firmar. |
| password | const System::String\& | Contraseña para obtener acceso a la clave privada del certificado. |

## Ver también

* Class [String](../../../system/string/)
* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7Detached::PKCS7Detached(const System::String\&, const System::String\&, DigestHashAlgorithm) constructor


Inicializa una nueva instancia de la clase [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached(const System::String &pfx, const System::String &password, DigestHashAlgorithm digestHashAlgorithm)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pfx | const System::String\& | Archivo pfx que contiene el certificado para firmar. |
| password | const System::String\& | Contraseña para obtener acceso a la clave privada del certificado. |
| digestHashAlgorithm | DigestHashAlgorithm | El algoritmo de resumen para firmar un documento. |

## Ver también

* Class [String](../../../system/string/)
* Enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7Detached::PKCS7Detached(DigestHashAlgorithm) constructor


Inicializa una nueva instancia de la clase [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached(DigestHashAlgorithm digestHashAlgorithm)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| digestHashAlgorithm | DigestHashAlgorithm | El algoritmo de resumen para firmar un documento. |

## Ver también

* Enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
