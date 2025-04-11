---
title: Class SaveOptions.ResourceSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SaveOptionsResourceSavingInfo クラス。このクラスは、PDFを他の形式（例：HTML）に変換する際に発生する外部リソースファイルの保存に関連するデータのセットを表します。
type: docs
weight: 9940
url: /ja/net/aspose.pdf/saveoptions.resourcesavinginfo/
---
## SaveOptions.ResourceSavingInfo クラス

このクラスは、PDFを他の形式（例：HTML）に変換する際に発生する外部リソースファイルの保存に関連するデータのセットを表します。

```csharp
public class ResourceSavingInfo
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | コンバータによって設定されます。コンバータからカスタムメソッドのコードに渡される想定ファイル名。カスタムコードでどのように処理するか、またはそのファイルをどこに保存するかを決定するために使用できます。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | コンバータによって設定されます。保存されたファイルのバイナリコンテンツを表します。 |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | 何らかの理由で提案されたファイルがカスタムコードではなく、コンバータのコード自体で標準的な方法で処理されるべき場合、このフラグはカスタムコードで「true」に設定する必要があります。したがって、trueに設定されていることは、カスタムコードが参照されたファイルを処理せず、コンバータがそれ自体で処理しなければならないことを意味します（保存先や参照ファイルの命名の両方の意味で）。 |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | コンバータによって設定されます。コンバータからカスタムメソッドのコードに渡される想定ファイル名。カスタムコードでどのように処理するか、またはそのファイルをどこに保存するかを決定するために使用できます。 |

### 参照

* クラス [SaveOptions](../saveoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)