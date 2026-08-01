---
title: "クラス SvgSaveOptions.SvgImageSavingInfo"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.SvgSaveOptionsSvgImageSavingInfo クラス。このクラスは、PDF から HTML への変換中に外部リソース画像ファイルの保存に関連するデータのセットを表します。"
type: docs
weight: 10440
url: /ja/net/aspose.pdf/svgsaveoptions.svgimagesavinginfo/
---
## SvgSaveOptions.SvgImageSavingInfo class

このクラスは、PDF から HTML への変換中に外部リソース画像ファイルの保存に関連するデータのセットを表します。

```csharp
public class SvgImageSavingInfo : ResourceSavingInfo
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SvgImageSavingInfo](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/.ctor)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | コンバータによって設定されます。コンバータからカスタムメソッドのコードへ渡される想定のファイル名です。カスタムコードでこのファイルをどのように処理するか、またはどこに保存するかを決定するために使用できます。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | コンバータによって設定されます。保存されたファイルのバイナリ内容を表します。 |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | このフラグは、何らかの理由で対象ファイルをカスタムコードではなくコンバータのコード自体で標準的に処理すべき場合、カスタムコード内で "true" に設定する必要があります。したがって、true に設定されているということは、カスタムコードが参照ファイルを処理せず、コンバータが自ら（保存場所の決定および参照ファイルの命名の両方で）処理しなければならないことを意味します。 |
| [ImageType](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/imagetype) | HTML で参照される保存画像のタイプを表します。コンバータによって設定され、カスタムコードで何をすべきかを決定するために使用できます。 |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | コンバータによって設定されます。コンバータからカスタムメソッドのコードへ渡される想定のファイル名です。カスタムコードでこのファイルをどのように処理するか、またはどこに保存するかを決定するために使用できます。 |

### 関連項目

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


