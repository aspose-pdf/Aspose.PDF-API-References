---
title: "Aspose::Pdf::Facades::PdfFileSecurity::TrySetPrivilege método"
linktitle: "TrySetPrivilege"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileSecurity::TrySetPrivilege método. Establece la seguridad del archivo Pdf con la contraseña original. No lanza una excepción si el proceso falla en C++."
type: docs
weight: 1800
url: /es/cpp/aspose.pdf.facades/pdffilesecurity/trysetprivilege/
---
## PdfFileSecurity::TrySetPrivilege method


Establece la seguridad del archivo [Pdf](../../../aspose.pdf/) con la contraseña original. No lanza una excepción si el proceso falla.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::TrySetPrivilege(const System::String &userPassword, const System::String &ownerPassword, const System::SharedPtr<DocumentPrivilege> &privilege)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| userPassword | const System::String\& | Contraseña de usuario original. |
| ownerPassword | const System::String\& | Contraseña de propietario original. |
| privilegio | const System::SharedPtr\\<DocumentPrivilege\\>\\& | Establecer privilegio. |

### ReturnValue

True para éxito, o false.

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../documentprivilege/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
