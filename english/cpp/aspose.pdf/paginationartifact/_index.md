---
title: Aspose::Pdf::PaginationArtifact class
linktitle: PaginationArtifact
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PaginationArtifact class. Represents an abstract base class for pagination artifacts in a document in C++.'
type: docs
weight: 14700
url: /cpp/aspose.pdf/paginationartifact/
---
## PaginationArtifact class


Represents an abstract base class for pagination artifacts in a document.

```cpp
class PaginationArtifact : public Aspose::Pdf::Artifact
```

## Methods

| Method | Description |
| --- | --- |
| [get_EndPage](./get_endpage/)() const | Gets the ending page number for the artifact. The value must be greater than or equal to 0. If a value less than 0 is set, it will be adjusted to 0. The default value of 0 means there are no end page boundaries. |
| [get_StartPage](./get_startpage/)() const | Gets the starting page number for the artifact. The value must be greater than or equal to 1. If a value less than 1 is set, it will be adjusted to 1. |
| [get_Subset](./get_subset/)() const | Gets the subset of pages to which the artifact applies (e.g., all pages, even pages, odd pages). |
| [set_EndPage](./set_endpage/)(int32_t) | Sets the ending page number for the artifact. The value must be greater than or equal to 0. If a value less than 0 is set, it will be adjusted to 0. The default value of 0 means there are no end page boundaries. |
| [set_StartPage](./set_startpage/)(int32_t) | Sets the starting page number for the artifact. The value must be greater than or equal to 1. If a value less than 1 is set, it will be adjusted to 1. |
| [set_Subset](./set_subset/)(Aspose::Pdf::Subset) | Sets the subset of pages to which the artifact applies (e.g., all pages, even pages, odd pages). |
## See Also

* Class [Artifact](../artifact/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
