---
title: "System::Net::Cookie::VerifySetDefaults метод"
linktitle: "VerifySetDefaults"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Cookie::VerifySetDefaults метод. Проверяет и устанавливает значения атрибутов по умолчанию в C++."
type: docs
weight: 4200
url: /ru/cpp/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults method


Проверяет и устанавливает значения атрибутов по умолчанию.

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| variant | CookieVariant | Спецификация cookie. |
| uri | System::SharedPtr\<Uri\> | Экземпляр класса Uri, используемый для инициализации внутренних полей. |
| isLocalDomain | bool | Значение, указывающее, помещён ли cookie в локальный домен. |
| localDomain | String | Имя локального домена. |
| setDefault | bool | Значение, указывающее, должны ли атрибуты cookie инициализироваться значениями по умолчанию. |
| shouldThrow | bool | Значение, указывающее, должно ли быть выброшено исключение, когда указанные значения недействительны. |

### ReturnValue

True, если все значения действительны, иначе false.

## См. также

* Enum [CookieVariant](../../cookievariant/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [Cookie](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
