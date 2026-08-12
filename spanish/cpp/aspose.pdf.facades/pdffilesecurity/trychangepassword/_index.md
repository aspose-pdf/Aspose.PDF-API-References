---
title: "Aspose::Pdf::Facades::PdfFileSecurity::TryChangePassword método"
linktitle: "TryChangePassword"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileSecurity::TryChangePassword método. Cambia la contraseña de usuario y la contraseña de propietario mediante la contraseña de propietario, mantiene la configuración de seguridad original. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o vacías. La contraseña del propietario será reemplazada con una cadena aleatoria si la nueva contraseña del propietario es nula o vacía. No lanza una excepción si el proceso falla en C++."
type: docs
weight: 1500
url: /es/cpp/aspose.pdf.facades/pdffilesecurity/trychangepassword/
---
## PdfFileSecurity::TryChangePassword(const System::String\&, const System::String\&, const System::String\&) method


Cambia la contraseña de usuario y la contraseña de propietario mediante la contraseña de propietario, mantiene la configuración de seguridad original. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada con una cadena aleatoria si la nueva contraseña de propietario es nula o vacía. No lanza una excepción si el proceso falla.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::TryChangePassword(const System::String &ownerPassword, const System::String &newUserPassword, const System::String &newOwnerPassword)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ownerPassword | const System::String\& | Contraseña original del propietario. |
| newUserPassword | const System::String\& | Nueva contraseña de usuario. |
| newOwnerPassword | const System::String\& | Nueva contraseña de propietario. |

### ReturnValue

Verdadero para éxito, o falso.

## Ver también

* Class [String](../../../system/string/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSecurity::TryChangePassword(const System::String\&, const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize) method


Cambia la contraseña de usuario y la contraseña mediante la contraseña del propietario, permite restablecer la seguridad del documento [Pdf](../../../aspose.pdf/). La nueva contraseña de usuario y la nueva contraseña del propietario pueden ser nulas o vacías. La contraseña del propietario será reemplazada por una cadena aleatoria si la nueva contraseña del propietario es nula o vacía. No lanza una excepción si el proceso falla.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::TryChangePassword(const System::String &ownerPassword, const System::String &newUserPassword, const System::String &newOwnerPassword, const System::SharedPtr<DocumentPrivilege> &privilege, KeySize keySize)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ownerPassword | const System::String\& | Contraseña de propietario original. |
| newUserPassword | const System::String\& | Nueva contraseña de usuario. |
| newOwnerPassword | const System::String\& | Nueva contraseña de propietario. |
| privilegio | const System::SharedPtr\\<DocumentPrivilege\\>\\& | Restablecer seguridad. |
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
## PdfFileSecurity::TryChangePassword(const System::String\&, const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize, Algorithm) method


Cambia la contraseña de usuario y la contraseña mediante la contraseña del propietario, permite restablecer la seguridad del documento [Pdf](../../../aspose.pdf/). La nueva contraseña de usuario y la nueva contraseña del propietario pueden ser nulas o vacías. La contraseña del propietario será reemplazada por una cadena aleatoria si la nueva contraseña del propietario es nula o vacía. Hay 6 combinaciones posibles de valores de [KeySize](../../keysize/) y [Algorithm](../../algorithm/). Sin embargo, ([KeySize.x40](../../keysize/), [Algorithm.AES](../../algorithm/)) y ([KeySize.x256](../../keysize/), [Algorithm.RC4](../../algorithm/)) son inválidas y se lanzará una excepción correspondiente si el kit encuentra esta combinación. No lanza una excepción si el proceso falla.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::TryChangePassword(const System::String &ownerPassword, const System::String &newUserPassword, const System::String &newOwnerPassword, const System::SharedPtr<DocumentPrivilege> &privilege, KeySize keySize, Algorithm cipher)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ownerPassword | const System::String\& | Contraseña de propietario original. |
| newUserPassword | const System::String\& | Nueva contraseña de usuario. |
| newOwnerPassword | const System::String\& | Nueva contraseña de propietario. |
| privilegio | const System::SharedPtr\\<DocumentPrivilege\\>\\& | Restablecer seguridad. |
| keySize | KeySize | [KeySize.x40](../../keysize/) para cifrado de 40 bits, [KeySize.x128](../../keysize/) para cifrado de 128 bits y [KeySize.x256](../../keysize/) para cifrado de 256 bits. |
| cipher | Algorithm | [Algorithm.AES](../../algorithm/) para cifrar usando el algoritmo AES o [Algorithm.RC4](../../algorithm/) para cifrado RC4. |

### ReturnValue

True para éxito, o false.

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../documentprivilege/)
* Enum [KeySize](../../keysize/)
* Enum [Algorithm](../../algorithm/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
