---
title: System::Drawing::Text::FontCollection class
linktitle: FontCollection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Text::FontCollection class. A base class for installed and private font collections. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.drawing.text/fontcollection/
---
## FontCollection class


A base class for installed and private font collections. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class FontCollection : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [Dispose](./dispose/)() override | Releases operating system resources acquired by the current object. |
| virtual [get_Families](./get_families/)() | Returns an array of [FontFamily](../../system.drawing/fontfamily/) objects associated with the font collection represented by the current object. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Drawing::Text](../)
* Library [Aspose.PDF for C++](../../)
