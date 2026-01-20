---
title: Aspose::Pdf::AssemblyConstants class
linktitle: AssemblyConstants
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::AssemblyConstants class. Defines the constants that participate in the license check for the component. These used to be defined directly as assembly attributes, but I moved them into separate class because in .NET Compact Framework I cannot access assembly attributes. Now the licensing code when compiled for the .NET Compact Framework uses these constants instead of the assembly attributes in C++.'
type: docs
weight: 500
url: /cpp/aspose.pdf/assemblyconstants/
---
## AssemblyConstants class


Defines the constants that participate in the license check for the component. These used to be defined directly as assembly attributes, but I moved them into separate class because in .NET Compact Framework I cannot access assembly attributes. Now the licensing code when compiled for the .NET Compact Framework uses these constants instead of the assembly attributes.

```cpp
class AssemblyConstants : public System::Object
```

## Fields

| Field | Description |
| --- | --- |
| static [Family](./family/) |  |
| static [Platform](./platform/) |  |
| static [Producer](./producer/) | The producer of the [Pdf](../) file. |
| static [PRODUCT](./product/) |  |
| static [Product](./product/) | This is used by **Aspose** licensing code to verify the license is for the correct product. |
| static [ReleaseDate](./releasedate/) | This is used by **Aspose** licensing code to check for subscription expiry. You need to set this to the date you publish a release or a hotfix. |
| static [Title](./title/) |  |
| static [VERSION](./version/) |  |
| static [Version](./version/) | The version of the assembly. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
