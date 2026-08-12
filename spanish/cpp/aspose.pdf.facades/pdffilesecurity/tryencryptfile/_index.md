---
title: "Aspose::Pdf::Facades::PdfFileSecurity::TryEncryptFile método"
linktitle: "TryEncryptFile"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileSecurity::TryEncryptFile método. Encripta el archivo Pdf con userpassword y ownerpassword y establece los privilegios del documento para el acceso. La contraseña de usuario y la contraseña del propietario pueden ser nulas o vacías. La contraseña del propietario será reemplazada por una cadena aleatoria si la contraseña del propietario de entrada es nula o vacía. No lanza una excepción si el proceso falla en C++."
type: docs
weight: 1700
url: /es/cpp/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## PdfFileSecurity::TryEncryptFile method


Encripta el archivo [Pdf](../../../aspose.pdf/) con userpassword y ownerpassword y establece los privilegios del documento para el acceso. La contraseña de usuario y la contraseña del propietario pueden ser nulas o vacías. La contraseña del propietario será reemplazada por una cadena aleatoria si la contraseña del propietario de entrada es nula o vacía. No lanza una excepción si el proceso falla.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::TryEncryptFile(const System::String &userPassword, const System::String &ownerPassword, const System::SharedPtr<DocumentPrivilege> &privilege, KeySize keySize)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| userPassword | const System::String\& | Contraseña de usuario. |
| ownerPassword | const System::String\& | Contraseña del propietario. |
| privilegio | const System::SharedPtr\\<DocumentPrivilege\\>\\& | Establecer privilegio. |
| keySize | KeySize | [KeySize.x40](../../keysize/) para cifrado de 40 bits, [KeySize.x128](../../keysize/) para cifrado de 128 bits y [KeySize.x256](../../keysize/) para cifrado de 256 bits. |

### ReturnValue

True para éxito, o false.

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../documentprivilege/)
* Enum [KeySize](../../keysize/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
