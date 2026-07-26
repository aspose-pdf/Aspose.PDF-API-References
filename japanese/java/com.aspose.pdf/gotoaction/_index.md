---
title: "GoToAction"
linktitle: "GoToAction"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "指定された宛先（ページ、位置、拡大率）にビューを変更する GoTo アクションを表します。"
type: docs
weight: 1810
url: /ja/java/com.aspose.pdf/gotoaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.GoToAction, com.aspose.pdf.PdfAction, com.aspose.pdf.GoToAction

**All Implemented Interfaces:**
IAppointment

```
public class GoToAction extends PdfAction
```

指定された宛先（ページ、位置、拡大率）にビューを変更する GoTo アクションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [GoToAction](#GoToAction--) | コンストラクタ。 |
| [GoToAction](#GoToAction-com.aspose.pdf.Document-java.lang.String-) | コンストラクタ。 |
| [GoToAction](#GoToAction-com.aspose.pdf.ExplicitDestination-) | コンストラクタ。 |
| [GoToAction](#GoToAction-int-) | GoToAction クラスのコンストラクタ。 |
| [GoToAction](#GoToAction-com.aspose.pdf.Page-) | コンストラクタ。 |
| [GoToAction](#GoToAction-com.aspose.pdf.Page-com.aspose.pdf.ExplicitDestinationType-double...-) | コンストラクタ。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDestination](#getDestination--) | ジャンプ先の宛先を取得します。 |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | ジャンプ先の宛先を設定します。 |

### GoToAction {#GoToAction--}
```
@Deprecated public GoToAction()
```

コンストラクタ。

### GoToAction {#GoToAction-com.aspose.pdf.Document-java.lang.String-}
コンストラクタ。

### GoToAction {#GoToAction-com.aspose.pdf.ExplicitDestination-}
コンストラクタ。

### GoToAction {#GoToAction-int-}
```
@Deprecated public GoToAction(int page)
```

GoToAction クラスのコンストラクタ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ページ |  | int 値です。 |

### GoToAction {#GoToAction-com.aspose.pdf.Page-}
コンストラクタ。

### GoToAction {#GoToAction-com.aspose.pdf.Page-com.aspose.pdf.ExplicitDestinationType-double...-}
コンストラクタ。

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

ジャンプ先の宛先を取得します。

**Returns:**
IAppointment 値

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
ジャンプ先の宛先を設定します。
