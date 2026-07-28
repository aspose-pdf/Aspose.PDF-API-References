---
title: "com.aspose.pdf.vector"
linktitle: "com.aspose.pdf.vector"
second_title: "Справочник API Aspose.PDF для Java"
description: "Aspose.Pdf.Vector является корневым пространством имён для графических операций."
type: docs
weight: 390
url: /ru/java/com.aspose.pdf.vector/
---
Aspose.Pdf.Vector является корневым пространством имён для графических операций.

## Классы

| Класс | Описание |
| --- | --- |
| [GraphicElement](./graphicelement/) | Представляет базовый класс графического объекта на странице. |
| [GraphicElementCollection](./graphicelementcollection/) | Представляет коллекцию {@link GraphicElement}. |
| [GraphicsAbsorber](./graphicsabsorber/) | Представляет объект‑поглотитель графических элементов. Выполняет поиск графики и предоставляет доступ к результатам поиска через коллекцию {@code GraphicsAbsorber.Elements}({@link GraphicsAbsorber#getElements}). |
| [GraphicState](./graphicstate/) | Представляет графическое состояние текущего {@link GraphicElement}. |
| [InternalHelper](./internalhelper/) |  |
| [SubPath](./subpath/) | Представляет объект векторной графики на странице. По сути, объекты векторной графики представлены двумя группами SubPath. Одна из них состоит из набора линий и кривых. Другие представлены в виде прямоугольников и иногда могут быть спутаны. Обычно это прямоугольная область, имеющая цвет, но часто этот прямоугольник размещается в начале страницы и определяет всё пространство страницы белым цветом. Таким образом, вы получаете SubPath, но визуально видите только текст на странице. |
| [XFormPlacement](./xformplacement/) | Представляет размещение XForm. Если XForm отображается на странице более одного раза, все XformPlacements, связанные с этим XForm, будут иметь общие графические элементы, но разные графические состояния. |
