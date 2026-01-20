---
title: System::Globalization::CultureInfo::GetCultureInfo method
linktitle: GetCultureInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Globalization::CultureInfo::GetCultureInfo method. Gets culture by its name. Same as CreateSpecificCulture in C++.'
type: docs
weight: 4200
url: /cpp/system.globalization/cultureinfo/getcultureinfo/
---
## CultureInfo::GetCultureInfo(const String\&) method


Gets culture by its name. Same as CreateSpecificCulture.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | const String\& | Predefined culture name or existing culture object's name. |

### ReturnValue

Newly created culture object.

## See Also

* Typedef [CultureInfoPtr](../../cultureinfoptr/)
* Class [String](../../../system/string/)
* Class [CultureInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.PDF for C++](../../../)
## CultureInfo::GetCultureInfo(const String\&, const String\&) method


Gets culture by its name.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name, const String &text_and_compare_culture_name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | const String\& | Culture name. |
| text_and_compare_culture_name | const String\& | Culture name used for [TextInfo](../../textinfo/) and [CompareInfo](../../compareinfo/) objects. |

### ReturnValue

Culture object.

## See Also

* Typedef [CultureInfoPtr](../../cultureinfoptr/)
* Class [String](../../../system/string/)
* Class [CultureInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.PDF for C++](../../../)
## CultureInfo::GetCultureInfo(int32_t) method


Gets culture by id.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(int32_t culture)
```


| Parameter | Type | Description |
| --- | --- | --- |
| culture | int32_t | Culture identifier. |

### ReturnValue

Newly created culture object.

## See Also

* Typedef [CultureInfoPtr](../../cultureinfoptr/)
* Class [CultureInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.PDF for C++](../../../)
