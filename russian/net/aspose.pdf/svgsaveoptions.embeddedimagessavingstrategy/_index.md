---
title: SvgSaveOptions.EmbeddedImagesSavingStrategy
second_title: Aspose.PDF для справочника API .NET
description: Свойству такого типа Вы можете назначить делегата созданного из пользовательского метода который реализует обработку внешнего сохранения изображения которое было извлечено из SVG созданного из PDF и должно быть сохранено как внешний ресурс при преобразовании PDF в HTML. В таком случае обработка например самодельное сохранение в поток или на диск можно выполнить в этом пользовательском коде и этот пользовательский код должен возвращать путь или любую другую строку без кавычек  которая впоследствии будет включена в сгенерированный SVG вместо исходного предполагаемого пути к этот ресурс изображения. В этом случае все необходимые действия по сохранению изображения должны быть выполнены в коде предоставленного метода т.к. сохранение результата в коде конвертера не будет использоваться. Если обработка того или иного файла по какой-то причине должна производиться самим кодом конвертера а не в пользовательском коде установите в пользовательском коде флаг CustomProcessingCancelled переменной параметра imageSavingInfo Сигнализирует конвертеру что выполнены все необходимые действия для обработка этого ресурса должна выполняться в самом конвертере как если бы не было никакого внешнего пользовательского кода . представляет информацию о сохраненном изображении которое можно использовать в пользовательском коде.должна возвращать строку представляющую URL-адрес изображения которое будет помещено в SVG.
type: docs
weight: 6460
url: /ru/net/aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
## SvgSaveOptions.EmbeddedImagesSavingStrategy delegate

Свойству такого типа Вы можете назначить делегата, созданного из пользовательского метода, который реализует обработку внешнего сохранения изображения, которое было извлечено из SVG, созданного из PDF и должно быть сохранено как внешний ресурс при преобразовании PDF в HTML. В таком случае обработка (например, самодельное сохранение в поток или на диск) можно выполнить в этом пользовательском коде, и этот пользовательский код должен возвращать путь (или любую другую строку без кавычек) , которая впоследствии будет включена в сгенерированный SVG вместо исходного предполагаемого пути к этот ресурс изображения. В этом случае все необходимые действия по сохранению изображения должны быть выполнены в коде предоставленного метода, т.к. сохранение результата в коде конвертера не будет использоваться. Если обработка того или иного файла по какой-то причине должна производиться самим кодом конвертера, а не в пользовательском коде, установите в пользовательском коде флаг CustomProcessingCancelled переменной параметра imageSavingInfo Сигнализирует конвертеру, что выполнены все необходимые действия для обработка этого ресурса должна выполняться в самом конвертере, как если бы не было никакого внешнего пользовательского кода . представляет информацию о сохраненном изображении, которое можно использовать в пользовательском коде.должна возвращать строку, представляющую URL-адрес изображения, которое будет помещено в SVG.

```csharp
public delegate string EmbeddedImagesSavingStrategy(SvgImageSavingInfo imageSavingInfo);
```

### Смотрите также

* class [SvgImageSavingInfo](../svgsaveoptions.svgimagesavinginfo)
* class [SvgSaveOptions](../svgsaveoptions)
* пространство имен [Aspose.Pdf](../../aspose.pdf)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->