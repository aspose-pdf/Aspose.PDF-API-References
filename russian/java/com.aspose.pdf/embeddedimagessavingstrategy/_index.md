---
название: SvgSaveOptions.EmbeddedImagesSavingStrategy
second_title: Aspose.PDF для справки по Java API
описание: Свойству такого типа можно назначить делегат, созданный из пользовательского метода, который реализует обработку внешнего сохранения изображения, которое было извлечено из SVG, созданного из PDF и должно быть сохранено как внешний ресурс при преобразовании PDF в HTML.
тип: документы
вес: 12
URL-адрес: /java/com.aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---```
общедоступный статический интерфейс SvgSaveOptions.EmbeddedImagesSavingStrategy
```

To property of such type You can assign delegate created from custom method that implements processing of external saving of image that was extracted from SVG created from PDF and must be saved as external resource during conversion of PDF to HTML. In such case processing (like self-made saving into stream or on disk) can be done in that custom code and that custom code must return path(or any another string without quotemarks) that will be afterwards incorporated into generated SVG instead of original supposed path to that image resource. In such case all the necessary actions for saving of image must be undertaken in code of supplied method, because saving of result in code of converter will be not in use. If processing for this or that file for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'imageSavingInfo' parameter's variable It signals to converter that all the necessary steps for processing of that resource must be done in converter itself as if there was no any external custom code .
## Methods

| Method | Description |
| --- | --- |
| [invoke(SvgSaveOptions.SvgImageSavingInfo imageSavingInfo)](#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-) |  |
### invoke(SvgSaveOptions.SvgImageSavingInfo imageSavingInfo) {#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-}
```
общедоступная абстрактная строка вызова (SvgSaveOptions.SvgImageSavingInfo imageSavingInfo)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageSavingInfo | [SvgImageSavingInfo](../../com.aspose.pdf/svgimagesavinginfo) |  |

**Returns:**
java.lang.String