---
title: "XYZExplicitDestination"
linktitle: "XYZExplicitDestination"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "<p> ウィンドウの左上隅に座標 (left, top) が配置されたページとその内容を表示する明示的なデスティネーションを表します。"
type: docs
weight: 5800
url: /ja/java/com.aspose.pdf/xyzexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.XYZExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.XYZExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class XYZExplicitDestination extends ExplicitDestination
```

<p> 明示的なデスティネーションを表します。このデスティネーションは、座標 (left, top) がウィンドウの左上隅に位置し、ページの内容がズーム係数で拡大表示されます。left、top、または zoom のいずれかのパラメータが null の場合、そのパラメータの現在の値が変更されずに保持されます。ズーム値が 0 の場合も null と同じ意味です。 </p> <hr> <p> Document doc = new Document("example.pdf"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom(); </p>

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [XYZExplicitDestination](#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-) | リモートの明示的なデスティネーションを作成します。 |
| [XYZExplicitDestination](#XYZExplicitDestination-int-double-double-double-) | リモートの明示的なデスティネーションを作成します。 |
| [XYZExplicitDestination](#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-) | インスタンスを作成し、DOM ページオブジェクトと可視パラメータで初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [createDestination](#createDestination-com.aspose.pdf.Page-double-double-double-boolean-) | 必要に応じてページの回転を考慮し、ページの指定位置へのデスティネーションを作成します。 |
| [createDestinationToUpperLeftCorner](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-) | 指定ページへのデスティネーションを作成します。 |
| [createDestinationToUpperLeftCorner](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-) | 指定ページの左上隅へのデスティネーションを作成します。 |
| [getLeft](#getLeft--) | ウィンドウの左上隅の左水平座標を取得します。 |
| [getTop](#getTop--) | ウィンドウの左上隅の上部垂直座標を取得します。 |
| [getZoom](#getZoom--) | ズーム係数を取得します。 |
| [toString](#toString--) | オブジェクトの状態を文字列値に変換します。例: "1 XYZ 100 200 3"。 |

### XYZExplicitDestination {#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-}
リモートの明示的なデスティネーションを作成します。

### XYZExplicitDestination {#XYZExplicitDestination-int-double-double-double-}
```
public XYZExplicitDestination(int pageNumber, double left, double top, double zoom)
```

リモートの明示的なデスティネーションを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber |  | リモートドキュメントのデスティネーションページ番号です。 |
| left |  | ウィンドウの左上隅の左水平座標。 |
| 上部 |  | ウィンドウの左上隅の上部垂直座標。 |
| ズーム |  | ズーム係数。 |

### XYZExplicitDestination {#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-}
インスタンスを作成し、DOM ページオブジェクトと可視パラメータで初期化します。

### createDestination {#createDestination-com.aspose.pdf.Page-double-double-double-boolean-}
必要に応じてページの回転を考慮し、ページの指定位置へのデスティネーションを作成します。

### createDestinationToUpperLeftCorner {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-}
指定ページへのデスティネーションを作成します。

### createDestinationToUpperLeftCorner {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-}
指定ページの左上隅へのデスティネーションを作成します。

### getLeft {#getLeft--}
```
public double getLeft()
```

ウィンドウの左上隅の左水平座標を取得します。

**Returns:**
double

### getTop {#getTop--}
```
public double getTop()
```

ウィンドウの左上隅の上部垂直座標を取得します。

**Returns:**
double

### getZoom {#getZoom--}
```
public double getZoom()
```

ズーム係数を取得します。

**Returns:**
double

### toString {#toString--}
```
public String toString()
```

オブジェクトの状態を文字列値に変換します。例: "1 XYZ 100 200 3"。

**Returns:**
オブジェクトの状態を表す文字列値です。
