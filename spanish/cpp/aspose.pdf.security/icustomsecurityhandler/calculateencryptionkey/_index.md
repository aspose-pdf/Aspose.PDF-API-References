---
title: "Aspose::Pdf::Security::ICustomSecurityHandler::CalculateEncryptionKey método"
linktitle: "CalculateEncryptionKey"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Security::ICustomSecurityHandler::CalculateEncryptionKey método. Calcula la EncryptionKey. Generalmente la clave se calcula en base al UserKey. Puedes usar valores de EncryptionParams, que contiene los parámetros actuales en el momento de la llamada. Este valor se pasa como argumento key en Encrypt y Decrypt en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/
---
## ICustomSecurityHandler::CalculateEncryptionKey method


Calcula la EncryptionKey. Generalmente la clave se calcula en base al UserKey. Puedes usar valores de EncryptionParams, que contiene los parámetros actuales en el momento de la llamada. Este valor se pasa como argumento key en [Encrypt](../encrypt/) y [Decrypt](../decrypt/).

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Pdf::Security::ICustomSecurityHandler::CalculateEncryptionKey(System::String password)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| password | System::String | Contraseña introducida por el usuario. |

### ReturnValue

El arreglo de la clave de cifrado.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
