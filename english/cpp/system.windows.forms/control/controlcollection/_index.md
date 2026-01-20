---
title: System::Windows::Forms::Control::ControlCollection class
linktitle: ControlCollection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Windows::Forms::Control::ControlCollection class. Collection of controls. Not implemented in C++.'
type: docs
weight: 200
url: /cpp/system.windows.forms/control/controlcollection/
---
## ControlCollection class


Collection of controls. Not implemented.

```cpp
class ControlCollection : public System::Collections::Generic::IList<System::SharedPtr<Control>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Control\>\&) override | Adds control into collection. |
| virtual [AddRange](./addrange/)(System::ArrayPtr\<System::SharedPtr\<Control\>\>) | Adds several controls into collection. |
| [Clear](./clear/)() override | Deletes all controls from collection. |
| [Contains](./contains/)(const System::SharedPtr\<Control\>\&) const override | Checks if specific control is present in collection. |
| virtual [ContainsKey](./containskey/)(System::String) const | Checks if control with specific name is present in collection. |
| [ControlCollection](./controlcollection/)(const System::SharedPtr\<Control\>\&) | Constructor. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Control\>\>, int) override | Copies collection contents into existing array elements. |
| [Find](./find/)(const System::String\&, bool) const | Looks for the named control in collection. Optionally checks contained controls' collections recursively. |
| [get_Count](./get_count/)() const override | Gets number of controls in collection. |
| [get_Owner](./get_owner/)() const | Gets collection owner control. |
| [GetChildIndex](./getchildindex/)(const System::SharedPtr\<Control\>\&) const | Looks for specific control. |
| virtual [GetChildIndex](./getchildindex/)(const System::SharedPtr\<Control\>\&, bool) const | Looks for specific control. |
| [GetEnumerator](./getenumerator/)() override | Gets enumerator to iterate through collection. |
| [idx_get](./idx_get/)(int) const override | By-index accessor. |
| virtual [idx_get](./idx_get/)(System::String) const | By-name accessor. |
| [idx_set](./idx_set/)(int, System::SharedPtr\<Control\>) override | By-index accessor. |
| virtual [idx_set](./idx_set/)(System::String, System::SharedPtr\<Control\>) | By-name accessor. |
| [IndexOf](./indexof/)(const System::SharedPtr\<Control\>\&) const override | Looks for control in collection. |
| virtual [IndexOfKey](./indexofkey/)(System::String) const | Looks for named control in collection. |
| [Insert](./insert/)(int, const System::SharedPtr\<Control\>\&) override | Inserts control into collection. |
| [Remove](./remove/)(const System::SharedPtr\<Control\>\&) override | Removes control from collection. |
| [RemoveAt](./removeat/)(int) override | Removes control from collection. |
| virtual [RemoveByKey](./removebykey/)(System::String) | Removes control from collection. |
| virtual [SetChildIndex](./setchildindex/)(const System::SharedPtr\<Control\>\&, int) | Moves control to a new position. |
## See Also

* Class [IList](../../../system.collections.generic/ilist/)
* Class [Control](../)
* Namespace [System::Windows::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
