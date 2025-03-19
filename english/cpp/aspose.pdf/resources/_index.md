---
title: Aspose::Pdf::Resources class
linktitle: Resources
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Resources class. Class representing page resources in C++.'
type: docs
weight: 16100
url: /cpp/aspose.pdf/resources/
---
## Resources class


Class representing page resources.

```cpp
class Resources : public Aspose::Pdf::ISupportsMemoryCleanup
```

## Nested classes

* Class [ExtGStateValue](./extgstatevalue/)
## Methods

| Method | Description |
| --- | --- |
| [cpp_set_xfrom_weak](./cpp_set_xfrom_weak/)(System::SharedPtr\<XForm\>) |  |
| [FreeMemory](./freememory/)() override | Clears cached data, frees memory etc. |
| [get_Fonts](./get_fonts/)() | Gets [Fonts](../) resources collection. |
| [get_Forms](./get_forms/)() | Gets [Forms](../../aspose.pdf.forms/) forms collection. |
| [get_Images](./get_images/)() | Gets [Images](../) images collection. |
| [GetExtGStates](./getextgstates/)() | Gets all ExGStates from resources. |
| [GetFonts](./getfonts/)(bool) | Returns fonts collection. If resources don't contain fonts entry it will be created in depends of CreateIfAbsent flag. |
## See Also

* Class [ISupportsMemoryCleanup](../isupportsmemorycleanup/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
