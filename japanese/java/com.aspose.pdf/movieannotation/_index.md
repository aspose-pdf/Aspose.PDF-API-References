---
title: "MovieAnnotation"
linktitle: "MovieAnnotation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "コンピュータ画面とスピーカーで表示されるアニメーション画像と音声を含むムービーアノテーションを表します。アノテーションがアクティブ化されると、。"
type: docs
weight: 3090
url: /ja/java/com.aspose.pdf/movieannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MovieAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MovieAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MovieAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class MovieAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

コンピュータ画面とスピーカーで表示されるアニメーション画像と音声を含むムービーアノテーションを表します。アノテーションがアクティブになると、ムービーが再生されます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MovieAnnotation](#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-) | Generator と共に使用するためのコンストラクタです。 |
| [MovieAnnotation](#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | 指定されたページに新しいサウンドアノテーションを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 注釈を処理するためのビジタオブジェクトを受け取ります。 |
| [getAnnotationType](#getAnnotationType--) | 注釈のタイプを取得します。 |
| [getAspect](#getAspect--) | ムービーのバウンディングボックスの幅と高さ（ピクセル単位）を取得または設定します。 |
| [getFile](#getFile--) | 自己記述型ムービーファイルを識別するファイル仕様を取得します。 |
| [getPoster](#getPoster--) | ムービーを表すポスター画像を表示するかどうか、またその方法を指定するフラグまたはストリームを取得または設定します。true の場合、ポスター画像はムービーファイルから取得されます。false の場合、ポスターは表示されません。 |
| [getRotate](#getRotate--) | ページに対してムービーが時計回りに回転する角度（度数）を取得または設定します。値は 90 の倍数でなければなりません。 |
| [getTitle](#getTitle--) | ムービーアノテーションのタイトルを取得します。 |
| [setAspect](#setAspect-com.aspose.pdf.Point-) | ムービーのバウンディングボックスの幅と高さ（ピクセル単位）を取得または設定します。 |
| [setFile](#setFile-com.aspose.pdf.FileSpecification-) | 自己記述型ムービーファイルを識別するファイル仕様を設定します。 |
| [setPoster](#setPoster-boolean-) | ムービーを表すポスター画像を表示するかどうか、またその方法を指定するフラグまたはストリームを取得または設定します。true の場合、ポスター画像はムービーファイルから取得されます。false の場合、ポスターは表示されません。 |
| [setRotate](#setRotate-int-) | ページに対してムービーが時計回りに回転する角度（度数）を取得または設定します。値は 90 の倍数でなければなりません。 |
| [setTitle](#setTitle-java.lang.String-) | ムービーアノテーションのタイトルを設定します。 |

### MovieAnnotation {#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-}
Generator と共に使用するためのコンストラクタです。

### MovieAnnotation {#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
指定されたページに新しいサウンドアノテーションを作成します。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
注釈を処理するためのビジタオブジェクトを受け取ります。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

注釈のタイプを取得します。

**Returns:**
AnnotationType 要素を int 値として @see AnnotationType

### getAspect {#getAspect--}
```
public final Point getAspect()
```

ムービーのバウンディングボックスの幅と高さ（ピクセル単位）を取得または設定します。

**Returns:**
Point インスタンス

### getFile {#getFile--}
```
public FileSpecification getFile()
```

自己記述型ムービーファイルを識別するファイル仕様を取得します。

**Returns:**
FileSpecification 値

### getPoster {#getPoster--}
```
public final boolean getPoster()
```

ムービーを表すポスター画像を表示するかどうか、またその方法を指定するフラグまたはストリームを取得または設定します。true の場合、ポスター画像はムービーファイルから取得されます。false の場合、ポスターは表示されません。

**Returns:**
ブール値

### getRotate {#getRotate--}
```
public final int getRotate()
```

ページに対してムービーが時計回りに回転する角度（度数）を取得または設定します。値は 90 の倍数でなければなりません。

**Returns:**
int 値です。

### getTitle {#getTitle--}
```
public String getTitle()
```

ムービーアノテーションのタイトルを取得します。

**Returns:**
文字列値

### setAspect {#setAspect-com.aspose.pdf.Point-}
ムービーのバウンディングボックスの幅と高さ（ピクセル単位）を取得または設定します。

### setFile {#setFile-com.aspose.pdf.FileSpecification-}
自己記述型ムービーファイルを識別するファイル仕様を設定します。

### setPoster {#setPoster-boolean-}
```
public final void setPoster(boolean value)
```

ムービーを表すポスター画像を表示するかどうか、またその方法を指定するフラグまたはストリームを取得または設定します。true の場合、ポスター画像はムービーファイルから取得されます。false の場合、ポスターは表示されません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setRotate {#setRotate-int-}
```
public final void setRotate(int value)
```

ページに対してムービーが時計回りに回転する角度（度数）を取得または設定します。値は 90 の倍数でなければなりません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setTitle {#setTitle-java.lang.String-}
ムービーアノテーションのタイトルを設定します。
