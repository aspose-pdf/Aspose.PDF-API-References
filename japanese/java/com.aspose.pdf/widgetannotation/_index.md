---
title: "WidgetAnnotation"
linktitle: "WidgetAnnotation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ウィジェットアノテーションを表すクラスです。"
type: docs
weight: 5540
url: /ja/java/com.aspose.pdf/widgetannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class WidgetAnnotation extends Annotation
```

ウィジェットアノテーションを表すクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [WidgetAnnotation](#WidgetAnnotation-com.aspose.pdf.IDocument-) | アノテーションを作成 (Generator 用に使用) |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | ビジターを受け入れます。 |
| [getAnnotationActions](#getAnnotationActions--) | アノテーションのアクションを取得します。 |
| [getAnnotationType](#getAnnotationType--) | 注釈のタイプを取得します。 |
| [getCheckedStateName](#getCheckedStateName--) | 既存の状態名に従って "checked" 状態の名前を返します。 |
| [getDefaultAppearance](#getDefaultAppearance--) | フィールドのデフォルト外観を取得します。 |
| [getExportable](#getExportable--) | フィールドのエクスポート可能フラグを取得します。 |
| [getHighlighting](#getHighlighting--) | 注釈のハイライトモード。 |
| [getOnActivated](#getOnActivated--) | 注釈がアクティブ化されたときに実行されるアクションを取得します。 |
| [getParent](#getParent--) | 注釈の親オブジェクトを取得します。 |
| [getReadOnly](#getReadOnly--) | フィールドの読み取り専用ステータスを取得します。 |
| [getRequired](#getRequired--) | フィールドの必須ステータスを取得します。 |
| [setDefaultAppearance](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | フィールドのデフォルト外観を設定します。 |
| [setExportable](#setExportable-boolean-) | フィールドの読み取り専用ステータスを設定します。 |
| [setHighlighting](#setHighlighting-com.aspose.pdf.HighlightingMode-) | 注釈のハイライトモード。 |
| [setOnActivated](#setOnActivated-com.aspose.pdf.PdfAction-) | 注釈がアクティブ化されたときに実行されるアクションを設定します。 |
| [setReadOnly](#setReadOnly-boolean-) | フィールドの読み取り専用ステータスを設定します。 |
| [setRequired](#setRequired-boolean-) | フィールドの読み取り専用ステータスを設定します。 |

### WidgetAnnotation {#WidgetAnnotation-com.aspose.pdf.IDocument-}
アノテーションを作成 (Generator 用に使用)

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
ビジターを受け入れます。

### getAnnotationActions {#getAnnotationActions--}
```
public AnnotationActionCollection getAnnotationActions()
```

アノテーションのアクションを取得します。

**Returns:**
AnnotationActionCollection オブジェクト

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

注釈のタイプを取得します。

**Returns:**
AnnotationType 要素 @see AnnotationType

### getCheckedStateName {#getCheckedStateName--}
```
public final String getCheckedStateName()
```

既存の状態名に従って "checked" 状態の名前を返します。

**Returns:**
この注釈の "checked" 状態の名前。

### getDefaultAppearance {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```

フィールドのデフォルト外観を取得します。

**Returns:**
DefaultAppearance オブジェクト

### getExportable {#getExportable--}
```
public boolean getExportable()
```

フィールドのエクスポート可能フラグを取得します。

**Returns:**
ブール値

### getHighlighting {#getHighlighting--}
```
public HighlightingMode getHighlighting()
```

注釈のハイライトモード。

**Returns:**
HighlightingMode の値 @see HighlightingMode

### getOnActivated {#getOnActivated--}
```
public PdfAction getOnActivated()
```

注釈がアクティブ化されたときに実行されるアクションを取得します。

**Returns:**
PdfAction オブジェクト

### getParent {#getParent--}
```
public Field getParent()
```

注釈の親オブジェクトを取得します。

**Returns:**
Field オブジェクト

### getReadOnly {#getReadOnly--}
```
public boolean getReadOnly()
```

フィールドの読み取り専用ステータスを取得します。

**Returns:**
ブール値

### getRequired {#getRequired--}
```
public boolean getRequired()
```

フィールドの必須ステータスを取得します。

**Returns:**
ブール値

### setDefaultAppearance {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
フィールドのデフォルト外観を設定します。

### setExportable {#setExportable-boolean-}
```
public void setExportable(boolean value)
```

フィールドの読み取り専用ステータスを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setHighlighting {#setHighlighting-com.aspose.pdf.HighlightingMode-}
注釈のハイライトモード。

### setOnActivated {#setOnActivated-com.aspose.pdf.PdfAction-}
注釈がアクティブ化されたときに実行されるアクションを設定します。

### setReadOnly {#setReadOnly-boolean-}
```
public void setReadOnly(boolean value)
```

フィールドの読み取り専用ステータスを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setRequired {#setRequired-boolean-}
```
public void setRequired(boolean value)
```

フィールドの読み取り専用ステータスを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
