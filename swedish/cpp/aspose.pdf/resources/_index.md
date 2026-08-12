---
title: "Aspose::Pdf::Resources klass"
linktitle: "Resurser"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Resources klass. Klass som representerar sidresurser i C++."
type: docs
weight: 16500
url: /sv/cpp/aspose.pdf/resources/
---
## Resources class


Klass som representerar sidresurser.

```cpp
class Resources : public Aspose::Pdf::ISupportsMemoryCleanup
```

## Nested classes

* Class [ExtGStateValue](./extgstatevalue/)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [cpp_set_xfrom_weak](./cpp_set_xfrom_weak/)(const System::SharedPtr\<XForm\>\&) |  |
| [FreeMemory](./freememory/)() override | Rensar cachad data, frigör minne osv. |
| [get_Fonts](./get_fonts/)() | Hämtar [Fonts](../) resurssamling. |
| [get_Forms](./get_forms/)() | Hämtar [Forms](../../aspose.pdf.forms/) formulärsamling. |
| [get_Images](./get_images/)() | Hämtar [Images](../) bildsamling. |
| [GetExtGStates](./getextgstates/)() | Hämtar alla ExGStates från resurser. |
| [GetFonts](./getfonts/)(bool) | Returnerar teckensnittssamling. Om resurserna inte innehåller teckensnittspost kommer den att skapas beroende på CreateIfAbsent-flaggan. |
## Se även

* Class [ISupportsMemoryCleanup](../isupportsmemorycleanup/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
