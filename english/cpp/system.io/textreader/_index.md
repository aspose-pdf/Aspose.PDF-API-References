---
title: System::IO::TextReader class
linktitle: TextReader
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::TextReader class. A base class for classes that represent readers that read sequences of characters from different sources. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2600
url: /cpp/system.io/textreader/
---
## TextReader class


A base class for classes that represent readers that read sequences of characters from different sources. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class TextReader : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Close](./close/)() | Closes the stream and releases aquired resources. |
| [Dispose](./dispose/)() override | Releases all resources used by the current object and closes the undelying stream. |
| virtual [Peek](./peek/)() | Reads a single character from the stream without changing the stream's read cursor. |
| virtual [Read](./read/)() | Reads a single character from the stream. |
| virtual [Read](./read/)(ArrayPtr\<char_t\>, int, int) | Reads the specified number of characters from the stream and writes them to the specified character array starting at the specified position. |
| virtual [ReadBlock](./readblock/)(ArrayPtr\<char_t\>, int, int) | Reads the specified maximum number of characters from the current text reader and writes the data to a buffer, starting at the specified index. |
| virtual [ReadLine](./readline/)() | Reads characters from the stream until the end of the current line. |
| virtual [ReadToEnd](./readtoend/)() | Reads characters from the stream until the end of the stream. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
