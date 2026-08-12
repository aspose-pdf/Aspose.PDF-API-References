---
title: "constructor de Aspose::Pdf::Forms::PKCS7::PKCS7"
linktitle: "PKCS7"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "constructor de Aspose::Pdf::Forms::PKCS7::PKCS7. Inicializa una nueva instancia de la clase PKKS7 en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.forms/pkcs7/pkcs7/
---
## PKCS7::PKCS7() constructor


Inicializa una nueva instancia de la clase [PKCS7](../).

```cpp
Aspose::Pdf::Forms::PKCS7::PKCS7()
```

## Ver también

* Class [PKCS7](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7::PKCS7(const System::SharedPtr\<Aspose::Pdf::TimestampSettings\>\&) constructor


Inicializa una nueva instancia de la clase [PKCS7](../).

```cpp
Aspose::Pdf::Forms::PKCS7::PKCS7(const System::SharedPtr<Aspose::Pdf::TimestampSettings> &timestampSettings)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| timestampSettings | const System::SharedPtr\<Aspose::Pdf::TimestampSettings\>\& | La configuración de marca de tiempo para la firma. |
## Observaciones



La configuración de marca de tiempo se usa para crear la firma de marca de tiempo sin necesidad de proporcionar un certificado. Puede establecer la marca de tiempo para un documento como una firma separada.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TimestampSettings](../../../aspose.pdf/timestampsettings/)
* Class [PKCS7](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7::PKCS7(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) constructor


Inicializa una nueva instancia de la clase [PKCS7](../).

```cpp
Aspose::Pdf::Forms::PKCS7::PKCS7(const System::SharedPtr<System::IO::Stream> &pfx, const System::String &password)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pfx | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia con datos del certificado organizados como pfx. |
| password | const System::String\& | Contraseña para obtener acceso a la clave privada del certificado. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [PKCS7](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7::PKCS7(const System::String\&, const System::String\&) constructor


Inicializa una nueva instancia de la clase [PKCS7](../).

```cpp
Aspose::Pdf::Forms::PKCS7::PKCS7(const System::String &pfx, const System::String &password)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pfx | const System::String\& | Archivo pfx que contiene el certificado para firmar. |
| password | const System::String\& | Contraseña del certificado. |
## Observaciones



Contraseña para obtener acceso a la clave privada del certificado.
## Ver también

* Class [String](../../../system/string/)
* Class [PKCS7](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
