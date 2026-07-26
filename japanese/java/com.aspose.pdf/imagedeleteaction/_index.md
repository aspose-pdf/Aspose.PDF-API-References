---
title: "ImageDeleteAction"
linktitle: "ImageDeleteAction"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "画像オブジェクトがコレクションから削除されたときに実行されるアクションです。画像オブジェクトが削除された場合"
type: docs
weight: 2290
url: /ja/java/com.aspose.pdf/imagedeleteaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.ImageDeleteAction, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.ImageDeleteAction, com.aspose.ms.System.Enum, com.aspose.pdf.ImageDeleteAction

```
public final class ImageDeleteAction extends com.aspose.ms.System.Enum
```

画像オブジェクトがコレクションから削除されたときに実行されるアクションです。画像オブジェクトが削除された場合

## フィールド

| フィールド | 説明 |
| --- | --- |
| [Check](#Check) | 画像はコレクションから削除され、他のページからその画像への参照が存在しない場合にのみ画像オブジェクトも削除されます。これは ForceDelete オプションと比較してより時間がかかる場合があります。 |
| [ForceDelete](#ForceDelete) | 画像はコレクションから削除され、画像オブジェクトはドキュメントから削除されます。同じオブジェクトへの他の参照が存在する場合、ドキュメントが破損する可能性があります。 |
| [KeepContents](#KeepContents) | 画像はコレクションから削除されます。ページ内容に画像への参照が含まれている場合、それらは削除されません。ドキュメントが無効になる可能性があります。 |
| [None](#None) | 画像はコレクションおよびページ内容から削除されますが、画像オブジェクトは削除されません。ファイルサイズは減少しません。 |

### Check {#Check}
```
public static final int Check
```

画像はコレクションから削除され、他のページからその画像への参照が存在しない場合にのみ画像オブジェクトも削除されます。これは ForceDelete オプションと比較してより時間がかかる場合があります。

### ForceDelete {#ForceDelete}
```
public static final int ForceDelete
```

画像はコレクションから削除され、画像オブジェクトはドキュメントから削除されます。同じオブジェクトへの他の参照が存在する場合、ドキュメントが破損する可能性があります。

### KeepContents {#KeepContents}
```
public static final int KeepContents
```

画像はコレクションから削除されます。ページ内容に画像への参照が含まれている場合、それらは削除されません。ドキュメントが無効になる可能性があります。

### None {#None}
```
public static final int None
```

画像はコレクションおよびページ内容から削除されますが、画像オブジェクトは削除されません。ファイルサイズは減少しません。
