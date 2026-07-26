---
title: "RichMediaAnnotation"
linktitle: "RichMediaAnnotation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメントにビデオ/オーディオデータを埋め込むことを可能にする RichMediaAnnotation を記述するクラスです。"
type: docs
weight: 4260
url: /ja/java/com.aspose.pdf/richmediaannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.RichMediaAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.RichMediaAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.RichMediaAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class RichMediaAnnotation extends Annotation
```

PDF ドキュメントにビデオ/オーディオデータを埋め込むことを可能にする RichMediaAnnotation を記述するクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [RichMediaAnnotation](#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | RichMediaAnnotation を初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | このアノテーションに対してビジターを受け入れます。 |
| [addCustomData](#addCustomData-java.lang.String-java.io.InputStream-) | カスタム名付きデータを追加します（例: flash スクリプトに必要な場合）。 |
| [getActivateOn](#getActivateOn--) | アプリケーションを起動するイベントです。 |
| [getAnnotationType](#getAnnotationType--) | 注釈のタイプを取得します。 |
| [getContent](#getContent--) | Rich Media コンテンツのデータです。 |
| [getCustomFlashVariables](#getCustomFlashVariables--) | プレーヤーに渡される flash 変数を設定または取得します。 |
| [getCustomPlayer](#getCustomPlayer--) | ビデオ/オーディオ データを再生するカスタム flash プレーヤーを設定または取得します。 |
| [getType](#getType--) | コンテンツのタイプを取得または設定します。可能な値: Audio, Video。 |
| [setActivateOn](#setActivateOn-int-) | アプリケーションを起動するイベントです。 |
| [setContent](#setContent-java.lang.String-java.io.InputStream-) | コンテンツ ストリームを設定します。 |
| [setCustomFlashVariables](#setCustomFlashVariables-java.lang.String-) | プレーヤーに渡される flash 変数を設定または取得します。 |
| [setCustomPlayer](#setCustomPlayer-java.io.InputStream-) | ビデオ/オーディオ データを再生するカスタム flash プレーヤーを設定または取得します。 |
| [setPoster](#setPoster-java.io.InputStream-) | アノテーションのポスターを設定します。 |
| [setType](#setType-int-) | コンテンツのタイプを取得または設定します。可能な値: Audio, Video。 |
| [update](#update--) | 指定されたパラメータでデータを更新します。 |

### RichMediaAnnotation {#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
RichMediaAnnotation を初期化します。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
このアノテーションに対してビジターを受け入れます。

### addCustomData {#addCustomData-java.lang.String-java.io.InputStream-}
カスタム名付きデータを追加します（例: flash スクリプトに必要な場合）。

### getActivateOn {#getActivateOn--}
```
public int getActivateOn()
```

アプリケーションを起動するイベントです。

**Returns:**
ActivationEvent 要素

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

注釈のタイプを取得します。

**Returns:**
AnnotationType 要素 @see AnnotationType

### getContent {#getContent--}
```
public InputStream getContent()
```

Rich Media コンテンツのデータです。

**Returns:**
InputStream オブジェクト

### getCustomFlashVariables {#getCustomFlashVariables--}
```
public String getCustomFlashVariables()
```

プレーヤーに渡される flash 変数を設定または取得します。

**Returns:**
String オブジェクト

### getCustomPlayer {#getCustomPlayer--}
```
public InputStream getCustomPlayer()
```

ビデオ/オーディオ データを再生するカスタム flash プレーヤーを設定または取得します。

**Returns:**
InputStream オブジェクト

### getType {#getType--}
```
public int getType()
```

コンテンツのタイプを取得または設定します。可能な値: Audio, Video。

**Returns:**
ContentType 値 @see ContentType

### setActivateOn {#setActivateOn-int-}
```
public void setActivateOn(int value)
```

アプリケーションを起動するイベントです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ActivationEvent 要素 |

### setContent {#setContent-java.lang.String-java.io.InputStream-}
コンテンツ ストリームを設定します。

### setCustomFlashVariables {#setCustomFlashVariables-java.lang.String-}
プレーヤーに渡される flash 変数を設定または取得します。

### setCustomPlayer {#setCustomPlayer-java.io.InputStream-}
ビデオ/オーディオ データを再生するカスタム flash プレーヤーを設定または取得します。

### setPoster {#setPoster-java.io.InputStream-}
アノテーションのポスターを設定します。

### setType {#setType-int-}
```
public void setType(int value)
```

コンテンツのタイプを取得または設定します。可能な値: Audio, Video。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ContentType 要素 |

### update {#update--}
```
public void update()
```

指定されたパラメータでデータを更新します。
