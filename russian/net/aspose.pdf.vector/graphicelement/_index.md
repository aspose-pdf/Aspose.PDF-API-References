---
title: "Класс GraphicElement"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Vector.GraphicElement. Представляет базовый класс для графического объекта на странице"
type: docs
weight: 11370
url: /ru/net/aspose.pdf.vector/graphicelement/
---
## GraphicElement class

Представляет базовый класс для графического объекта на странице.

```csharp
public abstract class GraphicElement : IDisposable
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Получает матрицу графического элемента. Матрица задаётся при создании элемента. Она изменяется при вызове SetPosition(). |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Получает коллекцию операторов, представляющих элемент. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Получает текущий [`XFormPlacement`](../xformplacement/), в котором находится элемент. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Получает или задает позицию в текущем координатном пространстве. Если [`Parent`](./parent/) не !:null, то элемент имеет координатное пространство xForm. |
| abstract [Rectangle](../../aspose.pdf.vector/graphicelement/rectangle/) { get; } | Получает ограничивающий прямоугольник `GraphicElement`. |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Получает страницу, из которой извлекается графический элемент. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Добавляет текущий элемент на страницу. Если нужно добавить много элементов, лучше использовать [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Освобождает все ресурсы, используемые классом `GraphicElement`. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Удаляет текущий элемент со страницы. Если нужно удалить много элементов, лучше использовать [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg)() | Преобразует элемент в одно SVG‑изображение. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg_1)(string) | Преобразует элемент в один файл SVG‑изображения. |

### См. также

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


