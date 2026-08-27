---
title: "Класс SubPath"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Vector.SubPath. Представляет векторный графический объект на странице. По сути, векторные графические объекты представлены двумя группами SubPath. Одна из них представлена набором линий и кривых. Другие представлены прямоугольниками и иногда могут быть спутаны. Обычно это прямоугольная область, имеющая цвет, но очень часто этот прямоугольник размещается в начале страницы и определяет всё пространство страницы белым цветом. Таким образом, вы получаете SubPath, но визуально видите только текст на странице."
type: docs
weight: 11410
url: /ru/net/aspose.pdf.vector/subpath/
---
## SubPath class

Представляет объект векторной графики на странице. По сути, объекты векторной графики представлены двумя группами SubPath. Одна из них задаётся набором линий и кривых. Другие представлены прямоугольниками и иногда могут быть спутаны. Обычно это прямоугольная область, имеющая цвет, но очень часто этот прямоугольник размещён в начале страницы и определяет всё пространство страницы белым цветом. Таким образом, вы получаете SubPath, но визуально видите только текст на странице.

```csharp
public sealed class SubPath : GraphicElement
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Получает матрицу графического элемента. Матрица задаётся при создании элемента. Она изменяется при вызове SetPosition(). |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Получает коллекцию операторов, представляющих элемент. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Получает текущий [`XFormPlacement`](../xformplacement/), в котором находится элемент. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Получает или задает позицию в текущем координатном пространстве. Если [`Parent`](../graphicelement/parent/) не !:null, то элемент имеет координатное пространство xForm. |
| override [Rectangle](../../aspose.pdf.vector/subpath/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Получает страницу, из которой извлекается графический элемент. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Добавляет текущий элемент на страницу. Если нужно добавить много элементов, лучше использовать [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Освобождает все ресурсы, используемые классом [`GraphicElement`](../graphicelement/). |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Удаляет текущий элемент со страницы. Если нужно удалить много элементов, лучше использовать [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Преобразует элемент в одно SVG‑изображение. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Преобразует элемент в один файл SVG‑изображения. |

### См. также

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


