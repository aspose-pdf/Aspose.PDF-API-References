---
title: Aspose::Pdf::PasswordType enum
linktitle: PasswordType
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PasswordType enum. This enum represents known password types used for password protected pdf documents in C++.'
type: docs
weight: 25700
url: /cpp/aspose.pdf/passwordtype/
---
## PasswordType enum


This enum represents known password types used for password protected pdf documents.

```cpp
enum class PasswordType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | [Pdf](../) document is not password protected. |
| User | 1 | [Pdf](../) document was opened using document open password (restricted access). |
| Owner | 2 | [Pdf](../) document was opened using change permissions password (full access). |
| Inaccessible | 3 | [Pdf](../) document is password protected but both user and owner passwords are not empty and none of the passwords was defined or supplied password was incorrect. So it impossible to deduce the type of the password. |

## See Also

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
