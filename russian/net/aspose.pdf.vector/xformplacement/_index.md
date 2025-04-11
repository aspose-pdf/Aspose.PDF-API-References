---
title: Class XFormPlacement
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Vector.XFormPlacement. Представляет размещение XForm. Если XForm отображается на странице более 1 раза, все XformPlacements, связанные с этим XForm, будут иметь общие графические элементы, но разные графические состояния.
type: docs
weight: 11260
url: /ru/net/aspose.pdf.vector/xformplacement/
---
## XFormPlacement class

Представляет размещение XForm. Если XForm отображается на странице более 1 раза, все XformPlacements, связанные с этим XForm, будут иметь общие графические элементы, но разные графические состояния.

```csharp
public sealed class XFormPlacement : GraphicElement
```

## Properties

| Name | Description |
| --- | --- |
| [Elements](../../aspose.pdf.vector/xformplacement/elements/) { get; } | Получает графические элементы внутри этого XForm. |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Получает матрицу графического элемента. Матрица устанавливается при создании элемента. Она изменяется, когда вызывается SetPosition(). |
| [Name](../../aspose.pdf.vector/xformplacement/name/) { get; } | Получает имя XForm. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Получает коллекцию операторов, представляющих элемент. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Получает текущий `XFormPlacement`, в котором находится элемент. |
| override [Position](../../aspose.pdf.vector/xformplacement/position/) { set; } |  |
| override [Rectangle](../../aspose.pdf.vector/xformplacement/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Получает страницу, из которой извлекается графический элемент. |
| [XForm](../../aspose.pdf.vector/xformplacement/xform/) { get; } | Получает XForm, связанный с этим XFormPlacement. |

## Methods

| Name | Description |
| --- | --- |
| override [AddOnPage](../../aspose.pdf.vector/xformplacement/addonpage/)(Page) | Добавляет текущий элемент на страницу. Если нужно добавить много элементов, лучше использовать [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Освобождает все ресурсы, используемые классом [`GraphicElement`](../graphicelement/). |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Удаляет текущий элемент со страницы. Если нужно удалить много элементов, лучше использовать [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Преобразует элемент в одно изображение SVG. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Преобразует элемент в файл изображения SVG. |

### See Also

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)