---
title: "FileAttachmentAnnotation"
linktitle: "FileAttachmentAnnotation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ファイル添付アノテーションを記述するクラスです。"
type: docs
weight: 1430
url: /ja/java/com.aspose.pdf/fileattachmentannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FileAttachmentAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FileAttachmentAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FileAttachmentAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.FileAttachmentAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class FileAttachmentAnnotation extends MarkupAnnotation
```

ファイル添付アノテーションを記述するクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FileAttachmentAnnotation](#FileAttachmentAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.FileSpecification-) | 指定されたページに新しい FileAttachment アノテーションを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | アノテーションを処理するための visitor オブジェクトを受け入れます。 |
| [getAnnotationType](#getAnnotationType--) | 注釈のタイプを取得します。 |
| [getFile](#getFile--) | このアノテーションに関連付けられたファイルの仕様を取得します。 |
| [getIcon](#getIcon--) | アノテーションの表示に使用されるアイコンを取得します。 |
| [setFile](#setFile-com.aspose.pdf.FileSpecification-) | このアノテーションに関連付けられたファイルの仕様を設定します。 |
| [setIcon](#setIcon-com.aspose.pdf.FileIcon-) | アノテーションの表示に使用されるアイコンを設定します。 |

### FileAttachmentAnnotation {#FileAttachmentAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.FileSpecification-}
指定されたページに新しい FileAttachment アノテーションを作成します。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
アノテーションを処理するための visitor オブジェクトを受け入れます。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

注釈のタイプを取得します。

**Returns:**
整数値 @see AnnotationType

### getFile {#getFile--}
```
public FileSpecification getFile()
```

このアノテーションに関連付けられたファイルの仕様を取得します。

**Returns:**
ファイルの仕様。

### getIcon {#getIcon--}
```
public FileIcon getIcon()
```

アノテーションの表示に使用されるアイコンを取得します。

**Returns:**
FileIcon の値 @see FileIcon

### setFile {#setFile-com.aspose.pdf.FileSpecification-}
このアノテーションに関連付けられたファイルの仕様を設定します。

### setIcon {#setIcon-com.aspose.pdf.FileIcon-}
アノテーションの表示に使用されるアイコンを設定します。
