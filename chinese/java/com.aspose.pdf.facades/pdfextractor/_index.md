---
title: "PdfExtractor"
linktitle: "PdfExtractor"
second_title: "Aspose.PDF for Java API 参考"
description: "用于从 PDF 文档中提取图像和文本的类。"
type: docs
weight: 400
url: /zh/java/com.aspose.pdf.facades/pdfextractor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.PdfExtractor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.PdfExtractor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfExtractor extends Facade
```

用于从 PDF 文档中提取图像和文本的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfExtractor](#PdfExtractor--) | / * / * 绑定用于编辑的 Pdf 文档。 / * / * / * |
| [PdfExtractor](#PdfExtractor-com.aspose.pdf.IDocument-) | / * / * 绑定用于编辑的 Pdf 文档。 / * / * / * |

## 方法

| 方法 | 描述 |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | <p> 从流绑定 PDF 文档。 </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); InputStream stream = new FileInputStream("sample.pdf"); ext.bindPdf(stream); </pre> |
| [bindPdf](#bindPdf-java.lang.String-) | <p> 绑定输入 PDF 文件。 </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindPdf("sample.pdf"); </pre> |
| [extractAttachment](#extractAttachment--) | 从 Pdf 文档中提取附件。 |
| [extractAttachment](#extractAttachment-java.lang.String-) | 从 Pdf 文档中提取附件。 |
| [extractImage](#extractImage--) | <p> 从 PDF 文件中提取图像。 </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.HasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [extractMarkedContentAsImages](#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-) | <p> 获取所有标记内容容器为单独的图像。 </p> <p> 每个标记内容将以 png 格式保存为图像，文件名为 {@code MCID_<ID number of block for the page>.png}</p> |
| [extractText](#extractText--) | <p> 从 Pdf 文档中提取文本。 </p> <hr> <pre> 第一个示例演示如何从 PDF 文件中提取所有文本。 PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\\Text\\text.pdf"); extractor.extractText(); extractor.getText("D:\\Text\\text.txt"); </pre> <p> 第二个示例演示如何将每页的文本提取到一个 txt 文件中。 <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [extractText](#extractText-java.nio.charset.Charset-) | <p> 从 Pdf 文档中提取文本。 </p> <hr> <pre> 第一个示例演示如何从 PDF 文件中提取所有文本。 PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\\Text\\text.pdf"); extractor.extractText(); extractor.getText("D:\\Text\\text.txt"); </pre> <p> 第二个示例演示如何将每页的文本提取到一个 txt 文件中。 <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [extractTextInternal](#extractTextInternal-com.aspose.pdf.TextEncodingInternal-) | 仅供内部使用 |
| [getAttachment](#getAttachment--) | <p> 将所有附件文件保存到流中。 </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre> |
| [getAttachment](#getAttachment-java.lang.String-) | <p> 将所有附件文件保存到流中。 </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre> |
| [getAttachmentInfo](#getAttachmentInfo--) | 获取附件列表。 |
| [getAttachNames](#getAttachNames--) | <p> 返回 PDF 文件中附件的列表。注意：在使用此方法前必须先调用 ExtractAttachments。 </p> <hr> <pre> 示例演示如何从 PDF 文件中提取附件名称。 PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestSettings.GetInputFile("sample.pdf")); extractor.ExtractAttachment(); List attachments = extractor.getAttachNames(); for (String name : {@code (Iterable<String>)}attachments) System.out.println(name); </pre> |
| [getEndPage](#getEndPage--) | <p> 获取将在该页范围内执行提取操作的结束页。 </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre> |
| [getExtractImageMode](#getExtractImageMode--) | <p> 设置图像提取过程的模式。 </p> <hr> 默认值为 ExtractImageMode.DefinedInResources，它提取资源中定义的所有图像。要提取实际显示的图像，应使用 ExtractImageMode.ActuallyUsed 模式。 |
| [getExtractTextMode](#getExtractTextMode--) | <p> 获取文本提取结果的模式。 </p> <hr> <pre> 示例演示在文本提取场景中 {@code ExtractTextMode} 属性的使用。 PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\\Text\\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\\Text\\text.txt"); </pre> <p> 值：0 表示纯文本模式，1 表示原始顺序模式。默认值为 0。</p> |
| [getNextImage](#getNextImage-java.io.OutputStream-) | 检索 PDF 文件中的下一张图像并将其存储到流中。 |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | 检索 PDF 文件中的下一张图像并使用给定的图像格式将其存储到流中。 |
| [getNextImage](#getNextImage-java.lang.String-) | <p> 检索 PDF 文档中的下一张图像。注意：在使用此方法之前必须调用 ExtractImage。 </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | 使用给定的图像格式检索 PDF 文档中的下一张图像。注意：在使用此方法之前必须调用 ExtractImage。 |
| [getNextPageText](#getNextPageText-java.io.OutputStream-) | <p> 将单页文本保存到流中。 </p> <hr> <pre> 示例演示了 {@code GetNextPageText} 方法在文本提取场景中的用法。 PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create); extractor.getNextPageText(fs); fs.close(); pageCount++; } </pre> |
| [getNextPageText](#getNextPageText-java.lang.String-) | <p> 将单页文本保存到文件中。 </p> <hr> <pre> 示例演示了 GetNextPageText 方法在文本提取场景中的用法。 PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + @"Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [getPassword](#getPassword--) | 获取输入文件的密码。 |
| [getResolution](#getResolution--) | 获取已提取图像的分辨率。默认值为 150。分辨率更高的图像更清晰。然而，提高分辨率会导致提取图像所需的时间和内存增加。通常，要获得清晰的图像，分辨率设置为 150 或 300 即可。 |
| [getStartPage](#getStartPage--) | 表示 PDF 文档的 Pdf.Engine 对象。 |
| [getText](#getText-java.io.OutputStream-) | 将文本保存到流中。另请参阅：{@code ExtractText} |
| [getText](#getText-java.io.OutputStream-boolean-) | 将文本保存到流中。另请参阅：{@code ExtractText} |
| [getText](#getText-java.lang.String-) | 将文本保存到文件中。另请参阅：{@code ExtractText} |
| [getTextSearchOptions](#getTextSearchOptions--) | 获取文本搜索选项。 |
| [hasNextImage](#hasNextImage--) | <p> 检查 PDF 文档中是否还有可访问的图像。注意：在使用此方法之前必须调用 ExtractImage。 </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [hasNextPageText](#hasNextPageText--) | <p> 指示是否可以获取更多文本。 </p> <hr> <pre> 示例演示了 {@code HasNextPageText} 属性在文本提取场景中的用法。 PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [isBidi](#isBidi--) | 当文本包含希伯来语或阿拉伯语符号时为 true。此情况必须特别考虑，因为字符串函数的行为会改变，文本处理会从右向左进行（数字和其他非文本字符除外）。 |
| [setEndPage](#setEndPage-int-) | <p> 设置提取操作将在其执行的页面范围的结束页。 </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre> |
| [setExtractImageMode](#setExtractImageMode-com.aspose.pdf.ExtractImageMode-) | <p> 设置图像提取过程的模式。 </p> <hr> 默认值为 ExtractImageMode.DefinedInResources，它提取资源中定义的所有图像。要提取实际显示的图像，应使用 ExtractImageMode.ActuallyUsed 模式。 |
| [setExtractTextMode](#setExtractTextMode-int-) | <p> 设置提取文本结果的模式。 </p> <hr> <pre> 示例演示了 {@code ExtractTextMode} 属性在文本提取场景中的用法。 PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\\Text\\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\\Text\\text.txt"); </pre> 值：0 为纯文本模式，1 为原始顺序模式。默认值为 0。 |
| [setPassword](#setPassword-java.lang.String-) | 设置输入文件的密码。 |
| [setResolution](#setResolution-int-) | 设置已提取图像的分辨率。默认值为 150。分辨率更高的图像更清晰。然而，提高分辨率会导致提取图像所需的时间和内存增加。通常，要获得清晰的图像，分辨率设置为 150 或 300 即可。 |
| [setStartPage](#setStartPage-int-) | <p> 设置提取操作将在其执行的页面范围的起始页。 </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(5); ext.extractText(); </pre> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | 设置文本搜索选项。 |

### PdfExtractor {#PdfExtractor--}
```
public PdfExtractor()
```

/ * / * 绑定用于编辑的 Pdf 文档。 / * / * / *

### PdfExtractor {#PdfExtractor-com.aspose.pdf.IDocument-}
/ * / * 绑定用于编辑的 Pdf 文档。 / * / * / *

### bindPdf {#bindPdf-java.io.InputStream-}
<p> 从流绑定 PDF 文档。 </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); InputStream stream = new FileInputStream("sample.pdf"); ext.bindPdf(stream); </pre>

### bindPdf {#bindPdf-java.lang.String-}
<p> 绑定输入 PDF 文件。 </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindPdf("sample.pdf"); </pre>

### extractAttachment {#extractAttachment--}
```
public void extractAttachment()
```

从 Pdf 文档中提取附件。

### extractAttachment {#extractAttachment-java.lang.String-}
从 Pdf 文档中提取附件。

### extractImage {#extractImage--}
```
public void extractImage()
```

<p> 从 PDF 文件中提取图像。 </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.HasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

### extractMarkedContentAsImages {#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-}
<p> 获取所有标记内容容器为单独的图像。 </p> <p> 每个标记内容将以 png 格式保存为图像，文件名为 {@code MCID_<ID number of block for the page>.png}</p>

### extractText {#extractText--}
```
public void extractText()
```

<p> 从 PDF 文档中提取文本。 </p> <hr> <pre> 第一个示例演示了如何从 PDF 文件中提取所有文本。 PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\Text\text.pdf"); extractor.extractText(); extractor.getText("D:\Text\text.txt"); </pre> <p> 第二个示例演示了如何将每页的文本提取到单独的 txt 文件中。 <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### extractText {#extractText-java.nio.charset.Charset-}
<p> 从 PDF 文档中提取文本。 </p> <hr> <pre> 第一个示例演示了如何从 PDF 文件中提取所有文本。 PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\Text\text.pdf"); extractor.extractText(); extractor.getText("D:\Text\text.txt"); </pre> <p> 第二个示例演示了如何将每页的文本提取到单独的 txt 文件中。 <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### extractTextInternal {#extractTextInternal-com.aspose.pdf.TextEncodingInternal-}
仅供内部使用

### getAttachment {#getAttachment--}
```
public ByteArrayOutputStream [] getAttachment()
```

<p> 将所有附件文件保存到流中。 </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre>

**Returns:**
PDF 文档中附件文件的流数组。

### getAttachment {#getAttachment-java.lang.String-}
<p> 将所有附件文件保存到流中。 </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre>

**Returns:**
PDF 文档中附件文件的流数组。

### getAttachmentInfo {#getAttachmentInfo--}
```
public List < FileSpecification > getAttachmentInfo()
```

获取附件列表。

**Returns:**
返回一个 List<FileSpecificatio>。

### getAttachNames {#getAttachNames--}
```
public List < String > getAttachNames()
```

<p> 返回 PDF 文件中附件的列表。注意：在使用此方法前必须先调用 ExtractAttachments。 </p> <hr> <pre> 示例演示如何从 PDF 文件中提取附件名称。 PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestSettings.GetInputFile("sample.pdf")); extractor.ExtractAttachment(); List attachments = extractor.getAttachNames(); for (String name : {@code (Iterable<String>)}attachments) System.out.println(name); </pre>

**Returns:**
附件列表

### getEndPage {#getEndPage--}
```
public int getEndPage()
```

<p> 获取将在该页范围内执行提取操作的结束页。 </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre>

**Returns:**
结束页。

### getExtractImageMode {#getExtractImageMode--}
```
public ExtractImageMode getExtractImageMode()
```

<p> 设置图像提取过程的模式。 </p> <hr> 默认值为 ExtractImageMode.DefinedInResources，它提取资源中定义的所有图像。要提取实际显示的图像，应使用 ExtractImageMode.ActuallyUsed 模式。

**Returns:**
ExtractImageMode 值 @see ExtractImageMode

### getExtractTextMode {#getExtractTextMode--}
```
public int getExtractTextMode()
```

<p> 获取提取文本结果的模式。 </p> <hr> <pre> 示例演示了在文本提取场景中 {@code ExtractTextMode} 属性的用法。 PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@\"D:\\Text\\text.pdf\"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@\"D:\\Text\\text.txt\"); </pre> <p> 值：0 为纯文本模式，1 为原始顺序模式。默认值为 0.</p>

**Returns:**
提取文本的结果。

### getNextImage {#getNextImage-java.io.OutputStream-}
检索 PDF 文件中的下一张图像并将其存储到流中。

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
检索 PDF 文件中的下一张图像并使用给定的图像格式将其存储到流中。

### getNextImage {#getNextImage-java.lang.String-}
<p> 检索 PDF 文档中的下一张图像。注意：在使用此方法之前必须调用 ExtractImage。 </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
使用给定的图像格式检索 PDF 文档中的下一张图像。注意：在使用此方法之前必须调用 ExtractImage。

### getNextPageText {#getNextPageText-java.io.OutputStream-}
<p> 将单页文本保存到流中。 </p> <hr> <pre> 示例演示了 {@code GetNextPageText} 方法在文本提取场景中的用法。 PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create); extractor.getNextPageText(fs); fs.close(); pageCount++; } </pre>

### getNextPageText {#getNextPageText-java.lang.String-}
<p> 将单页文本保存到文件中。 </p> <hr> <pre> 示例演示了 GetNextPageText 方法在文本提取场景中的用法。 PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + @"Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### getPassword {#getPassword--}
```
public String getPassword()
```

获取输入文件的密码。

**Returns:**
字符串值

### getResolution {#getResolution--}
```
public int getResolution()
```

获取已提取图像的分辨率。默认值为 150。分辨率更高的图像更清晰。然而，提高分辨率会导致提取图像所需的时间和内存增加。通常，要获得清晰的图像，分辨率设置为 150 或 300 即可。

**Returns:**
int 值

### getStartPage {#getStartPage--}
```
public int getStartPage()
```

表示 PDF 文档的 Pdf.Engine 对象。

**Returns:**
页面范围中的起始页。

### getText {#getText-java.io.OutputStream-}
将文本保存到流中。另请参阅：{@code ExtractText}

### getText {#getText-java.io.OutputStream-boolean-}
将文本保存到流中。另请参阅：{@code ExtractText}

### getText {#getText-java.lang.String-}
将文本保存到文件中。另请参阅：{@code ExtractText}

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

获取文本搜索选项。

**Returns:**
文本搜索选项。

### hasNextImage {#hasNextImage--}
```
public boolean hasNextImage()
```

<p> 检查 PDF 文档中是否还有可访问的图像。注意：在使用此方法之前必须调用 ExtractImage。 </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

**Returns:**
如果有更多图像可访问，则为 true。

### hasNextPageText {#hasNextPageText--}
```
public boolean hasNextPageText()
```

<p> 指示是否可以获取更多文本。 </p> <hr> <pre> 示例演示了 {@code HasNextPageText} 属性在文本提取场景中的用法。 PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

**Returns:**
是否可以获取更多文本，true 表示可以，false 表示不可以。

### isBidi {#isBidi--}
```
public boolean isBidi()
```

当文本包含希伯来语或阿拉伯语符号时为 true。此情况必须特别考虑，因为字符串函数的行为会改变，文本处理会从右向左进行（数字和其他非文本字符除外）。

**Returns:**
布尔值

### setEndPage {#setEndPage-int-}
```
public void setEndPage(int value)
```

<p> 设置提取操作将在其执行的页面范围的结束页。 </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 结束页。 |

### setExtractImageMode {#setExtractImageMode-com.aspose.pdf.ExtractImageMode-}
<p> 设置图像提取过程的模式。 </p> <hr> 默认值为 ExtractImageMode.DefinedInResources，它提取资源中定义的所有图像。要提取实际显示的图像，应使用 ExtractImageMode.ActuallyUsed 模式。

### setExtractTextMode {#setExtractTextMode-int-}
```
public void setExtractTextMode(int value)
```

<p> 设置提取文本结果的模式。 </p> <hr> <pre> 示例演示了在文本提取场景中 {@code ExtractTextMode} 属性的用法。 PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@\"D:\\Text\\text.pdf\"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@\"D:\\Text\\text.txt\"); </pre> 值：0 为纯文本模式，1 为原始顺序模式。默认值为 0.

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 提取文本的结果。 |

### setPassword {#setPassword-java.lang.String-}
设置输入文件的密码。

### setResolution {#setResolution-int-}
```
public void setResolution(int value)
```

设置已提取图像的分辨率。默认值为 150。分辨率更高的图像更清晰。然而，提高分辨率会导致提取图像所需的时间和内存增加。通常，要获得清晰的图像，分辨率设置为 150 或 300 即可。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setStartPage {#setStartPage-int-}
```
public void setStartPage(int value)
```

<p> 设置提取操作将在其执行的页面范围的起始页。 </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(5); ext.extractText(); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 页面范围中的起始页。 |

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
设置文本搜索选项。
