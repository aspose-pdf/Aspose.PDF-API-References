---
title: "クラス HtmlSaveOptions.HtmlImageSavingInfo"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.HtmlSaveOptionsHtmlImageSavingInfo クラス。このクラスは、PDF から HTML への変換中に外部リソース画像ファイルの保存に関連するデータのセットを表します。"
type: docs
weight: 5770
url: /ja/net/aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
## HtmlSaveOptions.HtmlImageSavingInfo class

このクラスは、PDF から HTML への変換中に外部リソース画像ファイルの保存に関連するデータのセットを表します。

```csharp
public class HtmlImageSavingInfo : ResourceSavingInfo
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [HtmlImageSavingInfo](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/.ctor)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | コンバータによって設定されます。コンバータからカスタムメソッドのコードへ渡される想定のファイル名です。カスタムコードでこのファイルをどのように処理するか、またはどこに保存するかを決定するために使用できます。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | コンバータによって設定されます。保存されたファイルのバイナリ内容を表します。 |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | このフラグは、何らかの理由で対象ファイルをカスタムコードではなくコンバータのコード自体で標準的に処理すべき場合、カスタムコード内で "true" に設定する必要があります。したがって、true に設定されているということは、カスタムコードが参照ファイルを処理せず、コンバータが自ら（保存場所の決定および参照ファイルの命名の両方で）処理しなければならないことを意味します。 |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/htmlhostpagenumber) | 生成された HTML ページファイルのセットのどのページに保存された画像が対応するかをカスタムコードに指示します。ページ分割がオフの場合、この値は常に '1' を含みます。なぜならその場合は HTML ページが 1 つだけ生成されるからです。 |
| [ImageType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/imagetype) | HTMLで参照される保存画像のタイプを表します。コンバータによって設定され、カスタムコードで何をすべきかを決定するために使用できます。 |
| [ParentType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/parenttype) | 保存された画像はHTML自体に関連する場合や、HTMLに埋め込まれたSVGから抽出される場合があります。このプロパティは、カスタムコードに対して処理された画像の親のタイプが何であるかを伝えることができます。コンバータによって設定され、カスタムコードでその画像に対して何をすべきか（例：画像をどこに保存するか、または親のコンテンツでどのように参照すべきか）を決定するために使用できます。 |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/pdfhostpagenumber) | カスタムコードに、保存された画像が元の PDF ドキュメントのどの page に対応しているかを伝えます。元のドキュメントのすべての page が保存されるわけではない可能性があるため、この値は元の PDF 内のホスト page 番号を示します。何らかの理由で元の page 番号が不明な場合は、常に「1」を返します。 |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | コンバータによって設定されます。コンバータからカスタムメソッドのコードへ渡される想定のファイル名です。カスタムコードでこのファイルをどのように処理するか、またはどこに保存するかを決定するために使用できます。 |

### 関連項目

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


