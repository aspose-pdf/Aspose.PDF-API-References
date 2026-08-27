---
title: "UnifiedSaveOptions.ProgressEventHandlerInfo"
linktitle: "UnifiedSaveOptions.ProgressEventHandlerInfo"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "このクラスは、外部アプリケーションで変換進行状況をエンドユーザーに表示するために使用できる変換進捗情報を表します。"
type: docs
weight: 5440
url: /ja/java/com.aspose.pdf/unifiedsaveoptions.progresseventhandlerinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.UnifiedSaveOptions.ProgressEventHandlerInfo

```
public static class UnifiedSaveOptions.ProgressEventHandlerInfo extends Object
```

このクラスは、外部アプリケーションで変換進行状況をエンドユーザーに表示するために使用できる変換進捗情報を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDocumentId](#getDocumentId--) | 一意のドキュメント ID です。 |
| [getEventType](#getEventType--) | 発生した進捗イベントのタイプ |
| [getMaxValue](#getMaxValue--) | 進捗値の最大可能値 |
| [getValue](#getValue--) | 進捗値の現在の値 |
| [setDocumentId](#setDocumentId-com.aspose.ms.System.Guid-) | 一意のドキュメント ID です。 |
| [setEventType](#setEventType-int-) | 発生した進捗イベントのタイプ |
| [setMaxValue](#setMaxValue-int-) | 進捗値の最大可能値 |
| [setValue](#setValue-int-) | 進捗値の現在の値 |

### getDocumentId {#getDocumentId--}
```
public com.aspose.ms.System.Guid getDocumentId()
```

一意のドキュメント ID です。

**Returns:**
Guid インスタンス

### getEventType {#getEventType--}
```
public int getEventType()
```

発生した進捗イベントのタイプ

**Returns:**
ProgressEventType 要素 @see ProgressEventType

### getMaxValue {#getMaxValue--}
```
public int getMaxValue()
```

進捗値の最大可能値

**Returns:**
int 値です。

### getValue {#getValue--}
```
public int getValue()
```

進捗値の現在の値

**Returns:**
int 値です。

### setDocumentId {#setDocumentId-com.aspose.ms.System.Guid-}
一意のドキュメント ID です。

### setEventType {#setEventType-int-}
```
public void setEventType(int eventType)
```

発生した進捗イベントのタイプ

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| eventType |  | ProgressEventType 要素 @see ProgressEventType |

### setMaxValue {#setMaxValue-int-}
```
public void setMaxValue(int maxValue)
```

進捗値の最大可能値

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| maxValue |  | int 値です。 |

### setValue {#setValue-int-}
```
public void setValue(int value)
```

進捗値の現在の値

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |
