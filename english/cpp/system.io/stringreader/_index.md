---
title: System::IO::StringReader class
linktitle: StringReader
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::StringReader class. Represents a reader that reads characters from a string. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2400
url: /cpp/system.io/stringreader/
---
## StringReader class


Represents a reader that reads characters from a string. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StringReader : public System::IO::TextReader
```

## Methods

| Method | Description |
| --- | --- |
| [Close](./close/)() override | Closes the stream. |
| [Dispose](./dispose/)() override | Does nothing. |
| [Dispose](./dispose/)(bool) override | Does nothing. |
| [Peek](./peek/)() override | Reads a single character from the stream without changing the stream's position. |
| [Read](./read/)() override | Reads a single character from the stream. |
| [Read](./read/)(ArrayPtr\<char_t\>, int, int) override | Reads the specified number of characters from the stream to the specified character array starting at the specified position. |
| [ReadLine](./readline/)() override | Reads characters from the stream until the end of the current line. |
| [ReadToEnd](./readtoend/)() override | Reads characters from the stream until the end of the stream. |
| [StringReader](./stringreader/)(const String\&) | Constructs a new instance of [StringReader](./) class that reads characters from the specified string. |
## See Also

* Class [TextReader](../textreader/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
