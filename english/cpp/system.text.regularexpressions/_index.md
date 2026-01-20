---
title: System::Text::RegularExpressions namespace
linktitle: System::Text::RegularExpressions
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::RegularExpressions namespace in C++.'
type: docs
weight: 7100
url: /cpp/system.text.regularexpressions/
---



## Classes

| Class | Description |
| --- | --- |
| [Capture](./capture/) | Result of single subexpression matching. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [CaptureCollection](./capturecollection/) | List of captures done by single capturing group. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [Group](./group/) | Result of matching done by single capturing group. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [GroupCollection](./groupcollection/) | List of capture groups in a single match. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [GroupCollectionPtr](./groupcollectionptr/) | [Group](./group/) collection pointer. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference. |
| [Match](./match/) | [Single](../system/single/) match of regexp over string. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [MatchCollection](./matchcollection/) | Collection of matches done by repeatedly applying regexp to string. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [Regex](./regex/) | Regular expression that follows C#-like syntax. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
## Enums

| Enum | Description |
| --- | --- |
| [RegexOptions](./regexoptions/) | [Regex](./regex/) options. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [CaptureCollectionPtr](./capturecollectionptr/) | Pointer to capture collection. |
| [CapturePtr](./captureptr/) | Pointer to single capture object. |
| [GroupPtr](./groupptr/) | Pointer to group. |
| [MatchCollectionPtr](./matchcollectionptr/) | [Match](./match/) collection pointer. |
| [MatchEvaluator](./matchevaluator/) | Delegate type to evaluate match. |
| [MatchPtr](./matchptr/) | [Match](./match/) pointer. |
| [RegexPtr](./regexptr/) | [Regex](./regex/) pointer. |
| [UStringPtr](./ustringptr/) | Shared UnicodeString to avoid copying. |
