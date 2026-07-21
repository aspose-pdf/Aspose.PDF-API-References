---
title: "Aspose::Pdf::Security::ICustomSecurityHandler::Initialize método"
linktitle: "Initialize"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Security::ICustomSecurityHandler::Initialize método. Llamado para inicializar la instancia actual para la encriptación. Tenga en cuenta que al encriptar, se rellenará con los datos de las propiedades transferidas ICustomSecurityHandler, y al abrir el documento desde el diccionario de encriptación. Si el método se llama durante una nueva encriptación, entonces EncryptionParameters::UserKey y EncryptionParameters::OwnerKey serán nulos en C++."
type: docs
weight: 1200
url: /es/cpp/aspose.pdf.security/icustomsecurityhandler/initialize/
---
## ICustomSecurityHandler::Initialize method


Llamado para inicializar la instancia actual para la encriptación. [Nota](../../../aspose.pdf/note/) que al encriptar, se rellenará con los datos de las propiedades transferidas [ICustomSecurityHandler](../), y al abrir el documento desde el diccionario de encriptación. Si el método se llama durante una nueva encriptación, entonces [EncryptionParameters::UserKey](../) y [EncryptionParameters::OwnerKey](../) serán nulos.

```cpp
virtual void Aspose::Pdf::Security::ICustomSecurityHandler::Initialize(System::SharedPtr<EncryptionParameters> parameters)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parámetros | System::SharedPtr\<EncryptionParameters\> | Los parámetros de encriptación. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EncryptionParameters](../../encryptionparameters/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
