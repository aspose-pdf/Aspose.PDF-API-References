---
title: System::IO::STDIOStreamPositionPreference enum
linktitle: STDIOStreamPositionPreference
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::STDIOStreamPositionPreference enum. Determines which position in the stream is preferable as a common read and write position when std::basic_iostream and its descendants will have different read and write positions at the time of wrapper creation in C++.'
type: docs
weight: 3600
url: /cpp/system.io/stdiostreampositionpreference/
---
## STDIOStreamPositionPreference enum


Determines which position in the stream is preferable as a common read and write position when std::basic_iostream and its descendants will have different read and write positions at the time of wrapper creation.

```cpp
enum class STDIOStreamPositionPreference
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Zero | 0 | Zero position will sets as a read and write position. |
| ReadPosition | 1 | gptr position will sets as a read and write position. |
| WritePosition | 2 | pptr position will sets as a read and write position. |

## See Also

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
