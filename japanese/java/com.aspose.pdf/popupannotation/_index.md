---
title: "PopupAnnotation"
linktitle: "PopupAnnotation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テキストを入力・編集するためのポップアップウィンドウに表示するポップアップ注釈を表します。"
type: docs
weight: 3930
url: /ja/java/com.aspose.pdf/popupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PopupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PopupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PopupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PopupAnnotation extends Annotation
```

テキストを入力・編集するためのポップアップウィンドウに表示するポップアップ注釈を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PopupAnnotation](#PopupAnnotation-com.aspose.pdf.IDocument-) | コンストラクタ。Generator で使用するためのものです。 |
| [PopupAnnotation](#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 指定されたページに新しいポップアップアノテーションを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 注釈を処理するためのビジタオブジェクトを受け取ります。 |
| [getAnnotationType](#getAnnotationType--) | 注釈のタイプを取得します。 |
| [getOpen](#getOpen--) | ポップアップアノテーションを最初に開いた状態で表示すべきかを示すフラグを取得します。 |
| [getParent](#getParent--) | このポップアップアノテーションが関連付けられる親アノテーションを取得します。このエントリが存在する場合、親アノテーションの Contents、M、C、T エントリがポップアップアノテーション自体のそれらを上書きします。 |
| [setOpen](#setOpen-boolean-) | ポップアップアノテーションを最初に開いた状態で表示すべきかを示すフラグを設定します。 |
| [setParent](#setParent-com.aspose.pdf.MarkupAnnotation-) | このポップアップアノテーションが関連付けられる親アノテーションを設定します。このエントリが存在する場合、親アノテーションの Contents、M、C、T エントリがポップアップアノテーション自体のそれらを上書きします。 |

### PopupAnnotation {#PopupAnnotation-com.aspose.pdf.IDocument-}
コンストラクタ。Generator で使用するためのものです。

### PopupAnnotation {#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
指定されたページに新しいポップアップアノテーションを作成します。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
注釈を処理するためのビジタオブジェクトを受け取ります。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

注釈のタイプを取得します。

**Returns:**
AnnotationType 要素 @see AnnotationType

### getOpen {#getOpen--}
```
public boolean getOpen()
```

ポップアップアノテーションを最初に開いた状態で表示すべきかを示すフラグを取得します。

**Returns:**
ブール値

### getParent {#getParent--}
```
public Annotation getParent()
```

このポップアップアノテーションが関連付けられる親アノテーションを取得します。このエントリが存在する場合、親アノテーションの Contents、M、C、T エントリがポップアップアノテーション自体のそれらを上書きします。

**Returns:**
MarkupAnnotation オブジェクト

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

ポップアップアノテーションを最初に開いた状態で表示すべきかを示すフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setParent {#setParent-com.aspose.pdf.MarkupAnnotation-}
このポップアップアノテーションが関連付けられる親アノテーションを設定します。このエントリが存在する場合、親アノテーションの Contents、M、C、T エントリがポップアップアノテーション自体のそれらを上書きします。
