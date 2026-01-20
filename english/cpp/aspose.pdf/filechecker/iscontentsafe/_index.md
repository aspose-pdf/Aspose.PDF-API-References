---
title: Aspose::Pdf::FileChecker::IsContentSafe method
linktitle: IsContentSafe
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::FileChecker::IsContentSafe method. Checks the content of files to identify dangerous content. By checking the content, we do not allow adding dangerous content from a text file via stream in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf/filechecker/iscontentsafe/
---
## FileChecker::IsContentSafe method


Checks the content of files to identify dangerous content. By checking the content, we do not allow adding dangerous content from a text file via stream.

```cpp
static bool Aspose::Pdf::FileChecker::IsContentSafe(System::SharedPtr<System::IO::Stream> stream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | The content stream. |

### ReturnValue

**True** if check passed.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [FileChecker](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
