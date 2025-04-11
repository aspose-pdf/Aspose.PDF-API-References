---
title: Class SubPath
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Vector.SubPath. Представляет объект векторной графики на странице. В основном объекты векторной графики представлены двумя группами SubPaths. Одна из них представлена набором линий и кривых. Другие представлены в виде прямоугольников и иногда могут быть перепутаны. Обычно это прямоугольная область, которая имеет цвет, но очень часто этот прямоугольник располагается в начале страницы и определяет все пространство страницы в белом цвете. Таким образом, вы получаете SubPath, но визуально вы видите только текст на странице.
type: docs
weight: 11220
url: /ru/net/aspose.pdf.vector/subpath/
---
## Класс SubPath

Представляет объект векторной графики на странице. В основном, объекты векторной графики представлены двумя группами SubPaths. Одна из них представлена набором линий и кривых. Другие представлены в виде прямоугольников и иногда могут быть перепутаны. Обычно это прямоугольная область, которая имеет цвет, но очень часто этот прямоугольник располагается в начале страницы и определяет все пространство страницы в белом цвете. Таким образом, вы получаете SubPath, но визуально вы видите только текст на странице.

```csharp
public sealed class SubPath : GraphicElement
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Получает матрицу графического элемента. Матрица устанавливается при создании элемента. Она изменяется, когда вызывается SetPosition(). |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Получает коллекцию операторов, представляющих элемент. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Получает текущий [`XFormPlacement`](../xformplacement/), в котором находится элемент. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Получает или устанавливает позицию в текущем координатном пространстве. Если [`Parent`](../graphicelement/parent/) не !:null, то элемент имеет координатное пространство xForm. |
| override [Rectangle](../../aspose.pdf.vector/subpath/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Получает страницу, из которой извлечен графический элемент. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Добавляет текущий элемент на страницу. Если нужно добавить много элементов, лучше использовать [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Освобождает все ресурсы, используемые классом [`GraphicElement`](../graphicelement/). |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Удаляет текущий элемент со страницы. Если нужно удалить много элементов, лучше использовать [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Преобразует элемент в одно изображение SVG. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Преобразует элемент в один файл изображения SVG. |

### См. также

* класс [GraphicElement](../graphicelement/)
* пространство имен [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* сборка [Aspose.PDF](../../)