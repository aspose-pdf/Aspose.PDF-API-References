---
title: "MarkupAnnotation"
linktitle: "MarkupAnnotation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "マークアップ注釈を表す抽象クラスです。"
type: docs
weight: 2870
url: /ja/java/com.aspose.pdf/markupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class MarkupAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

マークアップ注釈を表す抽象クラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MarkupAnnotation](#MarkupAnnotation--) | コンストラクタ |
| [MarkupAnnotation](#MarkupAnnotation-com.aspose.pdf.IDocument-) | コンストラクタ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [clearState](#clearState--) | アノテーションの状態と状態モデルをクリアします。例えば、アノテーションのレビュー状態をクリアします。注意：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。 |
| [getCreationDate](#getCreationDate--) | アノテーションが作成された日時を取得します。 |
| [getInReplyTo](#getInReplyTo--) | このアノテーションが "in reply to" であるアノテーションへの参照です。両方のアノテーションは文書の同じページにある必要があります。 |
| [getOpacity](#getOpacity--) | アノテーションの描画に使用される定数不透明度値を取得します。 |
| [getPopup](#getPopup--) | このアノテーションに関連付けられたテキストを入力または編集するためのポップアップアノテーションです。 |
| [getReplyType](#getReplyType--) | このアノテーションと InReplyTo で指定されたものとの関係（"reply type"）を指定する文字列です。 |
| [getRichText](#getRichText--) | アノテーションが開かれたときにポップアップウィンドウに表示されるリッチテキスト文字列を取得します。 |
| [getRichText](#getRichText-com.aspose.pdf.engine.data.IPdfDictionary-) | アノテーションが開かれたときにポップアップウィンドウに表示されるリッチテキスト文字列を取得します。 |
| [getState](#getState--) | アノテーションの状態を取得します。注：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。 |
| [getStateModel](#getStateModel--) | アノテーションの状態モデルを取得します。注：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。 |
| [getSubject](#getSubject--) | オブジェクトの説明を表すテキストを取得します。 |
| [getTitle](#getTitle--) | 開いてアクティブな状態のアノテーションпїЅs ポップアップウィンドウのタイトルバーに表示されるテキストラベルを取得します。このエントリはアノテーションを追加したユーザーを識別します。 |
| [setCreationDate](#setCreationDate-java.util.Date-) | アノテーションが作成された日時を取得します。 |
| [setInReplyTo](#setInReplyTo-com.aspose.pdf.Annotation-) | このアノテーションが "in reply to" であるアノテーションへの参照です。両方のアノテーションは文書の同じページにある必要があります。 |
| [setMarkedState](#setMarkedState-boolean-) | アノテーションの Marked および Unmarked 状態を設定します。注：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。 |
| [setOpacity](#setOpacity-double-) | アノテーションの描画に使用される一定の不透明度値を設定します。 |
| [setPopup](#setPopup-com.aspose.pdf.PopupAnnotation-) | このアノテーションに関連付けられたテキストを入力または編集するためのポップアップアノテーションです。 |
| [setReplyType](#setReplyType-com.aspose.pdf.ReplyType-) | このアノテーションと InReplyTo で指定されたものとの関係（"reply type"）を指定する文字列です。 |
| [setReviewState](#setReviewState-com.aspose.pdf.AnnotationState-) | アノテーションのレビュー状態を設定します。Marked と Unmarked の状態は Review StateModel に属さないため無視されます。状態は対象アノテーションを作成したユーザーによって設定され、値は対象アノテーションの Title プロパティから取得されます。注：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。 |
| [setReviewState](#setReviewState-com.aspose.pdf.AnnotationState-java.lang.String-) | アノテーションのレビュー状態を設定します。Marked と Unmarked の状態は Review StateModel に属さないため無視されます。注：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。 |
| [setRichText](#setRichText-java.lang.String-) | アノテーションが開かれたときにポップアップウィンドウに表示されるリッチテキスト文字列を設定します。 |
| [setSubject](#setSubject-java.lang.String-) | オブジェクトの説明を表すテキストを設定します。 |
| [setTitle](#setTitle-java.lang.String-) | 開いてアクティブな状態のアノテーションпїЅs ポップアップウィンドウのタイトルバーに表示されるテキストラベルを設定します。このエントリはアノテーションを追加したユーザーを識別します。 |

### MarkupAnnotation {#MarkupAnnotation--}
```
public MarkupAnnotation()
```

コンストラクタ

### MarkupAnnotation {#MarkupAnnotation-com.aspose.pdf.IDocument-}
コンストラクタ

### clearState {#clearState--}
```
public final void clearState()
```

アノテーションの状態と状態モデルをクリアします。例えば、アノテーションのレビュー状態をクリアします。注意：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

アノテーションが作成された日時を取得します。

**Returns:**
Date オブジェクト

### getInReplyTo {#getInReplyTo--}
```
public Annotation getInReplyTo()
```

このアノテーションが "in reply to" であるアノテーションへの参照です。両方のアノテーションは文書の同じページにある必要があります。

**Returns:**
アノテーションの値

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

アノテーションの描画に使用される定数不透明度値を取得します。

**Returns:**
double 値

### getPopup {#getPopup--}
```
public PopupAnnotation getPopup()
```

このアノテーションに関連付けられたテキストを入力または編集するためのポップアップアノテーションです。

**Returns:**
PopupAnnotation の値

### getReplyType {#getReplyType--}
```
public ReplyType getReplyType()
```

このアノテーションと InReplyTo で指定されたものとの関係（"reply type"）を指定する文字列です。

**Returns:**
ReplyType の値 @see ReplyType

### getRichText {#getRichText--}
```
public final String getRichText()
```

アノテーションが開かれたときにポップアップウィンドウに表示されるリッチテキスト文字列を取得します。

**Returns:**
文字列値

### getRichText {#getRichText-com.aspose.pdf.engine.data.IPdfDictionary-}
アノテーションが開かれたときにポップアップウィンドウに表示されるリッチテキスト文字列を取得します。

**Returns:**
文字列値

### getState {#getState--}
```
public final AnnotationState getState()
```

アノテーションの状態を取得します。注：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。

**Returns:**
アノテーションの状態。

### getStateModel {#getStateModel--}
```
public final AnnotationStateModel getStateModel()
```

アノテーションの状態モデルを取得します。注：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。

**Returns:**
アノテーションの状態モデル。

### getSubject {#getSubject--}
```
public String getSubject()
```

オブジェクトの説明を表すテキストを取得します。

**Returns:**
文字列値

### getTitle {#getTitle--}
```
public String getTitle()
```

開いてアクティブな状態のアノテーションпїЅs ポップアップウィンドウのタイトルバーに表示されるテキストラベルを取得します。このエントリはアノテーションを追加したユーザーを識別します。

**Returns:**
文字列値

### setCreationDate {#setCreationDate-java.util.Date-}
アノテーションが作成された日時を取得します。

### setInReplyTo {#setInReplyTo-com.aspose.pdf.Annotation-}
このアノテーションが "in reply to" であるアノテーションへの参照です。両方のアノテーションは文書の同じページにある必要があります。

### setMarkedState {#setMarkedState-boolean-}
```
public final void setMarkedState(boolean marked)
```

アノテーションの Marked および Unmarked 状態を設定します。注：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| marked |  | Marked 状態を設定する場合は true、Unmarked 状態を設定する場合は false です。 |

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

アノテーションの描画に使用される一定の不透明度値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setPopup {#setPopup-com.aspose.pdf.PopupAnnotation-}
このアノテーションに関連付けられたテキストを入力または編集するためのポップアップアノテーションです。

### setReplyType {#setReplyType-com.aspose.pdf.ReplyType-}
このアノテーションと InReplyTo で指定されたものとの関係（"reply type"）を指定する文字列です。

### setReviewState {#setReviewState-com.aspose.pdf.AnnotationState-}
アノテーションのレビュー状態を設定します。Marked と Unmarked の状態は Review StateModel に属さないため無視されます。状態は対象アノテーションを作成したユーザーによって設定され、値は対象アノテーションの Title プロパティから取得されます。注：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。

### setReviewState {#setReviewState-com.aspose.pdf.AnnotationState-java.lang.String-}
アノテーションのレビュー状態を設定します。Marked と Unmarked の状態は Review StateModel に属さないため無視されます。注：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。

### setRichText {#setRichText-java.lang.String-}
アノテーションが開かれたときにポップアップウィンドウに表示されるリッチテキスト文字列を設定します。

### setSubject {#setSubject-java.lang.String-}
オブジェクトの説明を表すテキストを設定します。

### setTitle {#setTitle-java.lang.String-}
開いてアクティブな状態のアノテーションпїЅs ポップアップウィンドウのタイトルバーに表示されるテキストラベルを設定します。このエントリはアノテーションを追加したユーザーを識別します。
