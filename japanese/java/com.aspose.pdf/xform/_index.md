---
title: "XForm"
linktitle: "XForm"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "XForm を表すクラス"
type: docs
weight: 5590
url: /ja/java/com.aspose.pdf/xform/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XForm

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer

```
public final class XForm extends Object implements com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer
```

XForm を表すクラス

## メソッド

| メソッド | 説明 |
| --- | --- |
| [close](#close--) | メモリを解放します |
| [containsOwnResources](#containsOwnResources--) | 独自リソースを含む場合は True を返します |
| [createNewForm](#createNewForm-com.aspose.pdf.engine.data.ITrailerable-) | ドキュメント内に新しい XForm を作成します。 |
| [createNewForm](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-) | ページの内容を複製する XForm を作成します。 |
| [createNewForm](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-) |  |
| [dispose](#dispose--) | メモリを解放します |
| [freeMemory](#freeMemory--) | キャッシュされたデータをクリアします |
| [getBBox](#getBBox--) | フォームのバウンディングボックスを取得します。 |
| [getContents](#getContents--) | フォームのオペレーターを取得します。 |
| [getEngineObj](#getEngineObj--) | 内部のみ |
| [getIT](#getIT--) | フォーム IT を取得します。Form IT は XObject の意図を示す名前です。 |
| [getMatrix](#getMatrix--) | フォームのマトリックスを取得します。 |
| [getName](#getName--) | フォーム名を取得します。フォーム名はページリソースの XObject 辞書でフォームを参照するために使用される名前です。 |
| [getOpi](#getOpi--) | Open Prepress Interface (OPI) を取得します。 |
| [getRectangle](#getRectangle--) | フォームの矩形を取得します。 |
| [getResources](#getResources--) | Form X-Object のリソースを返します。Form にリソースがなく、allowCreate が true の場合、リソースは自動的に作成されます。 |
| [getResources](#getResources-boolean-) | Form X-Object のリソースを返します |
| [getResourcesField](#getResourcesField--) | Form XObject のリソースを取得します。 |
| [getSubtype](#getSubtype--) | フォームのサブタイプを取得します。 |
| [setBBox](#setBBox-com.aspose.pdf.Rectangle-) | フォームのバウンディングボックスを設定します。 |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | フォームのマトリックスを設定します。 |
| [setName](#setName-java.lang.String-) | フォーム名を設定します。フォーム名はページリソースの XObject 辞書でフォームを参照するために使用される名前です。 |

### close {#close--}
```
public final void close()
```

メモリを解放します

### containsOwnResources {#containsOwnResources--}
```
public boolean containsOwnResources()
```

独自リソースを含む場合は True を返します

**Returns:**
ブール値

### createNewForm {#createNewForm-com.aspose.pdf.engine.data.ITrailerable-}
ドキュメント内に新しい XForm を作成します。

### createNewForm {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-}
ページの内容を複製する XForm を作成します。

### createNewForm {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-}


### dispose {#dispose--}
```
public final void dispose()
```

メモリを解放します

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

キャッシュされたデータをクリアします

### getBBox {#getBBox--}
```
public Rectangle getBBox()
```

フォームのバウンディングボックスを取得します。

**Returns:**
Rectangle

### getContents {#getContents--}
```
public OperatorCollection getContents()
```

フォームのオペレーターを取得します。

**Returns:**
OperatorCollection オブジェクト

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

内部のみ

**Returns:**
IPdfObject オブジェクト

### getIT {#getIT--}
```
public final String getIT()
```

フォーム IT を取得します。Form IT は XObject の意図を示す名前です。

**Returns:**
文字列値

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

フォームのマトリックスを取得します。

**Returns:**
Matrix

### getName {#getName--}
```
public String getName()
```

フォーム名を取得します。フォーム名はページリソースの XObject 辞書でフォームを参照するために使用される名前です。

**Returns:**
文字列

### getOpi {#getOpi--}
```
public Opi getOpi()
```

Open Prepress Interface (OPI) を取得します。

**Returns:**
Opi インスタンス

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

フォームの矩形を取得します。

**Returns:**
Rectangle

### getResources {#getResources--}
```
public Resources getResources()
```

Form X-Object のリソースを返します。Form にリソースがなく、allowCreate が true の場合、リソースは自動的に作成されます。

**Returns:**
Resources インスタンス

### getResources {#getResources-boolean-}
```
public final Resources getResources(boolean allowCreate)
```

Form X-Object のリソースを返します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| allowCreate |  | If For がリソースを持っておらず、allowCreate が true の場合、Resources はフォームのために自動的に作成されます。 |

**Returns:**
Resources インスタンス

### getResourcesField {#getResourcesField--}
```
public final Resources getResourcesField()
```

Form XObject のリソースを取得します。

**Returns:**
Resources インスタンス。If For がリソースを持っていない場合、Resources はフォームのために自動的に作成されます。

### getSubtype {#getSubtype--}
```
public final String getSubtype()
```

フォームのサブタイプを取得します。

**Returns:**
文字列値

### setBBox {#setBBox-com.aspose.pdf.Rectangle-}
フォームのバウンディングボックスを設定します。

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
フォームのマトリックスを設定します。

### setName {#setName-java.lang.String-}
フォーム名を設定します。フォーム名はページリソースの XObject 辞書でフォームを参照するために使用される名前です。
