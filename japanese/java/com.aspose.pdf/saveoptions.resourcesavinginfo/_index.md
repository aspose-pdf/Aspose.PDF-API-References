---
title: "SaveOptions.ResourceSavingInfo"
linktitle: "SaveOptions.ResourceSavingInfo"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "このクラスは、PDF を他の形式（例：HTML）に変換する際に発生する外部リソースファイルの保存に関連するデータの集合を表します。"
type: docs
weight: 4440
url: /ja/java/com.aspose.pdf/saveoptions.resourcesavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.ResourceSavingInfo

```
public static class SaveOptions.ResourceSavingInfo extends Object
```

このクラスは、PDF を他の形式（例：HTML）に変換する際に発生する外部リソースファイルの保存に関連するデータの集合を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getContentStream](#getContentStream--) | コンバータによって設定されます。保存されたファイルのバイナリ内容を表します。 |
| [getResourceType](#getResourceType--) | コンバータによって設定されます。コンバータからカスタムメソッドのコードへ渡される想定のファイル名です。カスタムコードでこのファイルをどのように処理するか、またはどこに保存するかを決定する際に使用できます。 |
| [getSupposedFileName](#getSupposedFileName--) | コンバータによって設定されます。コンバータからカスタムメソッドのコードへ渡される想定のファイル名です。カスタムコードでこのファイルをどのように処理するか、またはどこに保存するかを決定する際に使用できます。 |
| [isCustomProcessingCancelled](#isCustomProcessingCancelled--) | このフラグは、何らかの理由で提案されたファイルをカスタムコードではなくコンバータのコード自体で標準的な方法で処理すべき場合、カスタムコードで "true" に設定する必要があります。したがって、true に設定されているということは、カスタムコードが参照ファイルを処理せず、コンバータがそれを自ら処理しなければならないことを意味します（保存場所と参照ファイルの命名の両方において）。 |
| [setCustomProcessingCancelled](#setCustomProcessingCancelled-boolean-) | このフラグは、何らかの理由で提案されたファイルをカスタムコードではなくコンバータのコード自体で標準的な方法で処理すべき場合、カスタムコードで "true" に設定する必要があります。したがって、true に設定されているということは、カスタムコードが参照ファイルを処理せず、コンバータがそれを自ら処理しなければならないことを意味します（保存場所と参照ファイルの命名の両方において）。 |

### getContentStream {#getContentStream--}
```
public byte[] getContentStream()
```

コンバータによって設定されます。保存されたファイルのバイナリ内容を表します。

**Returns:**
バイト配列

### getResourceType {#getResourceType--}
```
public SaveOptions.NodeLevelResourceType getResourceType()
```

コンバータによって設定されます。コンバータからカスタムメソッドのコードへ渡される想定のファイル名です。カスタムコードでこのファイルをどのように処理するか、またはどこに保存するかを決定する際に使用できます。

**Returns:**
NodeLevelResourceType 要素 @see NodeLevelResourceType

### getSupposedFileName {#getSupposedFileName--}
```
public String getSupposedFileName()
```

コンバータによって設定されます。コンバータからカスタムメソッドのコードへ渡される想定のファイル名です。カスタムコードでこのファイルをどのように処理するか、またはどこに保存するかを決定する際に使用できます。

**Returns:**
文字列値

### isCustomProcessingCancelled {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```

このフラグは、何らかの理由で提案されたファイルをカスタムコードではなくコンバータのコード自体で標準的な方法で処理すべき場合、カスタムコードで "true" に設定する必要があります。したがって、true に設定されているということは、カスタムコードが参照ファイルを処理せず、コンバータがそれを自ら処理しなければならないことを意味します（保存場所と参照ファイルの命名の両方において）。

**Returns:**
ブール値

### setCustomProcessingCancelled {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```

このフラグは、何らかの理由で提案されたファイルをカスタムコードではなくコンバータのコード自体で標準的な方法で処理すべき場合、カスタムコードで "true" に設定する必要があります。したがって、true に設定されているということは、カスタムコードが参照ファイルを処理せず、コンバータがそれを自ら処理しなければならないことを意味します（保存場所と参照ファイルの命名の両方において）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| customProcessingCancelled |  | ブール値 |
