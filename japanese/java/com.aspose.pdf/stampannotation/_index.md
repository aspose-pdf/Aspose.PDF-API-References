---
title: "StampAnnotation"
linktitle: "StampAnnotation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "<p> ゴムスタンプ注釈を表します。このタイプの注釈は、ページにゴムスタンプで押されたかのように見えるテキストまたはグラフィックを表示します。 </p> <hr>."
type: docs
weight: 4630
url: /ja/java/com.aspose.pdf/stampannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.StampAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class StampAnnotation extends MarkupAnnotation
```

<p> ゴムスタンプ注釈を表します。このタイプの注釈は、ページにゴムスタンプで押されたかのように見えるテキストまたはグラフィックを表示します。 </p> <hr> <pre> 次のコードスニペットは、最初の PDF 文書ページに 2 つのスタンプを追加する方法を示しています。入力文書は inFile から取得され、変更は outFile に保存されます。最初のスタンプはアイコン NotForPublicRelease を使用し、2 番目のスタンプは rubber.jpg の画像を使用します。 Document document = new Document(inFile); StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease); stamp1.setRect ( new Rectangle(100, 100, 120, 120)) document.getPages().get(1).getAnnotations().add(stamp1); StampAnnotation stamp2 = new StampAnnotation(new FileStream(\"rubber.jpg\", FileMode.Open)); stamp2.setRect ( new Rectangle(200, 200, 220, 220)) document.getPages().get(1).getAnnotations().add(stamp2); document.save(outFile); </pre>

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [StampAnnotation](#StampAnnotation-com.aspose.pdf.IDocument-) | コンストラクタ |
| [StampAnnotation](#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 指定されたページに新しいスタンプ注釈を作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 注釈コレクションを閲覧する際に {@code AnnotationSelector} ビジターを受け入れます。 |
| [clear](#clear--) | 静的インスタンスをクリアする |
| [getAnnotationType](#getAnnotationType--) | 注釈のタイプを取得します。 |
| [getIcon](#getIcon--) | ゴムスタンプのアイコンを取得します。 |
| [getImage](#getImage--) | 注釈の画像を取得します。 |
| [setBase64SVGImage](#setBase64SVGImage-java.lang.String-) | 注釈の SVG 画像を Base64 文字列で設定します。 |
| [setIcon](#setIcon-com.aspose.pdf.StampIcon-) | ゴムスタンプのアイコンを設定します。 |
| [setImage](#setImage-java.io.InputStream-) | 注釈の画像を設定します。 |

### StampAnnotation {#StampAnnotation-com.aspose.pdf.IDocument-}
コンストラクタ

### StampAnnotation {#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
指定されたページに新しいスタンプ注釈を作成します。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
注釈コレクションを閲覧する際に {@code AnnotationSelector} ビジターを受け入れます。

### clear {#clear--}
```
public static void clear()
```

静的インスタンスをクリアする

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

注釈のタイプを取得します。

**Returns:**
AnnotationType 要素 @see AnnotationType

### getIcon {#getIcon--}
```
public StampIcon getIcon()
```

ゴムスタンプのアイコンを取得します。

**Returns:**
StampIcon の値

### getImage {#getImage--}
```
public InputStream getImage()
```

注釈の画像を取得します。

**Returns:**
InputStream オブジェクト

### setBase64SVGImage {#setBase64SVGImage-java.lang.String-}
注釈の SVG 画像を Base64 文字列で設定します。

### setIcon {#setIcon-com.aspose.pdf.StampIcon-}
ゴムスタンプのアイコンを設定します。

### setImage {#setImage-java.io.InputStream-}
注釈の画像を設定します。
