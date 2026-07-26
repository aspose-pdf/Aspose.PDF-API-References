---
title: "LaunchAction"
linktitle: "LaunchAction"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "アプリケーションを起動する、またはドキュメントを開く・印刷するランチアクションを表します。"
type: docs
weight: 2620
url: /ja/java/com.aspose.pdf/launchaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.LaunchAction, com.aspose.pdf.PdfAction, com.aspose.pdf.LaunchAction

**All Implemented Interfaces:**
IAppointment

```
public final class LaunchAction extends PdfAction
```

アプリケーションを起動する、またはドキュメントを開く・印刷するランチアクションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [LaunchAction](#LaunchAction-com.aspose.pdf.IDocument-java.lang.String-) | 起動アクションを作成します。 |
| [LaunchAction](#LaunchAction-java.lang.String-) | 起動アクションを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFile](#getFile--) | 起動されるアプリケーションまたは開かれる・印刷されるドキュメントを取得します。 |
| [getNewWindow](#getNewWindow--) | 宛先ドキュメントを新しいウィンドウで開くかどうかを指定するフラグを取得します（PDF ドキュメントにのみ適用）。 |
| [setFile](#setFile-java.lang.String-) | 起動されるアプリケーションまたは開かれる・印刷されるドキュメントを設定します。 |
| [setNewWindow](#setNewWindow-com.aspose.pdf.ExtendedBoolean-) | 宛先ドキュメントを新しいウィンドウで開くかどうかを指定するフラグを設定します（PDF ドキュメントにのみ適用）。ExtendedBoolean |

### LaunchAction {#LaunchAction-com.aspose.pdf.IDocument-java.lang.String-}
起動アクションを作成します。

### LaunchAction {#LaunchAction-java.lang.String-}
起動アクションを作成します。

### getFile {#getFile--}
```
public String getFile()
```

起動されるアプリケーションまたは開かれる・印刷されるドキュメントを取得します。

**Returns:**
文字列値

### getNewWindow {#getNewWindow--}
```
public ExtendedBoolean getNewWindow()
```

宛先ドキュメントを新しいウィンドウで開くかどうかを指定するフラグを取得します（PDF ドキュメントにのみ適用）。

**Returns:**
ExtendedBoolean 要素 @see ExtendedBoolean

### setFile {#setFile-java.lang.String-}
起動されるアプリケーションまたは開かれる・印刷されるドキュメントを設定します。

### setNewWindow {#setNewWindow-com.aspose.pdf.ExtendedBoolean-}
宛先ドキュメントを新しいウィンドウで開くかどうかを指定するフラグを設定します（PDF ドキュメントにのみ適用）。ExtendedBoolean
