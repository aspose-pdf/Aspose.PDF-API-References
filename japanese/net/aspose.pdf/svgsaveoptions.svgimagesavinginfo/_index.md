---
title: Class SvgSaveOptions.SvgImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SvgSaveOptionsSvgImageSavingInfo クラス。このクラスは、PDFからHTMLへの変換中に外部リソース画像ファイルの保存に関連するデータのセットを表します。
type: docs
weight: 10260
url: /ja/net/aspose.pdf/svgsaveoptions.svgimagesavinginfo/
---
## SvgSaveOptions.SvgImageSavingInfo クラス

このクラスは、PDFからHTMLへの変換中に外部リソース画像ファイルの保存に関連するデータのセットを表します。

```csharp
public class SvgImageSavingInfo : ResourceSavingInfo
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [SvgImageSavingInfo](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/.ctor)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | コンバーターによって設定されます。コンバーターからカスタムメソッドのコードに渡されるファイル名の想定値。カスタムコードで使用して、ファイルをどのように処理するか、またはどこに保存するかを決定できます。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | コンバーターによって設定されます。保存されたファイルのバイナリコンテンツを表します。 |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | 何らかの理由で提案されたファイルがカスタムコードではなく、コンバーターのコード自体で標準的な方法で処理されるべき場合、このフラグはカスタムコードで「true」に設定する必要があります。したがって、trueに設定されていることは、カスタムコードが参照されたファイルを処理せず、コンバーターがそれ自体で処理する必要があることを意味します（保存先や参照ファイルの命名の両方の意味で）。 |
| [ImageType](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/imagetype) | HTMLに参照される保存された画像のタイプを表します。コンバーターによって設定され、カスタムコードで何をすべきかを決定するために使用できます。 |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | コンバーターによって設定されます。コンバーターからカスタムメソッドのコードに渡されるファイル名の想定値。カスタムコードで使用して、ファイルをどのように処理するか、またはどこに保存するかを決定できます。 |

### 参照

* クラス [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* クラス [SvgSaveOptions](../svgsaveoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)