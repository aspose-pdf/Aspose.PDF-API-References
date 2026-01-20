---
title: System::Drawing::ColorTranslator class
linktitle: ColorTranslator
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::ColorTranslator class. Performs color translations. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 600
url: /cpp/system.drawing/colortranslator/
---
## ColorTranslator class


Performs color translations. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ColorTranslator
```

## Methods

| Method | Description |
| --- | --- |
| static [FromHtml](./fromhtml/)(const System::String\&) | Converts the specified HTML color representation to the equvivalent [Color](../color/) object. |
| static [FromWin32](./fromwin32/)(int) | Converts the specified [Windows](../../system.windows/) color to the equvivalent [Color](../color/) object. |
| static [ToHtml](./tohtml/)(const Color\&) | Converts the specified [Color](../color/) object to the string representation of equivalent HTML color. |
## See Also

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
