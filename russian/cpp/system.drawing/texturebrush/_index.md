---
title: "Класс System::Drawing::TextureBrush"
linktitle: "TextureBrush"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Drawing::TextureBrush. Представляет кисть, использующую изображение для заполнения внутренней части фигуры. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2800
url: /ru/cpp/system.drawing/texturebrush/
---
## TextureBrush class


Представляет кисть, использующую изображение для заполнения внутренней части фигуры. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class TextureBrush : public System::Drawing::Brush
```

## Методы

| Метод | Описание |
| --- | --- |
| [Clone](./clone/)() override | Создаёт копию текущего объекта. |
| [get_Image](./get_image/)() | Возвращает изображение, используемое текущим объектом [TextureBrush](./). |
| [get_Transform](./get_transform/)() | Возвращает копию объекта Matrix, который задаёт геометрические преобразования для кисти, представленной текущим объектом. |
| [get_WrapMode](./get_wrapmode/)() | Возвращает значение, определяющее способ заполнения (тайлинга) кисти, представленной текущим объектом. |
| [MultiplyTransform](./multiplytransform/)(const SharedPtr\<Drawing2D::Matrix\>\&, Drawing2D::MatrixOrder) | Умножает матрицу преобразования текущего объекта на указанную матрицу. |
| [ResetTransform](./resettransform/)() | Сбрасывает матрицу преобразования текущего объекта, делая её единичной матрицей. |
| [RotateTransform](./rotatetransform/)(float, Drawing2D::MatrixOrder) | Вращает локальное геометрическое преобразование на указанный угол в указанном порядке. |
| [ScaleTransform](./scaletransform/)(float, float, Drawing2D::MatrixOrder) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты в указанном порядке. |
| [set_Transform](./set_transform/)(const System::SharedPtr\<Drawing2D::Matrix\>\&) | Устанавливает объект Matrix, задающий геометрические преобразования для кисти, представленной текущим объектом. |
| [set_WrapMode](./set_wrapmode/)(Drawing2D::WrapMode) | Устанавливает значение, определяющее способ заполнения (тайлинга) кисти, представленной текущим объектом. |
| [TextureBrush](./texturebrush/)(const SharedPtr\<Image\>\&, Drawing2D::WrapMode) | Создаёт новый экземпляр класса [TextureBrush](./), использующий указанное изображение. |
| [TextureBrush](./texturebrush/)(const SharedPtr\<Image\>\&, RectangleF, const SharedPtr\<Imaging::ImageAttributes\>\&) | Создаёт новый экземпляр класса [TextureBrush](./), использующий указанное изображение. |
| [TextureBrush](./texturebrush/)(const SharedPtr\<Image\>\&, Rectangle, const SharedPtr\<Imaging::ImageAttributes\>\&) | Создаёт новый экземпляр класса [TextureBrush](./), использующий указанное изображение. |
| [TextureBrush](./texturebrush/)(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, RectangleF) | Создаёт новый экземпляр класса [TextureBrush](./), использующий указанное изображение. |
| [TextureBrush](./texturebrush/)(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, Rectangle) | Создаёт новый экземпляр класса [TextureBrush](./), использующий указанное изображение. |
| [TranslateTransform](./translatetransform/)(float, float, Drawing2D::MatrixOrder) | Смещает локальное геометрическое преобразование на указанные размеры в указанном порядке. |
| virtual [~TextureBrush](./~texturebrush/)() | Деструктор. |
## См. также

* Class [Brush](../brush/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
