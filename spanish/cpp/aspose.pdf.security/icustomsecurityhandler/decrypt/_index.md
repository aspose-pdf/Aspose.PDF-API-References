---
title: "Aspose::Pdf::Security::ICustomSecurityHandler::Decrypt método"
linktitle: "Decrypt"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Security::ICustomSecurityHandler::Decrypt método. Descifre la matriz de datos en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf.security/icustomsecurityhandler/decrypt/
---
## ICustomSecurityHandler::Decrypt method


Desencripte el array de datos.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Pdf::Security::ICustomSecurityHandler::Decrypt(System::ArrayPtr<uint8_t> data, int32_t objectNumber, int32_t generation, System::ArrayPtr<uint8_t> key)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | System::ArrayPtr\<uint8_t\> | Datos a descifrar. |
| objectNumber | int32_t | Número del objeto que contiene los datos cifrados. |
| generation | int32_t | Generación del objeto. |
| clave | System::ArrayPtr\<uint8_t\> | Clave obtenida mediante el método CalculateEncryptionKey |

### ReturnValue

Los datos descifrados.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
