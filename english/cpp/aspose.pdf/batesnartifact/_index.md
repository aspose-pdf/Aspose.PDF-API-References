---
title: Aspose::Pdf::BatesNArtifact class
linktitle: BatesNArtifact
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::BatesNArtifact class. Class describes Bates Numbering artifact in C++.'
type: docs
weight: 1100
url: /cpp/aspose.pdf/batesnartifact/
---
## BatesNArtifact class


Class describes Bates Numbering artifact.

```cpp
class BatesNArtifact : public Aspose::Pdf::PaginationArtifact
```

## Methods

| Method | Description |
| --- | --- |
| [BatesNArtifact](./batesnartifact/)() | Initializes a new instance of the [BatesNArtifact](./) class. This constructor is internal and creates a header artifact instance with default values. |
| [get_NumberOfDigits](./get_numberofdigits/)() const | Gets the number of digits for Bates numbering. The value must be between 3 and 15 inclusive. If a value less than 3 is set, it will be adjusted to 3. If a value greater than 15 is set, it will be adjusted to 15. The default value is 6. |
| [get_Prefix](./get_prefix/)() const | Gets the prefix to be added to the Bates number. |
| [get_StartNumber](./get_startnumber/)() const | Gets the starting number for Bates numbering. The value must be greater than or equal to 1. If a value less than 1 is set, it will be adjusted to 1. |
| [get_Suffix](./get_suffix/)() const | Gets the suffix to be added to the Bates number. |
| [set_NumberOfDigits](./set_numberofdigits/)(int32_t) | Sets the number of digits for Bates numbering. The value must be between 3 and 15 inclusive. If a value less than 3 is set, it will be adjusted to 3. If a value greater than 15 is set, it will be adjusted to 15. The default value is 6. |
| [set_Prefix](./set_prefix/)(System::String) | Sets the prefix to be added to the Bates number. |
| [set_StartNumber](./set_startnumber/)(int32_t) | Sets the starting number for Bates numbering. The value must be greater than or equal to 1. If a value less than 1 is set, it will be adjusted to 1. |
| [set_Suffix](./set_suffix/)(System::String) | Sets the suffix to be added to the Bates number. |
## See Also

* Class [PaginationArtifact](../paginationartifact/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
