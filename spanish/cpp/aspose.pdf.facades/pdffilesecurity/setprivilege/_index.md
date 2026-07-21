---
title: "Aspose::Pdf::Facades::PdfFileSecurity::SetPrivilege método"
linktitle: "SetPrivilege"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileSecurity::SetPrivilege método. Establece la seguridad del archivo Pdf con contraseñas de usuario/propietario vacías. La contraseña del propietario se añadirá mediante una cadena aleatoria. Lanza una excepción si el proceso falla en C++."
type: docs
weight: 1400
url: /es/cpp/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## PdfFileSecurity::SetPrivilege(const System::SharedPtr\<DocumentPrivilege\>\&) method


Establece la seguridad del archivo [Pdf](../../../aspose.pdf/) con contraseñas de usuario/propietario vacías. La contraseña del propietario se añadirá mediante una cadena aleatoria. Lanza una excepción si el proceso falla.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::SetPrivilege(const System::SharedPtr<DocumentPrivilege> &privilege)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| privilegio | const System::SharedPtr\\<DocumentPrivilege\\>\\& | Establecer privilegio. |

### ReturnValue

True para éxito.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../documentprivilege/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSecurity::SetPrivilege(const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&) method


Establece la seguridad del archivo [Pdf](../../../aspose.pdf/) con la contraseña original. Lanza una excepción si el proceso falla.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::SetPrivilege(const System::String &userPassword, const System::String &ownerPassword, const System::SharedPtr<DocumentPrivilege> &privilege)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| userPassword | const System::String\& | Contraseña de usuario original. |
| ownerPassword | const System::String\& | Contraseña de propietario original. |
| privilegio | const System::SharedPtr\\<DocumentPrivilege\\>\\& | Establecer privilegio. |

### ReturnValue

True para éxito.

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../documentprivilege/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
