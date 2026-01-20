---
title: System::Reflection::MethodBase class
linktitle: MethodBase
second_title: Aspose.PDF for C++ API Reference
description: 'System::Reflection::MethodBase class. Base information on method. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 800
url: /cpp/system.reflection/methodbase/
---
## MethodBase class


Base information on method. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class MethodBase : public System::Reflection::MemberInfo
```

## Methods

| Method | Description |
| --- | --- |
| [get_MemberType](./get_membertype/)() const override | Indicating the type of the member - method, constructor, event, and so on. |
| static [GetCurrentMethod](./getcurrentmethod/)(const String\&) | This method allows getting current method name. Translator substitutes ASPOSE_CURRENT_FUNCTION as parameter automatically. |
| [MEMBER_FUNCTION_MAKE_OBJECT](./member_function_make_object/)(MethodBase, CODEPORTING_ARGS(const String\&full_name), CODEPORTING_ARGS(full_name)) |  |
| [MethodBase](./methodbase/)() | Initializes a new instance of the [MethodBase](./) class. |
## See Also

* Class [MemberInfo](../memberinfo/)
* Namespace [System::Reflection](../)
* Library [Aspose.PDF for C++](../../)
