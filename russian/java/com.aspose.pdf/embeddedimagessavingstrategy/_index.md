---
title: SvgSaveOptions.EmbeddedImagesSavingStrategy
second_title: Aspose.PDF для справки по Java API
description: К свойству такого типа можно привязать делегат, созданный из пользовательского метода, реализующего обработку внешнего сохранения изображения, которое было извлечено из SVG, созданного из PDF и которое необходимо сохранить как внешний ресурс при преобразовании PDF в HTML.
type: docs
weight: 12
url: /ru/java/com.aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
```
public static interface SvgSaveOptions.EmbeddedImagesSavingStrategy
```

К свойству такого типа можно привязать делегат, созданный из пользовательского метода, реализующего обработку внешнего сохранения изображения, которое было извлечено из SVG, созданного из PDF и которое необходимо сохранить как внешний ресурс при преобразовании PDF в HTML. В таком случае обработка (например, самодельное сохранение в поток или на диск) может быть выполнена в этом пользовательском коде, и этот пользовательский код должен возвращать путь (или любую другую строку без кавычек), которая впоследствии будет включена в сгенерированный SVG вместо исходного предполагаемого путь к этому ресурсу изображения. В таком случае все необходимые действия по сохранению изображения необходимо произвести в коде предоставленного метода, т.к. сохранение результата в коде конвертера не будет использоваться. Если обработка того или иного файла по каким-либо причинам должна производиться самим кодом конвертера, а не в пользовательском коде, установите в пользовательском коде флаг «CustomProcessingCancelled» переменной параметра «imageSavingInfo». этот ресурс должен быть сделан в самом конвертере, как если бы не было никакого внешнего пользовательского кода.
## Методы

| Метод | Описание |
| --- | --- |
| [invoke(SvgSaveOptions.SvgImageSavingInfo imageSavingInfo)](#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-) |  |
### invoke(SvgSaveOptions.SvgImageSavingInfo imageSavingInfo) {#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-}
```
public abstract String invoke(SvgSaveOptions.SvgImageSavingInfo imageSavingInfo)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageSavingInfo | [SvgImageSavingInfo](../../com.aspose.pdf/svgimagesavinginfo) |  |

**Возвращает:**
java.lang.String