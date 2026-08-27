---
title: "クラス SaveOptions.ResourceSavingInfo"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.SaveOptionsResourceSavingInfo クラス。このクラスは、PDF を他の形式（例：HTML）に変換する際に発生する外部リソースファイルの保存に関連するデータの集合を表します。"
type: docs
weight: 10090
url: /ja/net/aspose.pdf/saveoptions.resourcesavinginfo/
---
## SaveOptions.ResourceSavingInfo class

このクラスは、PDF を他の形式（例：HTML）に変換する際に発生する外部リソースファイルの保存に関連するデータの集合を表します。

```csharp
public class ResourceSavingInfo
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | コンバータによって設定されます。コンバータからカスタムメソッドのコードへ渡される想定のファイル名です。カスタムコードでこのファイルをどのように処理するか、またはどこに保存するかを決定するために使用できます。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | コンバータによって設定されます。保存されたファイルのバイナリ内容を表します。 |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | このフラグは、何らかの理由で対象ファイルをカスタムコードではなくコンバータのコード自体で標準的に処理すべき場合、カスタムコード内で "true" に設定する必要があります。したがって、true に設定されているということは、カスタムコードが参照ファイルを処理せず、コンバータが自ら（保存場所の決定および参照ファイルの命名の両方で）処理しなければならないことを意味します。 |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | コンバータによって設定されます。コンバータからカスタムメソッドのコードへ渡される想定のファイル名です。カスタムコードでこのファイルをどのように処理するか、またはどこに保存するかを決定するために使用できます。 |

### 関連項目

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


