---
title: System::Text::RegularExpressions::CaptureCollection class
linktitle: CaptureCollection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::RegularExpressions::CaptureCollection class. List of captures done by single capturing group. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 200
url: /cpp/system.text.regularexpressions/capturecollection/
---
## CaptureCollection class


List of captures done by single capturing group. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class CaptureCollection : public System::Collections::Generic::List<CapturePtr>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const CapturePtr\&) override | Disables collection ammendment. |
| [AddCapture](./addcapture/)(const CapturePtr\&) | Service method to add capture into collection. |
| [Clear](./clear/)() override | Disables cleaning collection. |
| [get_Count](./get_count/)() const override | Gets number of captures. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Marks collection as read-only. |
| [get_IsSynchronized](./get_issynchronized/)() const | Marks collection as unsynchronized. |
| [idx_get](./idx_get/)(int) const override | [Capture](../capture/) accessor. |
| [operator[]](./operator[]/)(int) | [Capture](../capture/) accessor. |
| [operator[]](./operator[]/)(int) const | [Capture](../capture/) accessor. |
| [Remove](./remove/)(const CapturePtr\&) override | Disables collection ammendment. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Base](./base/) | [Base](./base/) type. |
## See Also

* Class [List](../../system.collections.generic/list/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PDF for C++](../../)
