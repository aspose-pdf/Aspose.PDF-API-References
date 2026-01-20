---
title: System::Drawing::Imaging namespace
linktitle: System::Drawing::Imaging
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Drawing::Imaging namespace in C++.'
type: docs
weight: 4200
url: /cpp/system.drawing.imaging/
---



## Classes

| Class | Description |
| --- | --- |
| [BitmapData](./bitmapdata/) | Represents a set of attributes of a bitmap image. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [ColorMap](./colormap/) | Represents a map for converting colors. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [ColorMatrix](./colormatrix/) | Represents a 5x5 matrix that contains the coordinates for the RGBAW color space. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [ColorPalette](./colorpalette/) | Represents a set of 32-bit ARGB colors that make up a color palette. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [Encoder](./encoder/) | Represents a GUID that is associated with a set of image encoder parameters. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [EncoderParameter](./encoderparameter/) | Serves as a container used to pass values to an image encoder. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [EncoderParameters](./encoderparameters/) | Represents an array of [EncoderParameter](./encoderparameter/) objects. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [FrameDimension](./framedimension/) | Provides properties that get the frame dimensions of an image. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [ImageAttributes](./imageattributes/) | Represents information about how image colors are manipulated during rendering. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [ImageCodecInfo](./imagecodecinfo/) | Provides information about an image codec. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [ImageFormat](./imageformat/) | Represents the file format of an image. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [Metafile](./metafile/) | Represents a graphic metafile. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [MetafileHeader](./metafileheader/) | Contains attributes associated with a graphic metafile. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [PropertyItem](./propertyitem/) | Represents a metadata property to be included in an image file. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
## Enums

| Enum | Description |
| --- | --- |
| [ColorAdjustType](./coloradjusttype/) | Specifies which objects use color adjustment information. |
| [ColorChannelFlag](./colorchannelflag/) | Specifies a color channel in CMYK color space. |
| [ColorMatrixFlag](./colormatrixflag/) | Specifies the types of images and colors that will be affected by the color and grayscale adjustment settings of an [ImageAttributes](./imageattributes/) object. |
| [EmfPlusRecordType](./emfplusrecordtype/) | Represents the methods that can be used with a metafile to read and write graphic commands. |
| [EmfType](./emftype/) | Specifies the types of the records that are placed in an EMF file. |
| [EncoderParameterValueType](./encoderparametervaluetype/) | Specifies the type of a value represented by [EncoderParameter](./encoderparameter/) class. |
| [EncoderValue](./encodervalue/) | Specifies the parameter value passed to a JPEG or TIFF image encoder. |
| [ImageFlags](./imageflags/) | Represents attributes of the pixel data represented by an [Image](../system.drawing/image/) object. |
| [ImageLockMode](./imagelockmode/) | Specifies properties of the region of an image being locked. |
| [MetafileFrameUnit](./metafileframeunit/) | Specifies the unit of measurement for the rectangle used to size and position a metafile. |
| [MetafileType](./metafiletype/) | Represents a type of a graphic metafile. |
| [PixelFormat](./pixelformat/) | Specifies the color data format of a pixel. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [BitmapDataPtr](./bitmapdataptr/) | An alias for a shared pointer to an instance of [BitmapData](./bitmapdata/) class. |
| [ColorMapPtr](./colormapptr/) | An alias for a shared pointer to an instance of [ColorMap](./colormap/) class. |
| [ColorMatrixPtr](./colormatrixptr/) | An alias for a shared pointer to an instance of the [ColorMatrix](./colormatrix/) class. |
| [ColorPalettePtr](./colorpaletteptr/) | An alias for a shared pointer to an instance of the [ColorPalette](./colorpalette/) class. |
| [EncoderParameterPtr](./encoderparameterptr/) | An alias for a shared pointer to an instance of [EncoderParameter](./encoderparameter/) class. |
| [EncoderParametersPtr](./encoderparametersptr/) | An alias for a shared pointer to an instance of [EncoderParameters](./encoderparameters/) class. |
| [EncoderPtr](./encoderptr/) | An alias for a shared pointer to an instance of [Encoder](./encoder/) class. |
| [FrameDimensionPtr](./framedimensionptr/) | An alias for a shared pointer to an instance of [FrameDimension](./framedimension/) class. |
| [ImageAttributesPtr](./imageattributesptr/) | An aliast for a shared pointer to an instance of the [ImageAttributes](./imageattributes/) class. |
| [ImageCodecInfoPtr](./imagecodecinfoptr/) | An alias for a shared pointer to an instance of [ImageCodecInfo](./imagecodecinfo/) class. |
| [ImageFormatPtr](./imageformatptr/) | An alias for a shared pointer to an instance of [ImageFormat](./imageformat/) class. |
| [PlayRecordCallback](./playrecordcallback/) | A delegate used as a parameter in EnumerateMetafileProc function object. |
