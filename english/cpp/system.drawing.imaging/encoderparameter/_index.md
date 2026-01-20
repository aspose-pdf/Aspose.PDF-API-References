---
title: System::Drawing::Imaging::EncoderParameter class
linktitle: EncoderParameter
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Imaging::EncoderParameter class. Serves as a container used to pass values to an image encoder. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 600
url: /cpp/system.drawing.imaging/encoderparameter/
---
## EncoderParameter class


Serves as a container used to pass values to an image encoder. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EncoderParameter : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [EncoderParameter](./encoderparameter/)() | Constructs a new instance of [EncoderParameter](./) class. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, uint8_t, bool) | Constructs a new instance of [EncoderParameter](./) class. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int16_t) | Constructs a new instance of [EncoderParameter](./) class. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int64_t) | Constructs a new instance of [EncoderParameter](./) class. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int32_t) | Constructs a new instance of [EncoderParameter](./) class. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int32_t, int32_t) | Constructs a new instance of [EncoderParameter](./) class that represents a fraction. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int64_t, int64_t) | Constructs a new instance of [EncoderParameter](./) class that represents a range of integer values. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int32_t, int32_t, int32_t, int32_t) | Constructs a new instance of [EncoderParameter](./) class that represents a range of fractions. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const String\&) | Constructs a new instance of [EncoderParameter](./) class. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<uint8_t\>\&, bool) | Constructs a new instance of [EncoderParameter](./) class that represents an array of values. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int16_t\>\&) | Constructs a new instance of [EncoderParameter](./) class that represents an array of values. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int64_t\>\&) | Constructs a new instance of [EncoderParameter](./) class that represents an array of values. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int32_t\>\&, const ArrayPtr\<int32_t\>\&) | Constructs a new instance of [EncoderParameter](./) class that represents an array of fractions. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int64_t\>\&, const ArrayPtr\<int64_t\>\&) | Constructs a new instance of [EncoderParameter](./) class that represents an array of ranges of integers. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int32_t\>\&, const ArrayPtr\<int32_t\>\&, const ArrayPtr\<int32_t\>\&, const ArrayPtr\<int32_t\>\&) | Constructs a new instance of [EncoderParameter](./) class that represents an array of ranges of fractions. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int, EncoderParameterValueType, void *) | Constructs a new instance of [EncoderParameter](./) class that represents the specified number of values of the specified type which are read from the specified buffer. |
| [get_Encoder](./get_encoder/)() const | Returns the [Encoder](../encoder/) object associated with the current [EncoderParameter](./) object. |
| [get_NumberOfValues](./get_numberofvalues/)() const | Returns the number of value represented by the current object. |
| [get_Type](./get_type/)() const | Returns the type of the value(s) represented by the current object. |
| [set_Encoder](./set_encoder/)(const EncoderPtr\&) | Associates the specified [Encoder](../encoder/) object with the current [EncoderParameter](./) object. |
| [~EncoderParameter](./~encoderparameter/)() | Destructor. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
