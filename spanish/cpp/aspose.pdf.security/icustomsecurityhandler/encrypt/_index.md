---
title: "Aspose::Pdf::Security::ICustomSecurityHandler::Encrypt método"
linktitle: "Cifrar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Security::ICustomSecurityHandler::Encrypt método. Cifre la matriz de datos en C++."
type: docs
weight: 300
url: /es/cpp/aspose.pdf.security/icustomsecurityhandler/encrypt/
---
## ICustomSecurityHandler::Encrypt method


Encripte el array de datos.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Pdf::Security::ICustomSecurityHandler::Encrypt(System::ArrayPtr<uint8_t> data, int32_t objectNumber, int32_t generation, System::ArrayPtr<uint8_t> key)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | System::ArrayPtr\<uint8_t\> | Datos a cifrar. |
| objectNumber | int32_t | Número del objeto que contiene los datos cifrados. |
| generation | int32_t | Generación del objeto. |
| clave | System::ArrayPtr\<uint8_t\> | Clave obtenida mediante el método CalculateEncryptionKey |

### ReturnValue

Los datos encriptados.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
