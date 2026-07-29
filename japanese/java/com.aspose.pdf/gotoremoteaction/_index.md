---
title: "GoToRemoteAction"
linktitle: "GoToRemoteAction"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "通常の GoTo アクションと似ていますが、現在のファイルではなく別の PDF ファイルの宛先へジャンプするリモート GoTo アクションを表します。"
type: docs
weight: 1820
url: /ja/java/com.aspose.pdf/gotoremoteaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.GoToAction com.aspose.pdf.GoToRemoteAction, com.aspose.pdf.PdfAction, com.aspose.pdf.GoToAction com.aspose.pdf.GoToRemoteAction, com.aspose.pdf.GoToAction, com.aspose.pdf.GoToRemoteAction

**All Implemented Interfaces:**
IAppointment

```
public final class GoToRemoteAction extends GoToAction
```

通常の GoTo アクションと似ていますが、現在のファイルではなく別の PDF ファイルの宛先へジャンプするリモート GoTo アクションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [GoToRemoteAction](#GoToRemoteAction-java.lang.String-com.aspose.pdf.ExplicitDestination-) | GoToRemoteAction オブジェクトを初期化します。 |
| [GoToRemoteAction](#GoToRemoteAction-java.lang.String-int-) | GoToRemoteAction オブジェクトを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFile](#getFile--) | 目的地が配置されているファイルの仕様を取得します。 |
| [getNewWindow](#getNewWindow--) | 目的地ドキュメントを新しいウィンドウで開くかどうかを示すフラグを取得します。 |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | / * / * ジャンプ先の目的地を取得します。 / * / * / * |
| [setFile](#setFile-com.aspose.pdf.FileSpecification-) | 目的地が配置されているファイルの仕様を設定します。 |
| [setNewWindow](#setNewWindow-com.aspose.pdf.ExtendedBoolean-) | 目的地ドキュメントを新しいウィンドウで開くかどうかを示すフラグを設定します。 |

### GoToRemoteAction {#GoToRemoteAction-java.lang.String-com.aspose.pdf.ExplicitDestination-}
GoToRemoteAction オブジェクトを初期化します。

### GoToRemoteAction {#GoToRemoteAction-java.lang.String-int-}
GoToRemoteAction オブジェクトを初期化します。

### getFile {#getFile--}
```
public FileSpecification getFile()
```

目的地が配置されているファイルの仕様を取得します。

**Returns:**
FileSpecification オブジェクト

### getNewWindow {#getNewWindow--}
```
public ExtendedBoolean getNewWindow()
```

目的地ドキュメントを新しいウィンドウで開くかどうかを示すフラグを取得します。

**Returns:**
ExtendedBoolean 要素 @see ExtendedBoolean

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
/ * / * ジャンプ先の目的地を取得します。 / * / * / *

### setFile {#setFile-com.aspose.pdf.FileSpecification-}
目的地が配置されているファイルの仕様を設定します。

### setNewWindow {#setNewWindow-com.aspose.pdf.ExtendedBoolean-}
目的地ドキュメントを新しいウィンドウで開くかどうかを示すフラグを設定します。
