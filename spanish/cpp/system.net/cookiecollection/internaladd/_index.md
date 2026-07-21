---
title: "System::Net::CookieCollection::InternalAdd método"
linktitle: "InternalAdd"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::CookieCollection::InternalAdd método. Añade la cookie especificada a la colección en C++."
type: docs
weight: 1000
url: /es/cpp/system.net/cookiecollection/internaladd/
---
## CookieCollection::InternalAdd method


Añade la cookie especificada a la colección.

```cpp
int32_t System::Net::CookieCollection::InternalAdd(System::SharedPtr<Cookie> cookie, bool isStrict)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cookie | System::SharedPtr\<Cookie\> | La cookie a agregar. |
| isStrict | bool | Verdadero cuando la cookie especificada debe reemplazar a la anterior, de lo contrario falso. |

### ReturnValue

0 cuando la cookie especificada reemplazó a la anterior, de lo contrario 1.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Cookie](../../cookie/)
* Class [CookieCollection](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
