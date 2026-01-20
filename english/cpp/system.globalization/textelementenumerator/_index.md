---
title: System::Globalization::TextElementEnumerator class
linktitle: TextElementEnumerator
second_title: Aspose.PDF for C++ API Reference
description: 'System::Globalization::TextElementEnumerator class. Enumerator to iterate through string elements (characters). Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2700
url: /cpp/system.globalization/textelementenumerator/
---
## TextElementEnumerator class


Enumerator to iterate through string elements (characters). Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class TextElementEnumerator : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Current](./get_current/)() const | Gets the current text element. |
| [get_ElementIndex](./get_elementindex/)() const | Gets index of the current text element. |
| [GetTextElement](./gettextelement/)() const | Gets current element. |
| [MoveNext](./movenext/)() | Moves to the next element. |
| [operator=](./operator=/)(const TextElementEnumerator\&) |  |
| [Reset](./reset/)() | Sets enumerator to initial position. |
| [TextElementEnumerator](./textelementenumerator/)(const TextElementEnumerator\&) |  |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
