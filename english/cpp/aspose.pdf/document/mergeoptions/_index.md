---
title: Aspose::Pdf::Document::MergeOptions class
linktitle: MergeOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Document::MergeOptions class. Represents the options to Merge methods in C++.'
type: docs
weight: 12700
url: /cpp/aspose.pdf/document/mergeoptions/
---
## MergeOptions class


Represents the options to Merge methods.

```cpp
class MergeOptions : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_ConcatenationPacketSize](./get_concatenationpacketsize/)() const | Number of documents concatenated before new incremental update was made during concatenation when UseDiskBuffer is set to true. The default value is 4. |
| [get_IsNeedPageTreeBalance](./get_isneedpagetreebalance/)() const | Gets and sets the requirement for page tree balancing The entire page tree in the resulting document will be rebalanced. It creates balanced pages tree to speed up pages access. |
| [get_MaximumNodesInLevel](./get_maximumnodesinlevel/)() const | Gets and sets the maximum nodes in pages tree level. Default is 10. |
| [get_UseDiskBuffer](./get_usediskbuffer/)() const | If this option used then destination document will be saved on disk periodically and further concatenation will appllied to it as incremental updates. The default value is **false**. |
| [MergeOptions](./mergeoptions/)() |  |
| [set_ConcatenationPacketSize](./set_concatenationpacketsize/)(int32_t) | Number of documents concatenated before new incremental update was made during concatenation when UseDiskBuffer is set to true. The default value is 4. |
| [set_IsNeedPageTreeBalance](./set_isneedpagetreebalance/)(bool) | Gets and sets the requirement for page tree balancing The entire page tree in the resulting document will be rebalanced. It creates balanced pages tree to speed up pages access. |
| [set_MaximumNodesInLevel](./set_maximumnodesinlevel/)(uint8_t) | Gets and sets the maximum nodes in pages tree level. Default is 10. |
| [set_UseDiskBuffer](./set_usediskbuffer/)(bool) | If this option used then destination document will be saved on disk periodically and further concatenation will appllied to it as incremental updates. The default value is **false**. |
## See Also

* Class [Object](../../../system/object/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
