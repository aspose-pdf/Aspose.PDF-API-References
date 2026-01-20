---
title: System::Drawing::TextureBrush class
linktitle: TextureBrush
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::TextureBrush class. Represents a brush that uses an image to fill the interior of a shape. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2800
url: /cpp/system.drawing/texturebrush/
---
## TextureBrush class


Represents a brush that uses an image to fill the interior of a shape. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class TextureBrush : public System::Drawing::Brush
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() override | Creates a copy of the current object. |
| [get_Image](./get_image/)() | Returns an image used by the current [TextureBrush](./) object. |
| [get_Transform](./get_transform/)() | Returns a copy of a Matrix object that specifies the geometrical transformations for the brush represneted by the current object. |
| [get_WrapMode](./get_wrapmode/)() | Returns a value that specifies how the brush represented by the current object is tiled. |
| [MultiplyTransform](./multiplytransform/)(const SharedPtr\<Drawing2D::Matrix\>\&, Drawing2D::MatrixOrder) | Multiplies current object's transform matrix by the specified matrix. |
| [ResetTransform](./resettransform/)() | Resets the current object's transform matrix so that it becomes an identity matrix. |
| [RotateTransform](./rotatetransform/)(float, Drawing2D::MatrixOrder) | Rotates the local geometric transformation by the specified angle in the specified order. |
| [ScaleTransform](./scaletransform/)(float, float, Drawing2D::MatrixOrder) | Scales the local geometric transformation by the specified factors in the specified order. |
| [set_Transform](./set_transform/)(const System::SharedPtr\<Drawing2D::Matrix\>\&) | Sets a Matrix object that specifies the geometrical transformations for the brush represneted by the current object. |
| [set_WrapMode](./set_wrapmode/)(Drawing2D::WrapMode) | Sets a value that specifies how the brush represented by the current object is tiled. |
| [TextureBrush](./texturebrush/)(const SharedPtr\<Image\>\&, Drawing2D::WrapMode) | Constructs a new instance of [TextureBrush](./) class that uses the specified image. |
| [TextureBrush](./texturebrush/)(const SharedPtr\<Image\>\&, RectangleF, const SharedPtr\<Imaging::ImageAttributes\>\&) | Constructs a new instance of [TextureBrush](./) class that uses the specified image. |
| [TextureBrush](./texturebrush/)(const SharedPtr\<Image\>\&, Rectangle, const SharedPtr\<Imaging::ImageAttributes\>\&) | Constructs a new instance of [TextureBrush](./) class that uses the specified image. |
| [TextureBrush](./texturebrush/)(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, RectangleF) | Constructs a new instance of [TextureBrush](./) class that uses the specified image. |
| [TextureBrush](./texturebrush/)(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, Rectangle) | Constructs a new instance of [TextureBrush](./) class that uses the specified image. |
| [TranslateTransform](./translatetransform/)(float, float, Drawing2D::MatrixOrder) | Translates the local geometric transformation by the specified dimensions in the specified order. |
| virtual [~TextureBrush](./~texturebrush/)() | Destructor. |
## See Also

* Class [Brush](../brush/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
