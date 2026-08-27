---
title: "BDC"
linktitle: "BDC"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "BDC 演算子 (Begin marked-content sequence) を表すクラス"
type: docs
weight: 30
url: /ja/java/com.aspose.pdf.operators/bdc/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.BDC, com.aspose.pdf.Operator, com.aspose.pdf.operators.BDC

```
public class BDC extends Operator
```

BDC 演算子 (Begin marked-content sequence) を表すクラス

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [BDC](#BDC-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.BeginMarkedContentWithProperties-) | 演算子を初期化します。 |
| [BDC](#BDC-java.lang.String-) | 演算子を初期化します。 |
| [BDC](#BDC-java.lang.String-com.aspose.pdf.facades.BDCProperties-) |  |
| [BDC](#BDC-java.lang.String-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter-) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getProperties](#getProperties--) |  |
| [getTag](#getTag--) | マークされたコンテンツタグを取得します |
| [setTag](#setTag-java.lang.String-) | マークされたコンテンツタグを設定します |
| [toString](#toString--) | 演算子のテキスト表現を返します。 |

### BDC {#BDC-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.BeginMarkedContentWithProperties-}
演算子を初期化します。

### BDC {#BDC-java.lang.String-}
演算子を初期化します。

### BDC {#BDC-java.lang.String-com.aspose.pdf.facades.BDCProperties-}


### BDC {#BDC-java.lang.String-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

### getProperties {#getProperties--}
```
public final BDCProperties getProperties()
```



### getTag {#getTag--}
```
public String getTag()
```

マークされたコンテンツタグを取得します

**Returns:**
文字列値

### setTag {#setTag-java.lang.String-}
マークされたコンテンツタグを設定します

### toString {#toString--}
```
public String toString()
```

演算子のテキスト表現を返します。

**Returns:**
演算子のテキスト表現。
