---
title: PdfAnnotationEditor
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示用于处理 PDF 文档注释注释的类。
type: docs
weight: 34
url: /zh/java/com.aspose.pdf.facades/pdfannotationeditor/
---
**遗产：**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)
```
public final class PdfAnnotationEditor extends SaveableFacade
```

表示用于处理 PDF 文档注释（注释）的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfAnnotationEditor()](#PdfAnnotationEditor--) | 初始化新的 PdfAnnotationEditor 对象。 |
| [PdfAnnotationEditor(IDocument document)](#PdfAnnotationEditor-com.aspose.pdf.IDocument-) | 在文档的基础上初始化新的 PdfAnnotationEditor 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | 初始化门面。 |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | 初始化门面。 |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | 初始化门面。 |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | 初始化门面。 |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | 初始化门面。 |
| [close()](#close--) | 处理与外观绑定的文档。 |
| [deleteAnnotation(String annotName)](#deleteAnnotation-java.lang.String-) | 删除具有指定注释名称的注释。 |
| [deleteAnnotations()](#deleteAnnotations--) | 删除文档中的所有注释。 |
| [deleteAnnotations(String annotType)](#deleteAnnotations-java.lang.String-) | 删除文档中指定类型的所有注释。 |
| [dispose()](#dispose--) | 处理门面。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportAnnotationsToXfdf(OutputStream xmlOutputStream)](#exportAnnotationsToXfdf-java.io.OutputStream-) | 将注释导出到流。 |
| [exportAnnotationsXfdf(OutputStream xmlOutputStream, int start, int end, int[] annotTypes)](#exportAnnotationsXfdf-java.io.OutputStream-int-int-int---) | 将指定注释类型的内容导出到 XFDF |
| [exportAnnotationsXfdf(OutputStream xmlOutputStream, int start, int end, String[] annotTypes)](#exportAnnotationsXfdf-java.io.OutputStream-int-int-java.lang.String---) | 将指定注释类型的内容导出到 XFDF |
| [extractAnnotations(int start, int end, int[] annotTypes)](#extractAnnotations-int-int-int---) | 获取指定类型的注解列表。 |
| [extractAnnotations(int start, int end, String[] annotTypes)](#extractAnnotations-int-int-java.lang.String---) | 获取指定类型的注解列表。 |
| [flatteningAnnotations()](#flatteningAnnotations--) | 展平文档中的所有注释。 |
| [flatteningAnnotations(Form.FlattenSettings flattenSettings)](#flatteningAnnotations-com.aspose.pdf.Form.FlattenSettings-) | 展平文档中的所有注释。 |
| [flatteningAnnotations(int start, int end, int[] annotType)](#flatteningAnnotations-int-int-int---) | 展平指定类型的注解。 |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | 获取正在处理的文档外观。 |
| [hashCode()](#hashCode--) |  |
| [importAnnotationFromXfdf(InputStream xfdfStream)](#importAnnotationFromXfdf-java.io.InputStream-) | 从 XFDF 数据流导入所有注释。 |
| [importAnnotationFromXfdf(String xfdfFile)](#importAnnotationFromXfdf-java.lang.String-) | 从 XFDF 文件导入所有注释。 |
| [importAnnotations(InputStream[] annotFileInputStream)](#importAnnotations-java.io.InputStream---) | 从另一个 PDF 文档流的数组中将注释导入文档。 |
| [importAnnotations(InputStream[] annotFileInputStream, int[] annotType)](#importAnnotations-java.io.InputStream---int---) | 从另一个 PDF 文档流的数组中将指定的注释导入到文档中。 |
| [importAnnotations(String[] annotFile)](#importAnnotations-java.lang.String---) | 从另一个 PDF 文档的数组中将注释导入文档。 |
| [importAnnotations(String[] annotFile, int[] annotType)](#importAnnotations-java.lang.String---int---) | 从另一个 PDF 文档的数组中将指定的注释导入到文档中。 |
| [importAnnotationsFromXfdf(InputStream xfdfSteam)](#importAnnotationsFromXfdf-java.io.InputStream-) | 从 XFDF 数据流导入所有注释。 |
| [importAnnotationsFromXfdf(InputStream xfdfStream, int[] annotType)](#importAnnotationsFromXfdf-java.io.InputStream-int---) | 从 XFDF 数据流中导入指定的注释。 |
| [importAnnotationsFromXfdf(String xfdfFile)](#importAnnotationsFromXfdf-java.lang.String-) | 从 XFDF 文件导入所有注释。 |
| [importAnnotationsFromXfdf(String xfdfFile, int[] annotType)](#importAnnotationsFromXfdf-java.lang.String-int---) | 从 XFDF 文件导入指定的注释。 |
| [modifyAnnotations(int start, int end, Annotation annotation)](#modifyAnnotations-int-int-com.aspose.pdf.Annotation-) | 修改指定页面范围内指定类型的注释。 |
| [modifyAnnotations(int start, int end, int annotType, Annotation annotation)](#modifyAnnotations-int-int-int-com.aspose.pdf.Annotation-) | “改用 modifyAnnotations(int start, int end, Annotation annotation)。” |
| [modifyAnnotationsAuthor(int start, int end, String srcAuthor, String desAuthor)](#modifyAnnotationsAuthor-int-int-java.lang.String-java.lang.String-) | 修改指定页面范围内注释的作者。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [redactArea(int pageIndex, Rectangle rect, Color color)](#redactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-) | 编辑指定页面上的区域。 |
| [redactExactArea(int pageIndex, Rectangle rect, Color color)](#redactExactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-) | 编辑指定页面上的区域。 |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | 将结果 PDF 保存到流中。 |
| [save(String outputFile)](#save-java.lang.String-) | 将结果 PDF 保存到文件。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfAnnotationEditor() {#PdfAnnotationEditor--}
```
public PdfAnnotationEditor()
```


初始化新的 PdfAnnotationEditor 对象。

### PdfAnnotationEditor(IDocument document) {#PdfAnnotationEditor-com.aspose.pdf.IDocument-}
```
public PdfAnnotationEditor(IDocument document)
```


在文档的基础上初始化新的 PdfAnnotationEditor 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | pdf文档。 |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | 文档对象。 |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream srcStream)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | PDF文件流。 |

### bindPdf(InputStream srcStream, String password) {#bindPdf-java.io.InputStream-java.lang.String-}
```
public void bindPdf(InputStream srcStream, String password)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | PDF文件流。 |
| password | java.lang.String | PDF文档的密码。 |

### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String srcFile)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFile | java.lang.String | PDF文件。 |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFile | java.lang.String | PDF文件 |
| password | java.lang.String | PDF文档的密码。 |

### close() {#close--}
```
public void close()
```


处理与外观绑定的文档。

### deleteAnnotation(String annotName) {#deleteAnnotation-java.lang.String-}
```
public void deleteAnnotation(String annotName)
```


删除具有指定注释名称的注释。

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.deleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38");
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| annotName | java.lang.String | 注释名称 |

### deleteAnnotations() {#deleteAnnotations--}
```
public void deleteAnnotations()
```


删除文档中的所有注释。

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.deleteAnnotations();
 editor.save("example_out.pdf");
```

### deleteAnnotations(String annotType) {#deleteAnnotations-java.lang.String-}
```
public void deleteAnnotations(String annotType)
```


删除文档中指定类型的所有注释。

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.deleteAnnotations("Text");
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| annotType | java.lang.String | 注释类型将被删除。 |

### dispose() {#dispose--}
```
public void dispose()
```


处理门面。

此方法已过时，请改用 close() 。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### exportAnnotationsToXfdf(OutputStream xmlOutputStream) {#exportAnnotationsToXfdf-java.io.OutputStream-}
```
public final void exportAnnotationsToXfdf(OutputStream xmlOutputStream)
```


将注释导出到流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xmlOutputStream | java.io.OutputStream | OutputStream 实例（输出流） |

### exportAnnotationsXfdf(OutputStream xmlOutputStream, int start, int end, int[] annotTypes) {#exportAnnotationsXfdf-java.io.OutputStream-int-int-int---}
```
public void exportAnnotationsXfdf(OutputStream xmlOutputStream, int start, int end, int[] annotTypes)
```


将指定注释类型的内容导出到 XFDF

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight};
 OutputStream stream = new FileOutputStream("example.xfdf");
     editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes);
 stream.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xmlOutputStream | java.io.OutputStream | 输出 XFDF 流。 |
| start | int | 将从中导出文档注释的起始页。 |
| end | int | 文档注释将导出到的结束页面。 |
| annotTypes | int[] | 需要导出注释类型数组。 |

### exportAnnotationsXfdf(OutputStream xmlOutputStream, int start, int end, String[] annotTypes) {#exportAnnotationsXfdf-java.io.OutputStream-int-int-java.lang.String---}
```
public void exportAnnotationsXfdf(OutputStream xmlOutputStream, int start, int end, String[] annotTypes)
```


将指定注释类型的内容导出到 XFDF

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 String[] annotTypes = new String[] {"Text", "Highlight"};
 OutputStream stream = new FileOutputStream("example.xfdf");
 editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes);
 stream.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xmlOutputStream | java.io.OutputStream | 输出 XFDF 流。 |
| start | int | 将从中导出文档注释的起始页。 |
| end | int | 文档注释将导出到的结束页面。 |
| annotTypes | java.lang.String[] | 需要导出注释类型数组。 |

### extractAnnotations(int start, int end, int[] annotTypes) {#extractAnnotations-int-int-int---}
```
public List<Annotation> extractAnnotations(int start, int end, int[] annotTypes)
```


获取指定类型的注解列表。

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight};
 List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| start | int | 从中选择注释的起始页。 |
| end | int | 将选择注释的结束页面。 |
| annotTypes | int[] | 所需注释类型的数组。 |

**退货：**
java.util.List<com.aspose.pdf.Annotation> - 注释列表。
### extractAnnotations(int start, int end, String[] annotTypes) {#extractAnnotations-int-int-java.lang.String---}
```
public List<Annotation> extractAnnotations(int start, int end, String[] annotTypes)
```


获取指定类型的注解列表。

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 String[] annotTypes = new String[] {"Text", "Highlight"};
 List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| start | int | 从中选择注释的起始页。 |
| end | int | 将选择注释的结束页面。 |
| annotTypes | java.lang.String[] | 所需注释类型的数组。 |

**退货：**
java.util.List<com.aspose.pdf.Annotation> - 注释列表。
### flatteningAnnotations() {#flatteningAnnotations--}
```
public void flatteningAnnotations()
```


展平文档中的所有注释。

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.flatteningAnnotations();
 editor.save(example_out.pdf");
```

### flatteningAnnotations(Form.FlattenSettings flattenSettings) {#flatteningAnnotations-com.aspose.pdf.Form.FlattenSettings-}
```
public final void flatteningAnnotations(Form.FlattenSettings flattenSettings)
```


展平文档中的所有注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| flattenSettings | [FlattenSettings](../../com.aspose.pdf/flattensettings) | 指定展平模式。 |

### flatteningAnnotations(int start, int end, int[] annotType) {#flatteningAnnotations-int-int-int---}
```
public void flatteningAnnotations(int start, int end, int[] annotType)
```


展平指定类型的注解。

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 int[] annotTypes ={AnnotationType.Line, AnnotationType.FreeText};
 editor.flatteningAnnotations(1, 2, annotTypes);
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| start | int | 起始页。 |
| end | int | 然后结束页。 |
| annotType | int[] | 注释类型应该被展平。 |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


获取正在处理的文档外观。

**退货：**
[IDocument](../../com.aspose.pdf/idocument) IDocument 元素
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### importAnnotationFromXfdf(InputStream xfdfStream) {#importAnnotationFromXfdf-java.io.InputStream-}
```
public final void importAnnotationFromXfdf(InputStream xfdfStream)
```


从 XFDF 数据流导入所有注释。

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf"));
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xfdfStream | java.io.InputStream | 输入 XFDF 数据流。 |

### importAnnotationFromXfdf(String xfdfFile) {#importAnnotationFromXfdf-java.lang.String-}
```
public final void importAnnotationFromXfdf(String xfdfFile)
```


从 XFDF 文件导入所有注释。

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.importAnnotationFromXfdf("annots.xfdf");
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xfdfFile | java.lang.String | 输入 XFDF 文件。 |

### importAnnotations(InputStream[] annotFileInputStream) {#importAnnotations-java.io.InputStream---}
```
public void importAnnotations(InputStream[] annotFileInputStream)
```


从另一个 PDF 文档流的数组中将注释导入文档。

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 InputStream[] streams = new FileInputStream[2];
 streams[0]= new FileInputStream("with_annots1.pdf");
 streams[1]= new FileInputStream("with_annots2.pdf");
 editor.importAnnotations(streams);
 editor.save("example_out.pdf");
 streams[0].Close();
 streams[1].Close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| annotFileInputStream | java.io.InputStream[] | 包含源注释的 PDF 文档流数组。 |

### importAnnotations(InputStream[] annotFileInputStream, int[] annotType) {#importAnnotations-java.io.InputStream---int---}
```
public void importAnnotations(InputStream[] annotFileInputStream, int[] annotType)
```


从另一个 PDF 文档流的数组中将指定的注释导入到文档中。

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 InputStream[] streams = new FileInputStream[2];
 streams[0]= new FileInputStream("with_annots1.pdf");
 streams[1]= new FileInputStream("with_annots2.pdf");
 int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
 editor.importAnnotations(streams, annotTypes);
 editor.save("example_out.pdf");
 streams[0].close();
 streams[1].close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| annotFileInputStream | java.io.InputStream[] | 包含源注释的 PDF 文档流数组。 |
| annotType | int[] | 要导入的注释类型。 |

### importAnnotations(String[] annotFile) {#importAnnotations-java.lang.String---}
```
public void importAnnotations(String[] annotFile)
```


从另一个 PDF 文档的数组中将注释导入文档。

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
 editor.importAnnotations(paths);
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| annotFile | java.lang.String[] | 包含源注释的 PDF 文档路径数组。 |

### importAnnotations(String[] annotFile, int[] annotType) {#importAnnotations-java.lang.String---int---}
```
public void importAnnotations(String[] annotFile, int[] annotType)
```


从另一个 PDF 文档的数组中将指定的注释导入到文档中。

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
 int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
 editor.importAnnotations(paths, annotTypes);
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| annotFile | java.lang.String[] | 包含源注释的 PDF 文档路径数组。 |
| annotType | int[] | 要导入的注释类型数组。 |

### importAnnotationsFromXfdf(InputStream xfdfSteam) {#importAnnotationsFromXfdf-java.io.InputStream-}
```
public void importAnnotationsFromXfdf(InputStream xfdfSteam)
```


从 XFDF 数据流导入所有注释。

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.importAnnotationsFromXfdf(new FileInputStream("annots.xfdf"));
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xfdfSteam | java.io.InputStream | 输入 XFDF 数据流。 |

### importAnnotationsFromXfdf(InputStream xfdfStream, int[] annotType) {#importAnnotationsFromXfdf-java.io.InputStream-int---}
```
public void importAnnotationsFromXfdf(InputStream xfdfStream, int[] annotType)
```


从 XFDF 数据流中导入指定的注释。

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 int[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line };
 editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf"), annotTypes);
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xfdfStream | java.io.InputStream | 输入 XFDF 数据流。 |
| annotType | int[] | 要导入的注释类型数组。 |

### importAnnotationsFromXfdf(String xfdfFile) {#importAnnotationsFromXfdf-java.lang.String-}
```
public void importAnnotationsFromXfdf(String xfdfFile)
```


从 XFDF 文件导入所有注释。

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.importAnnotationsFromXfdf("annots.xfdf");
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xfdfFile | java.lang.String | 输入 XFDF 文件。 |

### importAnnotationsFromXfdf(String xfdfFile, int[] annotType) {#importAnnotationsFromXfdf-java.lang.String-int---}
```
public void importAnnotationsFromXfdf(String xfdfFile, int[] annotType)
```


从 XFDF 文件导入指定的注释。

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
 editor.importAnnotationFromXfdf("annots.xfdf", annotTypes);
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xfdfFile | java.lang.String | 输入 XFDF 文件。 |
| annotType | int[] | 要导入的注释数组。 |

### modifyAnnotations(int start, int end, Annotation annotation) {#modifyAnnotations-int-int-com.aspose.pdf.Annotation-}
```
public void modifyAnnotations(int start, int end, Annotation annotation)
```


修改指定页面范围内指定类型的注释。它支持修改下一个注释属性：Modified、Title、Contents、Color、Subject 和Open。

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 TextAnnotation annot = new TextAnnotation();
 annot.setModified ( new Date());
 annot.setTitle ( "NEW AUTHOR");
 annot.setContents ( "NEW CONTENTS");
 annot.setColor ( Color.RED);
 annot.setSubject ( "NEW SUBJECT");
 annot.setOpen ( true);
 editor.modifyAnnotations(1, 2, annot);
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| start | int | 起始页码。 |
| end | int | 结束页码。 |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | 注释对象包含新属性。 |

### modifyAnnotations(int start, int end, int annotType, Annotation annotation) {#modifyAnnotations-int-int-int-com.aspose.pdf.Annotation-}
```
public void modifyAnnotations(int start, int end, int annotType, Annotation annotation)
```


“改用 modifyAnnotations(int start, int end, Annotation annotation)。”

修改指定页面范围内指定类型的注释。它支持修改下一个注释属性：Modified、Title、Contents、Color、Subject 和Open。

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 com.aspose.pdf.TextAnnotation annot = new com.aspose.pdf.TextAnnotation();
 annot.setModified ( new java.util.Date());
 annot.setTitle ( "NEW AUTHOR");
 annot.setContents ( "NEW CONTENTS");
 annot.setColor (com.aspose.pdf.Color.getRed());
 annot.setSubject ( "NEW SUBJECT");
 annot.setOpen ( true);
 editor.modifyAnnotations(1, 2, com.aspose.pdf.AnnotationType.Text, annot);
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| start | int | 起始页码。 |
| end | int | 结束页码。 |
| annotType | int | 注释类型。 |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | 注释对象包含新属性。 |

### modifyAnnotationsAuthor(int start, int end, String srcAuthor, String desAuthor) {#modifyAnnotationsAuthor-int-int-java.lang.String-java.lang.String-}
```
public void modifyAnnotationsAuthor(int start, int end, String srcAuthor, String desAuthor)
```


修改指定页面范围内注释的作者。

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.modifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR");
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| start | int | 起始页码。 |
| end | int | 结束页码。 |
| srcAuthor | java.lang.String | 必须修改的作者。 |
| desAuthor | java.lang.String | 新作者。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### redactArea(int pageIndex, Rectangle rect, Color color) {#redactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-}
```
public void redactArea(int pageIndex, Rectangle rect, Color color)
```


编辑指定页面上的区域。所有内容都被删除。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageIndex | int | 页面索引。 |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | 区域长方形。 |
| color | java.awt.Color | 填充颜色。 |

### redactExactArea(int pageIndex, Rectangle rect, Color color) {#redactExactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-}
```
public void redactExactArea(int pageIndex, Rectangle rect, Color color)
```


编辑指定页面上的区域。所有内容都被删除。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageIndex | int | 页面索引。 |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | 区域长方形。 |
| color | java.awt.Color | 填充颜色。 |

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


将结果 PDF 保存到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 输出 PDF 流 |

### save(String outputFile) {#save-java.lang.String-}
```
public void save(String outputFile)
```


将结果 PDF 保存到文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 输出PDF文件 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
