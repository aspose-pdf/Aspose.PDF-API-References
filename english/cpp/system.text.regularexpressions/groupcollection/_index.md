---
title: System::Text::RegularExpressions::GroupCollection class
linktitle: GroupCollection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::RegularExpressions::GroupCollection class. List of capture groups in a single match. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 400
url: /cpp/system.text.regularexpressions/groupcollection/
---
## GroupCollection class


List of capture groups in a single match. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class GroupCollection : public System::Collections::Generic::List<GroupPtr>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const GroupPtr\&) override | Disables adding element into collection. |
| [AddGroup](./addgroup/)(const GroupPtr\&) | Adds group into collection. |
| [Clear](./clear/)() override | Disables dropping elements from collection. |
| [get_Item](./get_item/)(int) const | [Group](../group/) accessor. |
| [get_Item](./get_item/)(const String\&) const | [Group](../group/) accessor. |
| [GroupCollection](./groupcollection/)(const WeakPtr\<Match\>\&) | Constructor. |
| virtual [idx_get](./idx_get/)(String) const | [Group](../group/) accessor. |
| [idx_get](./idx_get/)(int) const override | [Group](../group/) accessor. |
| [IsReadOnly](./isreadonly/)() const | Marks collection as read-only. |
| [operator[]](./operator[]/)(const String\&) const | [Group](../group/) accessor. |
| [operator[]](./operator[]/)(int) | [Group](../group/) accessor. |
| [operator[]](./operator[]/)(int) const | [Group](../group/) accessor. |
| [Remove](./remove/)(const GroupPtr\&) override | Disables removing element from collection. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Base](./base/) | [Base](./base/) class. |
## See Also

* Class [List](../../system.collections.generic/list/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PDF for C++](../../)
