---
标题：LoadOptions.ResourceLoadingStrategy
second_title: Aspose.PDF for Java API 参考
描述：有时有必要避免使用图像或 CSS 等外部资源的内部加载器，并提供从某处获取请求资源的自定义方法。
类型：文档
体重：13
网址：/java/com.aspose.pdf/loadoptions.resourceloadingstrategy/
---```
公共静态接口 LoadOptions.ResourceLoadingStrategy
```

Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method, that will get requested resources from somewhere. For example during usage of Aspose.PDf in cloud direct access to referenced files impossible, and some custome code put into special method should be used. This delegate defines signature of such custom method.
## Methods

| Method | Description |
| --- | --- |
| [invoke(String resourceURI)](#invoke-java.lang.String-) |  |
### invoke(String resourceURI) {#invoke-java.lang.String-}
```
公共抽象 LoadOptions.ResourceLoadingResult 调用（字符串 resourceURI）
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resourceURI | java.lang.String |  |

**Returns:**
[ResourceLoadingResult](../../com.aspose.pdf/resourceloadingresult)