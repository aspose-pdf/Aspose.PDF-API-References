---
title: "Класс XFormPlacement"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Vector.XFormPlacement. Представляет размещение XForm. Если XForm отображается на странице более одного раза, все XFormPlacement, связанные с этим XForm, будут иметь общие графические элементы, но разные графические состояния"
type: docs
weight: 11450
url: /ru/net/aspose.pdf.vector/xformplacement/
---
## XFormPlacement class

Представляет размещение XForm. Если XForm отображается на странице более одного раза, все XformPlacements, связанные с этим XForm, будут иметь общие графические элементы, но разные графические состояния.

```csharp
public sealed class XFormPlacement : GraphicElement
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Elements](../../aspose.pdf.vector/xformplacement/elements/) { get; } | Получает графические элементы внутри этого XForm. |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Получает матрицу графического элемента. Матрица задаётся при создании элемента. Она изменяется при вызове SetPosition(). |
| [Name](../../aspose.pdf.vector/xformplacement/name/) { get; } | Получает имя XForm. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Получает коллекцию операторов, представляющих элемент. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Получает текущий `XFormPlacement`, в котором находится элемент. |
| override [Position](../../aspose.pdf.vector/xformplacement/position/) { set; } |  |
| override [Rectangle](../../aspose.pdf.vector/xformplacement/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Получает страницу, из которой извлекается графический элемент. |
| [XForm](../../aspose.pdf.vector/xformplacement/xform/) { get; } | Получает XForm, связанный с этим XFormPlacement. |

## Методы

| Имя | Описание |
| --- | --- |
| override [AddOnPage](../../aspose.pdf.vector/xformplacement/addonpage/)(Page) | Добавляет текущий элемент на страницу. Если нужно добавить много элементов, лучше использовать [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Освобождает все ресурсы, используемые классом [`GraphicElement`](../graphicelement/). |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Удаляет текущий элемент со страницы. Если нужно удалить много элементов, лучше использовать [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Преобразует элемент в одно SVG‑изображение. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Преобразует элемент в один файл SVG‑изображения. |

### См. также

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


