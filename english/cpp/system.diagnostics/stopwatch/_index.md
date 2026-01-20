---
title: System::Diagnostics::Stopwatch class
linktitle: Stopwatch
second_title: Aspose.PDF for C++ API Reference
description: 'System::Diagnostics::Stopwatch class. Allows time measurement. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 700
url: /cpp/system.diagnostics/stopwatch/
---
## Stopwatch class


Allows time measurement. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Stopwatch : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Elapsed](./get_elapsed/)() const | Gets the total elapsed time measured by the current instance. |
| [get_ElapsedMilliseconds](./get_elapsedmilliseconds/)() const | Gets the total elapsed time measured by the current instance, in milliseconds. |
| [get_ElapsedTicks](./get_elapsedticks/)() const | Gets the total elapsed time measured by the current instance, in timer ticks. |
| [get_IsRunning](./get_isrunning/)() const | Checks if stopwatch is running. |
| [Reset](./reset/)() | Stops time measurement, sets measured interval to zero. |
| [Restart](./restart/)() | Sets measured interval to zero, then starts time measurement. |
| [Start](./start/)() | Starts time measurement. |
| static [StartNew](./startnew/)() | Creates new [Stopwatch](./) object and starts measurement. |
| [Stop](./stop/)() | Stops time measurement. |
| [Stopwatch](./stopwatch/)() | RTTI information. |
| virtual [~Stopwatch](./~stopwatch/)() | Destructor. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PDF for C++](../../)
