---
title: "IPdfFileEditor"
linktitle: "IPdfFileEditor"
second_title: "Aspose.PDF for Java API 参考"
description: "实现对 PDF 文件的操作：合并、拆分、提取页面、制作小册子等。"
type: docs
weight: 290
url: /zh/java/com.aspose.pdf.facades/ipdffileeditor/
---
```
public interface IPdfFileEditor
```

实现对 PDF 文件的操作：合并、拆分、提取页面、制作小册子等。

## 方法

| 方法 | 描述 |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | 调整页面内容大小并添加指定的边距。 |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | 调整页面内容大小并添加指定的边距。 |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | 调整页面内容大小并添加指定的边距。 |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | 调整页面内容大小并添加指定的边距。 |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | 追加页面，这些页面从 portStreams 中的文档数组中选择。 |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | 追加页面，这些页面在 portStream 中从 startPage 到 endPage 范围内选择，并在 firstInputStream 末尾的 portStream 中。 |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | 追加页面，这些页面从 portFiles 文档中选择。 |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | 追加页面，这些页面在 portFile 中从 startPage 到 endPage 范围内选择，并在 firstInputFile 末尾的 portFile 中。 |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | 合并文档。 |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | 合并文件 |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | 将两个 Pdf 文档合并为一个新 Pdf 文档，页面交替排列，并用空白页填充空白位置。 |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | 合并两个文件。 |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | 将文件合并为一个文件。 |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | 合并两个文件。 |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | 将两个 Pdf 文档合并为一个新 Pdf 文档，页面交替排列，并用空白页填充空白位置。 |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | 从输入文件中删除由数字数组指定的页面，并保存为新的 Pdf 文件。 |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | 从输入文件中删除由数字数组指定的页面，并保存为新的 Pdf 文件。 |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | 提取由数字数组指定的页面，保存为新的 Pdf 文件。 |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | 从输入文件中提取页面，保存为新的 Pdf 文件。 |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | 提取由数字数组指定的页面，保存为新的 PDF 文件。 |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | 从输入文件中提取页面，保存为新的 Pdf 文件。 |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | 是否允许合并异常 |
| [getAttachmentName](#getAttachmentName--) | 获取当操作结果以附件形式存储到 HttpServletResponse 对象时的附件名称。 |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | 如果设置为 true，操作完成后流将被关闭。 |
| [getContentDisposition](#getContentDisposition--) | 获取当操作结果存储到 HttpServletResponse 对象时内容的存储方式。 |
| [getConversionLog](#getConversionLog--) | 获取转换过程的日志。 |
| [getCorruptedFileAction](#getCorruptedFileAction--) | 此属性定义在连接过程中遇到损坏文件时的行为。 |
| [getIncrementalUpdates](#getIncrementalUpdates--) | 如果为 true，则在连接期间进行增量更新。 |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | 如果为 true，则在合并表单时字段名称将被设为唯一。 |
| [getLastException](#getLastException--) | 获取最近发生的异常。 |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | 如果此属性为 true，具有相同名称的连接文档的可选内容将合并为结果文档中的一个层。 |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | 如果为 true，合并重复的大纲。 |
| [getOwnerPassword](#getOwnerPassword--) | 如果源输入 PDF 文件已加密，则获取所有者密码。 |
| [getPreserveUserRights](#getPreserveUserRights--) | 如果为 true，则将第一个文档的用户权限应用于连接后的文档。 |
| [getRemoveSignatures](#getRemoveSignatures--) | 如果为 true，所有签名将从字段中移除（字段仍然保留）；否则，可能会得到无效的签名。 |
| [getSaveOptions](#getSaveOptions--) | 获取或设置当结果存储为 HttpServletResponse 时的保存选项。 |
| [getUniqueSuffix](#getUniqueSuffix--) | 获取在合并表单时添加到字段名称以使其唯一的后缀格式。 |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | 将另一个文件的页面插入到输入 PDF 文件中。 |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | 将另一个文件的页面插入到输入 PDF 文件中。 |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | 将另一个文件的页面插入到输入 PDF 文件中。 |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | 在指定位置将另一个文件的页面插入到 PDF 文件中。 |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | 从 InputStream 创建小册子并输出到 outputStream。 |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | 从 firstInputStream 创建自定义小册子并输出到 outputStream。 |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | 从输入流创建小册子并将结果保存到输出流。 |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | 从 firstInputStream 创建小册子并输出到 outputStream。 |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | 从输入文件创建小册子并输出到输出文件。 |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | 从 firstInputFile 创建自定义小册子并输出到 outputFile。 |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | 从 inputFile 创建小册子并输出到 outputFile。 |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | 从 firstInputFile 创建自定义小册子并输出到 outputFile。 |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | 从多个输入 PDF 流创建 N-Up 文档并输出到 outputStream。 |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | 从两个输入 PDF 流创建 N-Up 文档并输出到 outputStream。 |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | 从输入流创建 N-Up 文档并将结果保存到输出流。 |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | 从第一个输入流创建 N-Up 文档并输出到输出流。 |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | 从多个输入 PDF 文件创建 N-Up 文档并输出到 outputFile。 |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | 从 firstInputFile 创建 N-Up 文档并输出到 outputFile。 |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | 从输入文件创建 N-Up 文档并输出到 outputFile。 |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | 从两个输入 PDF 文件创建 N-Up 文档并输出到 outputFile。 |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | 调整文档页面的内容大小。 |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | 调整文档页面的内容大小。 |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | 调整文档页面的内容大小。 |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | 调整文档页面的内容大小。 |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | 如果设置为 true，则在发生错误时抛出异常。 |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | 设置附件的名称，当操作结果以附件形式存储到 HttpServletResponse 对象时使用。 |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | 如果设置为 true，操作完成后流将被关闭。 |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | 设置当操作结果存储到 HttpServletResponse 对象时内容的存储方式。 |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | 设置 PDF 文件格式。 |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | 此属性定义在连接过程中遇到损坏文件时的行为。 |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | 如果为 true，则在连接期间进行增量更新。 |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | 如果为 true，则在合并表单时字段名称将被设为唯一。 |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | 如果此属性为 true，具有相同名称的连接文档的可选内容将合并为结果文档中的一个层。 |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | 如果为 true，合并重复的大纲。 |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | 如果源输入 Pdf 文件已加密，则设置所有者密码。 |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | 如果为 true，则将第一个文档的用户权限应用于连接后的文档。 |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | 如果为 true，所有签名将从字段中移除（字段仍然保留）；否则，可能会得到无效的签名。 |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 设置当结果存储为 HttpServletResponse 时的保存选项。 |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | 设置在表单合并时添加到字段名称以使其唯一的后缀格式。 |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | 从起始位置拆分到指定位置，并将前半部分保存到输出流中。 |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | 将 Pdf 文件从第一页拆分到指定位置，并将前半部分保存为新文件。 |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | 将 Pdf 文件拆分为多个文档。文档可以是单页的，也可以是多页的。 |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | 将 Pdf 文件拆分为多个文档。文档可以是单页的，也可以是多页的。 |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | 从指定位置拆分，并将后半部分保存为新的文件流。 |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | 从该位置拆分，并将后半部分保存为新文件。 |
| [splitToPages](#splitToPages-java.io.InputStream-) | 将 Pdf 文件拆分为单页文档。 |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | 将 Pdf 文件拆分为单页文档并保存到指定路径。 |
| [splitToPages](#splitToPages-java.lang.String-) | 将 PDF 文件拆分为单页文档。 |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | 将 Pdf 文件拆分为单页文档并保存到指定路径。 |

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
调整页面内容大小并添加指定的边距。

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
调整页面内容大小并添加指定的边距。

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
调整页面内容大小并添加指定的边距。

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
调整页面内容大小并添加指定的边距。

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
追加页面，这些页面从 portStreams 中的文档数组中选择。

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
追加页面，这些页面在 portStream 中从 startPage 到 endPage 范围内选择，并在 firstInputStream 末尾的 portStream 中。

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
追加页面，这些页面从 portFiles 文档中选择。

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
追加页面，这些页面在 portFile 中从 startPage 到 endPage 范围内选择，并在 firstInputFile 末尾的 portFile 中。

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
合并文档。

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
合并文件

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
将两个 Pdf 文档合并为一个新 Pdf 文档，页面交替排列，并用空白页填充空白位置。

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
合并两个文件。

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
将文件合并为一个文件。

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
合并两个文件。

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
将两个 Pdf 文档合并为一个新 Pdf 文档，页面交替排列，并用空白页填充空白位置。

### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
从输入文件中删除由数字数组指定的页面，并保存为新的 Pdf 文件。

### delete {#delete-java.lang.String-int:A-java.lang.String-}
从输入文件中删除由数字数组指定的页面，并保存为新的 Pdf 文件。

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
提取由数字数组指定的页面，保存为新的 Pdf 文件。

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
从输入文件中提取页面，保存为新的 Pdf 文件。

### extract {#extract-java.lang.String-int:A-java.lang.String-}
提取由数字数组指定的页面，保存为新的 PDF 文件。

### extract {#extract-java.lang.String-int-int-java.lang.String-}
从输入文件中提取页面，保存为新的 Pdf 文件。

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
boolean getAllowConcatenateExceptions()
```

是否允许合并异常

**Returns:**
布尔值

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

获取当操作结果以附件形式存储到 HttpServletResponse 对象时的附件名称。

**Returns:**
string 值

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
boolean getCloseConcatenatedStreams()
```

如果设置为 true，操作完成后流将被关闭。

**Returns:**
布尔值

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

获取当操作结果存储到 HttpServletResponse 对象时内容的存储方式。

**Returns:**
ContentDisposition 元素

### getConversionLog {#getConversionLog--}
```
String getConversionLog()
```

获取转换过程的日志。

**Returns:**
string 值

### getCorruptedFileAction {#getCorruptedFileAction--}
```
int getCorruptedFileAction()
```

此属性定义在连接过程中遇到损坏文件时的行为。

**Returns:**
ConcatenateCorruptedFileAction 元素

### getIncrementalUpdates {#getIncrementalUpdates--}
```
boolean getIncrementalUpdates()
```

如果为 true，则在连接期间进行增量更新。

**Returns:**
布尔值

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
boolean getKeepFieldsUnique()
```

如果为 true，则在合并表单时字段名称将被设为唯一。

**Returns:**
布尔值

### getLastException {#getLastException--}
```
Exception getLastException()
```

获取最近发生的异常。

**Returns:**
java.lang.Exception 对象

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
boolean getMergeDuplicateLayers()
```

如果此属性为 true，具有相同名称的连接文档的可选内容将合并为结果文档中的一个层。

**Returns:**
布尔值

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
boolean getMergeDuplicateOutlines()
```

如果为 true，合并重复的大纲。

**Returns:**
布尔值

### getOwnerPassword {#getOwnerPassword--}
```
String getOwnerPassword()
```

如果源输入 PDF 文件已加密，则获取所有者密码。

**Returns:**
string 值

### getPreserveUserRights {#getPreserveUserRights--}
```
boolean getPreserveUserRights()
```

如果为 true，则将第一个文档的用户权限应用于连接后的文档。

**Returns:**
布尔值

### getRemoveSignatures {#getRemoveSignatures--}
```
boolean getRemoveSignatures()
```

如果为 true，所有签名将从字段中移除（字段仍然保留）；否则，可能会得到无效的签名。

**Returns:**
布尔值

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

获取或设置当结果存储为 HttpServletResponse 时的保存选项。

**Returns:**
SaveOptions 对象

### getUniqueSuffix {#getUniqueSuffix--}
```
String getUniqueSuffix()
```

获取在合并表单时添加到字段名称以使其唯一的后缀格式。

**Returns:**
string 值

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
将另一个文件的页面插入到输入 PDF 文件中。

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
将另一个文件的页面插入到输入 PDF 文件中。

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
将另一个文件的页面插入到输入 PDF 文件中。

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
在指定位置将另一个文件的页面插入到 PDF 文件中。

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
从 InputStream 创建小册子并输出到 outputStream。

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
从 firstInputStream 创建自定义小册子并输出到 outputStream。

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
从输入流创建小册子并将结果保存到输出流。

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
从 firstInputStream 创建小册子并输出到 outputStream。

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
从输入文件创建小册子并输出到输出文件。

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
从 firstInputFile 创建自定义小册子并输出到 outputFile。

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
从 inputFile 创建小册子并输出到 outputFile。

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
从 firstInputFile 创建自定义小册子并输出到 outputFile。

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
从多个输入 PDF 流创建 N-Up 文档并输出到 outputStream。

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
从两个输入 PDF 流创建 N-Up 文档并输出到 outputStream。

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
从输入流创建 N-Up 文档并将结果保存到输出流。

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
从第一个输入流创建 N-Up 文档并输出到输出流。

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
从多个输入 PDF 文件创建 N-Up 文档并输出到 outputFile。

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
从 firstInputFile 创建 N-Up 文档并输出到 outputFile。

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
从输入文件创建 N-Up 文档并输出到 outputFile。

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
从两个输入 PDF 文件创建 N-Up 文档并输出到 outputFile。

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
调整文档页面的内容大小。

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
调整文档页面的内容大小。

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
调整文档页面的内容大小。

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
调整文档页面的内容大小。

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
void setAllowConcatenateExceptions(boolean value)
```

如果设置为 true，则在发生错误时抛出异常。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setAttachmentName {#setAttachmentName-java.lang.String-}
设置附件的名称，当操作结果以附件形式存储到 HttpServletResponse 对象时使用。

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
void setCloseConcatenatedStreams(boolean value)
```

如果设置为 true，操作完成后流将被关闭。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
设置当操作结果存储到 HttpServletResponse 对象时内容的存储方式。

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
设置 PDF 文件格式。

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
void setCorruptedFileAction(int value)
```

此属性定义在连接过程中遇到损坏文件时的行为。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | ConcatenateCorruptedFileAction 元素 |

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
void setIncrementalUpdates(boolean value)
```

如果为 true，则在连接期间进行增量更新。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
void setKeepFieldsUnique(boolean value)
```

如果为 true，则在合并表单时字段名称将被设为唯一。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
void setMergeDuplicateLayers(boolean value)
```

如果此属性为 true，具有相同名称的连接文档的可选内容将合并为结果文档中的一个层。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
void setMergeDuplicateOutlines(boolean value)
```

如果为 true，合并重复的大纲。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
如果源输入 Pdf 文件已加密，则设置所有者密码。

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
void setPreserveUserRights(boolean value)
```

如果为 true，则将第一个文档的用户权限应用于连接后的文档。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
void setRemoveSignatures(boolean value)
```

如果为 true，所有签名将从字段中移除（字段仍然保留）；否则，可能会得到无效的签名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
设置当结果存储为 HttpServletResponse 时的保存选项。

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
设置在表单合并时添加到字段名称以使其唯一的后缀格式。

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
从起始位置拆分到指定位置，并将前半部分保存到输出流中。

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
将 Pdf 文件从第一页拆分到指定位置，并将前半部分保存为新文件。

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
将 Pdf 文件拆分为多个文档。文档可以是单页的，也可以是多页的。

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
将 Pdf 文件拆分为多个文档。文档可以是单页的，也可以是多页的。

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
从指定位置拆分，并将后半部分保存为新的文件流。

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
从该位置拆分，并将后半部分保存为新文件。

### splitToPages {#splitToPages-java.io.InputStream-}
将 Pdf 文件拆分为单页文档。

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
将 Pdf 文件拆分为单页文档并保存到指定路径。

### splitToPages {#splitToPages-java.lang.String-}
将 PDF 文件拆分为单页文档。

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
将 Pdf 文件拆分为单页文档并保存到指定路径。
