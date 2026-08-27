---
title: "SoundAnnotation"
linktitle: "SoundAnnotation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "コンピュータのマイクで録音された音声またはファイルからインポートされた音声を含むサウンド注釈を表します。"
type: docs
weight: 4530
url: /ja/java/com.aspose.pdf/soundannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.SoundAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class SoundAnnotation extends MarkupAnnotation
```

コンピュータのマイクで録音された音声またはファイルからインポートされた音声を含むサウンド注釈を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SoundAnnotation](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | 指定されたページに新しいサウンドアノテーションを作成します。 |
| [SoundAnnotation](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-) | 指定されたページに新しいサウンドアノテーションを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 注釈を処理するためのビジタオブジェクトを受け取ります。 |
| [getAnnotationType](#getAnnotationType--) | 注釈のタイプを取得します。 |
| [getIcon](#getIcon--) | 注釈の表示に使用されるアイコンを取得します。 |
| [getSoundData](#getSoundData--) | 注釈が有効化されたときに再生されるサウンドを定義するサウンドオブジェクトを取得します。 |
| [setIcon](#setIcon-int-) | 注釈の表示に使用されるアイコンを設定します。 |

### SoundAnnotation {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
指定されたページに新しいサウンドアノテーションを作成します。

### SoundAnnotation {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-}
指定されたページに新しいサウンドアノテーションを作成します。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
注釈を処理するためのビジタオブジェクトを受け取ります。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

注釈のタイプを取得します。

**Returns:**
AnnotationType の値 @see AnnotationType

### getIcon {#getIcon--}
```
public int getIcon()
```

注釈の表示に使用されるアイコンを取得します。

**Returns:**
SoundIcon の値 @see SoundIcon

### getSoundData {#getSoundData--}
```
public SoundData getSoundData()
```

注釈が有効化されたときに再生されるサウンドを定義するサウンドオブジェクトを取得します。

**Returns:**
SoundData の値

### setIcon {#setIcon-int-}
```
public void setIcon(int value)
```

注釈の表示に使用されるアイコンを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | SoundIcon の値 @see SoundIcon |
