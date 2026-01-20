---
title: System::Drawing::Imaging::Encoder class
linktitle: Encoder
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Imaging::Encoder class. Represents a GUID that is associated with a set of image encoder parameters. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 500
url: /cpp/system.drawing.imaging/encoder/
---
## Encoder class


Represents a GUID that is associated with a set of image encoder parameters. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Encoder : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Encoder](./encoder/)(const Guid\&) | Constructs a new instance of [Encoder](./) class. |
| [get_Guid](./get_guid/)() const | Returns a GUID that specifies a set of image encoder parameters the current object represents. |
## Fields

| Field | Description |
| --- | --- |
| static [ChrominanceTable](./chrominancetable/) | An instance of [Encoder](./) class that represents chrominance table parameter category. |
| static [ColorDepth](./colordepth/) | An instance of [Encoder](./) class that represents the color depth parameter category. |
| static [Compression](./compression/) | An instance of [Encoder](./) class that represents the compression parameter category. |
| static [LuminanceTable](./luminancetable/) | An instance of [Encoder](./) class that represents the luminance table parameter category. |
| static [Quality](./quality/) | An instance of [Encoder](./) class that represents the quality parameter category. |
| static [RenderMethod](./rendermethod/) | An instance of [Encoder](./) class that represents the render method parameter category. |
| static [SaveFlag](./saveflag/) | An instance of [Encoder](./) class that represents the save flag parameter category. |
| static [ScanMethod](./scanmethod/) | An instance of [Encoder](./) class that represents the scan method parameter category. |
| static [Transformation](./transformation/) | An instance of [Encoder](./) class that represents the transformation parameter category. |
| static [Version](./version/) | An instance of [Encoder](./) class that represents the version parameter category. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
