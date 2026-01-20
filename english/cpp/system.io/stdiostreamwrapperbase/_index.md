---
title: System::IO::STDIOStreamWrapperBase class
linktitle: STDIOStreamWrapperBase
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::STDIOStreamWrapperBase class. Represents a base class for System.IO.Stream-like wrappers. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2000
url: /cpp/system.io/stdiostreamwrapperbase/
---
## STDIOStreamWrapperBase class


Represents a base class for [System.IO.Stream](../stream/)-like wrappers. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T,typename>class STDIOStreamWrapperBase : public System::IO::Stream
```

## Methods

| Method | Description |
| --- | --- |
| [get_CanRead](./get_canread/)() const override | Determines if the stream supports reading. |
| [get_CanSeek](./get_canseek/)() const override | Determines if the stream supports seeking. |
| [get_CanWrite](./get_canwrite/)() const override | Determines if the stream supports writing. |
| [get_Length](./get_length/)() const override | Returns length of the stream. |
| [get_Position](./get_position/)() const override | Returns current position of the stream. |
| [operator=](./operator=/)(const STDIOStreamWrapperBase\&) | Copy assignment operator. Deleted. |
| [Seek](./seek/)(int64_t, SeekOrigin) override | Sets the position of the stream represented by the current object. |
| [set_Position](./set_position/)(int64_t) override | Sets the stream's position. |
| [STDIOStreamWrapperBase](./stdiostreamwrapperbase/)(const STDIOStreamWrapperBase\&) | Copy constructor. Deleted. |
## Fields

| Field | Description |
| --- | --- |
| static [Null](../stream/null/) | A stream with no underlying storage. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [BaseType](./basetype/) |  |
| [char_type](./char_type/) | RTTI information. |
| [int_type](./int_type/) |  |
| [off_type](./off_type/) |  |
| [pos_type](./pos_type/) |  |
| [ThisType](./thistype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [traits_type](./traits_type/) |  |
## See Also

* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
