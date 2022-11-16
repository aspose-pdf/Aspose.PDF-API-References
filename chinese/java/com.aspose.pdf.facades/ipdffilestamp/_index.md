---
标题：IPdfFileStamp
second_title: Aspose.PDF for Java API 参考
描述：为PDF文件添加图章水印或背景的界面。
类型：文档
体重：71
网址：/java/com.aspose.pdf.facades/ipdffilestamp/
---```
公共接口 IPdfFileStamp
```

interface for adding stamps (watermark or background) to PDF files.
## Fields

| Field | Description |
| --- | --- |
| [POS_BOTTOM_LEFT](#POS-BOTTOM-LEFT) | Bottom left position. |
| [POS_BOTTOM_MIDDLE](#POS-BOTTOM-MIDDLE) | Bottom middle position. |
| [POS_BOTTOM_RIGHT](#POS-BOTTOM-RIGHT) | Bottom right position. |
| [POS_SIDES_LEFT](#POS-SIDES-LEFT) | Left position. |
| [POS_SIDES_RIGHT](#POS-SIDES-RIGHT) | Right position. |
| [POS_UPPER_LEFT](#POS-UPPER-LEFT) | Upper let position. |
| [POS_UPPER_MIDDLE](#POS-UPPER-MIDDLE) | Upper middle position. |
| [POS_UPPER_RIGHT](#POS-UPPER-RIGHT) | Right upper position. |
## Methods

| Method | Description |
| --- | --- |
| [addFooter(FormattedText formattedText, float bottomMargin)](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | Adds footer to the pages of the document. |
| [addFooter(FormattedText formattedText, float bottomMargin, float leftMargin, float rightMargin)](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | Adds footer to the pages of the document. |
| [addFooter(InputStream imageStream, float bottomMargin)](#addFooter-java.io.InputStream-float-) | Adds image as footer of the page. |
| [addFooter(InputStream imageStream, float bottomMargin, float leftMargin, float rightMargin)](#addFooter-java.io.InputStream-float-float-float-) | Adds image as footer of the page. |
| [addFooter(String imageFile, float bottomMargin)](#addFooter-java.lang.String-float-) | Adds image as footer to the pages of the document. |
| [addFooter(String imageFile, float bottomMargin, float leftMargin, float rightMargin)](#addFooter-java.lang.String-float-float-float-) | Adds image as footer of the pages. |
| [addHeader(FormattedText formattedText, float topMargin)](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | Adds header to the page. |
| [addHeader(FormattedText formattedText, float topMargin, float leftMargin, float rightMargin)](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | Adds header to the pages of file. |
| [addHeader(InputStream imageStream, float topMargin)](#addHeader-java.io.InputStream-float-) | Adds image as header on the pages. |
| [addHeader(InputStream inputStream, float topMargin, float leftMargin, float rightMargin)](#addHeader-java.io.InputStream-float-float-float-) | Adds image at the top of the page. |
| [addHeader(String imageFile, float topMargin)](#addHeader-java.lang.String-float-) | Adds image as header to the pages of the file. |
| [addHeader(String imageFile, float topMargin, float leftMargin, float rightMargin)](#addHeader-java.lang.String-float-float-float-) | Adds image as header on the pages. |
| [addPageNumber(FormattedText formattedText)](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | Adds page number to the page. |
| [addPageNumber(FormattedText formattedText, float x, float y)](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | Adds page number at the specified position on the page. |
| [addPageNumber(FormattedText formattedText, int position)](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | Adds page number to the pages. |
| [addPageNumber(FormattedText formattedText, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | Adds page number to the pages of document. |
| [addPageNumber(String formatString)](#addPageNumber-java.lang.String-) | Add page number to file. |
| [addPageNumber(String formatString, float x, float y)](#addPageNumber-java.lang.String-float-float-) | Adds page number at the specified position on the page. |
| [addPageNumber(String formatString, int position)](#addPageNumber-java.lang.String-int-) | Adds page number to the pages. |
| [addPageNumber(String formatString, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)](#addPageNumber-java.lang.String-int-float-float-float-float-) | Adds page number to the pages of document. |
| [addStamp(Stamp stamp)](#addStamp-com.aspose.pdf.facades.Stamp-) | Adds stamp to the file. |
| [close()](#close--) | Closes opened files and saves changes. |
| [dispose()](#dispose--) | Closes opened files and saves changes. |
| [getAttachmentName()](#getAttachmentName--) | Gets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [getContentDisposition()](#getContentDisposition--) | Gets how content will be stored when result of operation is stored into HttpResponse object. |
| [getDocument()](#getDocument--) | Gets the document  PdfFileStamp  is working on. |
| [getInputFile()](#getInputFile--) | Gets name and path of input file. |
| [getInputStream()](#getInputStream--) | Gets input stream. |
| [getKeepSecurity()](#getKeepSecurity--) | Keeps security if true. |
| [getOutputFile()](#getOutputFile--) | Gets name and path of output file. |
| [getOutputStream()](#getOutputStream--) | Gets output stream. |
| [getPageHeight()](#getPageHeight--) | Gets height of first page in souorce file. |
| [getPageNumberRotation()](#getPageNumberRotation--) | Gets rotation of page number. |
| [getPageWidth()](#getPageWidth--) | Gets width of first page in input file. |
| [getSaveOptions()](#getSaveOptions--) | Gets save options when result is stored as HttpResponse. |
| [getStartingNumber()](#getStartingNumber--) | Gets or sets starting number for first page in input file. |
| [setAttachmentName(String value)](#setAttachmentName-java.lang.String-) | Sets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [setContentDisposition(int value)](#setContentDisposition-int-) | Sets how content will be stored when result of operation is stored into HttpResponse object. |
| [setConvertTo(PdfFormat value)](#setConvertTo-com.aspose.pdf.PdfFormat-) | Sets PDF file format. |
| [setInputFile(String value)](#setInputFile-java.lang.String-) | Sets name and path of input file. |
| [setInputStream(InputStream value)](#setInputStream-java.io.InputStream-) | Sets input stream. |
| [setKeepSecurity(boolean value)](#setKeepSecurity-boolean-) | Set Keep Security |
| [setOutputFile(String value)](#setOutputFile-java.lang.String-) | Sets name and path of output file. |
| [setOutputStream(OutputStream value)](#setOutputStream-java.io.OutputStream-) | Sets or sets output stream. |
| [setPageNumberRotation(float value)](#setPageNumberRotation-float-) | Sets rotation of page number. |
| [setSaveOptions(SaveOptions value)](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Sets save options when result is stored as HttpResponse. |
| [setStartingNumber(int value)](#setStartingNumber-int-) | Sets starting number for first page in input file. |
### POS_BOTTOM_LEFT {#POS-BOTTOM-LEFT}
```
公共静态最终 int POS_BOTTOM_LEFT
```


Bottom left position.

### POS_BOTTOM_MIDDLE {#POS-BOTTOM-MIDDLE}
```
public static final int POS_BOTTOM_MIDDLE
```


Bottom middle position.

### POS_BOTTOM_RIGHT {#POS-BOTTOM-RIGHT}
```
public static final int POS_BOTTOM_RIGHT
```


Bottom right position.

### POS_SIDES_LEFT {#POS-SIDES-LEFT}
```
公共静态最终 int POS_SIDES_LEFT
```


Left position.

### POS_SIDES_RIGHT {#POS-SIDES-RIGHT}
```
public static final int POS_SIDES_RIGHT
```


Right position.

### POS_UPPER_LEFT {#POS-UPPER-LEFT}
```
公共静态最终 int POS_UPPER_LEFT
```


Upper let position.

### POS_UPPER_MIDDLE {#POS-UPPER-MIDDLE}
```
public static final int POS_UPPER_MIDDLE
```


Upper middle position.

### POS_UPPER_RIGHT {#POS-UPPER-RIGHT}
```
public static final int POS_UPPER_RIGHT
```


Right upper position.

### addFooter(FormattedText formattedText, float bottomMargin) {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
```
public abstract void addFooter(FormattedText formattedText, float bottomMargin)
```


Adds footer to the pages of the document.

--------------------

```
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
 stamp.addFooter(new FormattedText("页脚"), 10);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | FormattedText object which contains text of the footer and text properties. |
| bottomMargin | float | Margin at the top of page. |

### addFooter(FormattedText formattedText, float bottomMargin, float leftMargin, float rightMargin) {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
```
public abstract void addFooter(FormattedText formattedText, float bottomMargin, float leftMargin, float rightMargin)
```


Adds footer to the pages of the document.

--------------------

```
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
 stamp.addFooter(new FormattedText("页脚"), 10, 50, 50);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | FormattedText object which contains footer text and text properties. |
| bottomMargin | float | Margin at the bottom of the page. |
| leftMargin | float | Margin at the left side of the page. |
| rightMargin | float | Margin at the right side of the page. |

### addFooter(InputStream imageStream, float bottomMargin) {#addFooter-java.io.InputStream-float-}
```
public abstract void addFooter(InputStream imageStream, float bottomMargin)
```


Adds image as footer of the page.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("输入.pdf", 输出.pdf");
 fileStamp.addFooter(new FileInputStream("image.jpg"), 50);
 文件戳.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | java.io.InputStream | Stream contains image data. |
| bottomMargin | float | Margin at the bottom of the page. |

### addFooter(InputStream imageStream, float bottomMargin, float leftMargin, float rightMargin) {#addFooter-java.io.InputStream-float-float-float-}
```
public abstract void addFooter(InputStream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```


Adds image as footer of the page.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("输入.pdf", 输出.pdf");
 fileStamp.addFooter(new FileInputStream("image.jpg"), 50, 50, 50);
 文件戳.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | java.io.InputStream | Stream contains image data. |
| bottomMargin | float | Margin at the bottom of the page. |
| leftMargin | float | Margin at the left side of the page. |
| rightMargin | float | Margin at the right side of the page. |

### addFooter(String imageFile, float bottomMargin) {#addFooter-java.lang.String-float-}
```
public abstract void addFooter(String imageFile, float bottomMargin)
```


Adds image as footer to the pages of the document.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("输入.pdf", 输出.pdf");
 fileStamp.addFooter("图片.jpg", 50);
 文件戳.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageFile | java.lang.String | Image file name and path. |
| bottomMargin | float | Margin at the bottom of the page. |

### addFooter(String imageFile, float bottomMargin, float leftMargin, float rightMargin) {#addFooter-java.lang.String-float-float-float-}
```
public abstract void addFooter(String imageFile, float bottomMargin, float leftMargin, float rightMargin)
```


Adds image as footer of the pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageFile | java.lang.String | Iamge file name and path. |
| bottomMargin | float | Margin at the bottom of the page. |
| leftMargin | float | Margin at the left side of the page. |
| rightMargin | float | Margin at the right side of the page. |

### addHeader(FormattedText formattedText, float topMargin) {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
```
public abstract void addHeader(FormattedText formattedText, float topMargin)
```


Adds header to the page.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("输入.pdf", "输出.pdf");
 fileStamp.addHeader(new FormattedText("页眉"), 50);
 文件戳.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | Text for header and properties of the text. |
| topMargin | float | Margin on the top of page. |

### addHeader(FormattedText formattedText, float topMargin, float leftMargin, float rightMargin) {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
```
public abstract void addHeader(FormattedText formattedText, float topMargin, float leftMargin, float rightMargin)
```


Adds header to the pages of file.

--------------------

```
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
 stamp.addHeader(new FormattedText("页眉"), 10, 50, 50);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | Formatted text object which contains page text and its properties. |
| topMargin | float | Margin on the top of the page. |
| leftMargin | float | Margin on the left of the page. |
| rightMargin | float | Margin on the right of the page. |

### addHeader(InputStream imageStream, float topMargin) {#addHeader-java.io.InputStream-float-}
```
public abstract void addHeader(InputStream imageStream, float topMargin)
```


Adds image as header on the pages.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("输入.pdf", 输出.pdf");
 fileStamp.addHeader(new FileInputStream("image.jpg"), 50);
 文件戳.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | java.io.InputStream | Stream of the image. |
| topMargin | float | Margin at top of the page. |

### addHeader(InputStream inputStream, float topMargin, float leftMargin, float rightMargin) {#addHeader-java.io.InputStream-float-float-float-}
```
public abstract void addHeader(InputStream inputStream, float topMargin, float leftMargin, float rightMargin)
```


Adds image at the top of the page.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("输入.pdf", 输出.pdf");
 fileStamp.addHeader(new FileInputStream("image.jpg"), 50, 100, 100);
 文件戳.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Stream which contains image data. |
| topMargin | float | Margin at top of the page. |
| leftMargin | float | Margin at left side of the page. |
| rightMargin | float | Margin at right side of the page. |

### addHeader(String imageFile, float topMargin) {#addHeader-java.lang.String-float-}
```
public abstract void addHeader(String imageFile, float topMargin)
```


Adds image as header to the pages of the file.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("输入.pdf", 输出.pdf");
 fileStamp.addHeader("图片.jpg", 50);
 文件戳.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageFile | java.lang.String | Path to the image file. |
| topMargin | float | Margin at top of the page. |

### addHeader(String imageFile, float topMargin, float leftMargin, float rightMargin) {#addHeader-java.lang.String-float-float-float-}
```
public abstract void addHeader(String imageFile, float topMargin, float leftMargin, float rightMargin)
```


Adds image as header on the pages.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("输入.pdf", 输出.pdf");
 fileStamp.addHeader("图片.jpg", 50, 100, 100);
 文件戳.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageFile | java.lang.String | Path to the image file. |
| topMargin | float | Margin at top of the page. |
| leftMargin | float | Margin at left side of the page. |
| rightMargin | float | Margin at right side of the page. |

### addPageNumber(FormattedText formattedText) {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
```
public abstract void addPageNumber(FormattedText 格式化文本)
```


Adds page number to the page. Page number may contain \# sign which will be replaced with page number. Page number is placed in the bottom of the page centered horizontally.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("输入.pdf", "输出.pdf");
 fileStamp.addPageNumber(new FormattedText("Page #"));
 文件戳.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | Format string for page number representes as FormattedText. |

### addPageNumber(FormattedText formattedText, float x, float y) {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
```
public abstract void addPageNumber(FormattedText formattedText, float x, float y)
```


Adds page number at the specified position on the page.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("输入.pdf", "输出.pdf");
 fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357);
 文件戳.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | Formatted text which represents page number format and properties of the text. Format string can contain \# sign which will be replaced with page number. |
| x | float | X coordinate of page number. |
| y | float | Y coordinate of page number. |

### addPageNumber(FormattedText formattedText, int position) {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
```
public abstract void addPageNumber(FormattedText formattedText, int position)
```


Adds page number to the pages.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("输入.pdf", "输出.pdf");
 fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight);
 文件戳.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | FormattedText object which contains format of the page number and text properties. This text may contain \# which will be replaced with page number. |
| position | int | Position where page number will be placed on the page. 0-bottom middle, 1-bottom right, 2-upper right, 3 - sides right, 4 - upper middle,5 - bottom left,6 - sides left,7 - upper left. You can use the following constants: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### addPageNumber(FormattedText formattedText, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin) {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
```
public abstract void addPageNumber(FormattedText formattedText, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)
```


Adds page number to the pages of document.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("输入.pdf", "输出.pdf");
 fileStamp.addPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
 文件戳.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | FormattedText object which represents page number format and properties iof the text. |
| position | int | Position where page number will be placed on the page. 0-bottom middle, 1-bottom right, 2-upper right, 3 - sides right, 4 - upper middle,5 - bottom left,6 - sides left,7 - upper left. You can use the following constants: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | float | Margin on the left edge of the page. |
| rightMargin | float | Margin on the right edge of the page. |
| topMargin | float | Margin on the top edge of the page. |
| bottomMargin | float | Margin on the bottom edge of the page. |

### addPageNumber(String formatString) {#addPageNumber-java.lang.String-}
```
public abstract void addPageNumber(String formatString)
```


Add page number to file. Page number text may contain \# sign which will be replaced with number of the page. Page number is placed in the bottom of the page centered horizontally.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("输入.pdf", "输出.pdf");
 fileStamp.addPageNumber("页号");
 文件戳.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formatString | java.lang.String | Text of page number |

### addPageNumber(String formatString, float x, float y) {#addPageNumber-java.lang.String-float-float-}
```
public abstract void addPageNumber(String formatString, float x, float y)
```


Adds page number at the specified position on the page.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("输入.pdf", "输出.pdf");
 fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357);
 文件戳.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formatString | java.lang.String | Format string. Format string can contain \# sign which will be replaced with page number. |
| x | float | X coordinate of page number. |
| y | float | Y coordinate of page number. |

### addPageNumber(String formatString, int position) {#addPageNumber-java.lang.String-int-}
```
public abstract void addPageNumber(String formatString, int position)
```


Adds page number to the pages.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("输入.pdf", "输出.pdf");
 fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight);
 文件戳.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formatString | java.lang.String | Format of the page number. This text may contain \# which will be replaced with page number. |
| position | int | Position where page number will be placed on the page. 0-bottom middle, 1-bottom right, 2-upper right, 3 - sides right, 4 - upper middle,5 - bottom left,6 - sides left,7 - upper left. You can use the following constants: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### addPageNumber(String formatString, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin) {#addPageNumber-java.lang.String-int-float-float-float-float-}
```
public abstract void addPageNumber(String formatString, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)
```


Adds page number to the pages of document.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("输入.pdf", "输出.pdf");
 fileStamp.addPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
 文件戳.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formatString | java.lang.String | Format string for page number. |
| position | int | Position where page number will be placed on the page. 0-bottom middle, 1-bottom right, 2-upper right, 3 - sides right, 4 - upper middle,5 - bottom left,6 - sides left,7 - upper left. You can use the following constants: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | float | Margin on the left edge of the page. |
| rightMargin | float | Margin on the right edge of the page. |
| topMargin | float | Margin on the top edge of the page. |
| bottomMargin | float | Margin on the bottom edge of the page. |

### addStamp(Stamp stamp) {#addStamp-com.aspose.pdf.facades.Stamp-}
```
public abstract void addStamp(邮票邮票)
```


Adds stamp to the file.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("输入.pdf", "输出.pdf");
 stamp stamp = new com.aspose.pdf.facades.Stamp();
 stamp.setOrigin(140, 400);
 stamp.setImageSize(50, 50);
 stamp.setOpacity(0.8f);
 stamp.isBackground(true);
 stamp.bindImage("图片.jpg");
 fileStamp.addStamp(邮票);
 文件戳.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stamp | [Stamp](../../com.aspose.pdf.facades/stamp) | Stamp object which. |

### close() {#close--}
```
公共抽象无效关闭（）
```


Closes opened files and saves changes. Warning. If input or output streams are specified they are not closed by Close() method.

--------------------

```
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
 // 做一些工作...
 邮票.close();
```

### dispose() {#dispose--}
```
公共抽象无效处置（）
```


Closes opened files and saves changes. Warning. If input or output streams are specified they are not closed by Close() method.

--------------------

```
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
 // 做一些工作...
 邮票.处置（）；
```

This method is obsolete, use close() instead.

### getAttachmentName() {#getAttachmentName--}
```
公共抽象字符串 getAttachmentName()
```


Gets name of attachment when result of operation is stored into HttpResponse objects as attachment.

**Returns:**
java.lang.String - String value
### getContentDisposition() {#getContentDisposition--}
```
公共抽象 int getContentDisposition()
```


Gets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline.

**Returns:**
int - ContentDisposition element
### getDocument() {#getDocument--}
```
公共抽象 IDocument getDocument()
```


Gets the document  PdfFileStamp  is working on.

**Returns:**
[IDocument](../../com.aspose.pdf/idocument) - IDocument object
### getInputFile() {#getInputFile--}
```
公共抽象字符串 getInputFile()
```


Gets name and path of input file.

**Returns:**
java.lang.String - String object
### getInputStream() {#getInputStream--}
```
公共抽象输入流 getInputStream()
```


Gets input stream.

**Returns:**
java.io.InputStream - InputStream object
### getKeepSecurity() {#getKeepSecurity--}
```
公共抽象布尔值 getKeepSecurity()
```


Keeps security if true. (This feature will be implemented in next versions).

**Returns:**
boolean - boolean value
### getOutputFile() {#getOutputFile--}
```
公共抽象字符串 getOutputFile()
```


Gets name and path of output file.

**Returns:**
java.lang.String - String object
### getOutputStream() {#getOutputStream--}
```
公共抽象 OutputStream getOutputStream()
```


Gets output stream.

**Returns:**
java.io.OutputStream - OutputStream object
### getPageHeight() {#getPageHeight--}
```
公共抽象浮动 getPageHeight()
```


Gets height of first page in souorce file.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("输入.pdf", "输出.pdf");
 System.out.println("Height = " + fileStamp.getPageHeight());
 文件戳.close();
```

**Returns:**
float - float value
### getPageNumberRotation() {#getPageNumberRotation--}
```
公共抽象浮动 getPageNumberRotation()
```


Gets rotation of page number. Rotation is in degrees. Default is 0.

**Returns:**
float - float value
### getPageWidth() {#getPageWidth--}
```
公共抽象浮动 getPageWidth()
```


Gets width of first page in input file.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("输入.pdf", "输出.pdf");
 System.out.println("宽度 = " + fileStamp.getPageWidth());
 文件戳.close();
```

**Returns:**
float - float value
### getSaveOptions() {#getSaveOptions--}
```
公共抽象保存选项 getSaveOptions()
```


Gets save options when result is stored as HttpResponse. Default value: PdfSaveOptions.

**Returns:**
[SaveOptions](../../com.aspose.pdf/saveoptions) - SaveOptions object
### getStartingNumber() {#getStartingNumber--}
```
公共抽象 int getStartingNumber()
```


Gets or sets starting number for first page in input file. Next pages will be numbered starting from this value.

**Returns:**
int - int value
### setAttachmentName(String value) {#setAttachmentName-java.lang.String-}
```
公共抽象无效 setAttachmentName（字符串值）
```


Sets name of attachment when result of operation is stored into HttpResponse objects as attachment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setContentDisposition(int value) {#setContentDisposition-int-}
```
公共抽象无效 setContentDisposition（int 值）
```


Sets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ContentDisposition element |

### setConvertTo(PdfFormat value) {#setConvertTo-com.aspose.pdf.PdfFormat-}
```
公共抽象无效 setConvertTo（PdfFormat 值）
```


Sets PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfFormat](../../com.aspose.pdf/pdfformat) | PdfFormat element |

### setInputFile(String value) {#setInputFile-java.lang.String-}
```
公共抽象无效 setInputFile（字符串值）
```


Sets name and path of input file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setInputStream(InputStream value) {#setInputStream-java.io.InputStream-}
```
public abstract void setInputStream(InputStream 值)
```


Sets input stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream | InputStream object |

### setKeepSecurity(boolean value) {#setKeepSecurity-boolean-}
```
公共抽象无效 setKeepSecurity（布尔值）
```


Set Keep Security

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setOutputFile(String value) {#setOutputFile-java.lang.String-}
```
公共抽象无效 setOutputFile（字符串值）
```


Sets name and path of output file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### setOutputStream(OutputStream value) {#setOutputStream-java.io.OutputStream-}
```
public abstract void setOutputStream(OutputStream 值)
```


Sets or sets output stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.OutputStream | OutputStream object |

### setPageNumberRotation(float value) {#setPageNumberRotation-float-}
```
公共抽象无效 setPageNumberRotation（浮动值）
```


Sets rotation of page number. Rotation is in degrees. Default is 0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### setSaveOptions(SaveOptions value) {#setSaveOptions-com.aspose.pdf.SaveOptions-}
```
公共抽象无效 setSaveOptions（SaveOptions 值）
```


Sets save options when result is stored as HttpResponse. Default value: PdfSaveOptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SaveOptions](../../com.aspose.pdf/saveoptions) | SaveOptions value |

### setStartingNumber(int value) {#setStartingNumber-int-}
```
公共抽象无效 setStartingNumber（int 值）
```


Sets starting number for first page in input file. Next pages will be numbered starting from this value. For example if StartingNumber is set to 100, document pages will have numbers 100, 101, 102...

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("输入.pdf", "输出.pdf");
 fileStamp.setStartingNumber(100);
 fileStamp.addPageNumber("页号");
 文件戳.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |
