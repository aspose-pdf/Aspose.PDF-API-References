---
title: "PageInformationAnnotation"
linktitle: "PageInformationAnnotation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメント内のページ情報アノテーションを表します。このアノテーションはファイル名、ページ番号、およびアノテーション作成日時を含みます。このクラスは。"
type: docs
weight: 3380
url: /ja/java/com.aspose.pdf/pageinformationannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.PageInformationAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.PageInformationAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.PageInformationAnnotation, com.aspose.pdf.PrinterMarkAnnotation, com.aspose.pdf.PageInformationAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PageInformationAnnotation extends PrinterMarkAnnotation
```

PDF文書内のページ情報アノテーションを表します。このアノテーションにはファイル名、ページ番号、アノテーション作成日時が含まれます。このクラスは主にPDF文書の特定ページにメタデータを追加するために使用され、追跡や参照の目的に役立ちます。例えば、印刷プロセス中にページにマークを付けたり、文書閲覧時にページに関する追加情報を提供したりすることができます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PageInformationAnnotation](#PageInformationAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 指定されたページの指定された位置に {@link PageInformationAnnotation} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 注釈処理のためのビジターを受け入れます。 |
| [getAnnotationType](#getAnnotationType--) | 注釈のタイプを取得します。 |

### PageInformationAnnotation {#PageInformationAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
指定されたページの指定された位置に {@link PageInformationAnnotation} クラスの新しいインスタンスを初期化します。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
注釈処理のためのビジターを受け入れます。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

注釈のタイプを取得します。

**Returns:**
int 値です。
