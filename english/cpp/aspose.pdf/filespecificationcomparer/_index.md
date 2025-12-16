---
title: Aspose::Pdf::FileSpecificationComparer class
linktitle: FileSpecificationComparer
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::FileSpecificationComparer class. Represents a comparator class for a file specification. The comparator compares according to the specification, using the list of fields to sort in the collection definition. According to the specification, sorting is done by collection items values. If there is no collection items dictionary, then sorting is done by Params values in C++.'
type: docs
weight: 5800
url: /cpp/aspose.pdf/filespecificationcomparer/
---
## FileSpecificationComparer class


Represents a comparator class for a file specification. The comparator compares according to the specification, using the list of fields to sort in the collection definition. According to the specification, sorting is done by collection items values. If there is no collection items dictionary, then sorting is done by Params values.

```cpp
class FileSpecificationComparer : public System::Collections::Generic::IComparer<System::SharedPtr<FileSpecification>>
```

## Methods

| Method | Description |
| --- | --- |
| [Compare](./compare/)(const System::SharedPtr\<FileSpecification\>\&, const System::SharedPtr\<FileSpecification\>\&) const override | Compares two file specifications according to the collection definition, using the specified sort. |
| [FileSpecificationComparer](./filespecificationcomparer/)(System::SharedPtr\<CollectionSort\>) | Creates a file specification comparer. |
## See Also

* Class [IComparer](../../system.collections.generic/icomparer/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
