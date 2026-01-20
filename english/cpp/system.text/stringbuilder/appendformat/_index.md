---
title: System::Text::StringBuilder::AppendFormat method
linktitle: AppendFormat
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::StringBuilder::AppendFormat method. Appends formated string to builder in C++.'
type: docs
weight: 400
url: /cpp/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const SharedPtr\<IFormatProvider\>\&, const String\&, const TArgs\&...) method


Appends formated string to builder.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```


| Parameter | Description |
| --- | --- |
| TArgs | Arguments type. |

| Parameter | Type | Description |
| --- | --- | --- |
| fp | const SharedPtr\<IFormatProvider\>\& | Format provider; ignored. |
| format | const String\& | Format string. |
| args | const TArgs\&... | Arguments to insert into format string positions. |

### ReturnValue

This pointer.

## See Also

* Class [StringBuilder](../)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFormatProvider](../../../system/iformatprovider/)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## StringBuilder::AppendFormat(const String\&, const TArgs\&...) method


Appends formated string to builder.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```


| Parameter | Description |
| --- | --- |
| TArgs | Arguments type. |

| Parameter | Type | Description |
| --- | --- | --- |
| format | const String\& | Format string. |
| args | const TArgs\&... | Arguments to insert into format string positions. |

### ReturnValue

This pointer.

## See Also

* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
