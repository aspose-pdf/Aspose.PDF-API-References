---
标题：SvgSaveOptions.EmbeddedImagesSavingStrategy
second_title: Aspose.PDF for Java API 参考
描述：对于这种类型的属性您可以分配从自定义方法创建的委托，该方法实现了从 PDF 创建的 SVG 中提取的图像的外部保存处理，并且在将 PDF 转换为 HTML 期间必须将其保存为外部资源。
类型：文档
体重：12
网址：/java/com.aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---```
公共静态接口 SvgSaveOptions.EmbeddedImagesSavingStrategy
```

To property of such type You can assign delegate created from custom method that implements processing of external saving of image that was extracted from SVG created from PDF and must be saved as external resource during conversion of PDF to HTML. In such case processing (like self-made saving into stream or on disk) can be done in that custom code and that custom code must return path(or any another string without quotemarks) that will be afterwards incorporated into generated SVG instead of original supposed path to that image resource. In such case all the necessary actions for saving of image must be undertaken in code of supplied method, because saving of result in code of converter will be not in use. If processing for this or that file for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'imageSavingInfo' parameter's variable It signals to converter that all the necessary steps for processing of that resource must be done in converter itself as if there was no any external custom code .
## Methods

| Method | Description |
| --- | --- |
| [invoke(SvgSaveOptions.SvgImageSavingInfo imageSavingInfo)](#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-) |  |
### invoke(SvgSaveOptions.SvgImageSavingInfo imageSavingInfo) {#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-}
```
公共抽象字符串调用（SvgSaveOptions.SvgImageSavingInfo imageSavingInfo）
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageSavingInfo | [SvgImageSavingInfo](../../com.aspose.pdf/svgimagesavinginfo) |  |

**Returns:**
java.lang.String