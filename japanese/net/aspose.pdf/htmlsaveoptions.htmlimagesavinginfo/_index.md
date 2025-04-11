---
title: Class HtmlSaveOptions.HtmlImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsHtmlImageSavingInfo クラス。このクラスは、PDFからHTMLへの変換中に外部リソース画像ファイルの保存に関連するデータのセットを表します。
type: docs
weight: 5640
url: /ja/net/aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
## HtmlSaveOptions.HtmlImageSavingInfo クラス

このクラスは、PDFからHTMLへの変換中に外部リソース画像ファイルの保存に関連するデータのセットを表します。

```csharp
public class HtmlImageSavingInfo : ResourceSavingInfo
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [HtmlImageSavingInfo](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/.ctor)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | コンバータによって設定されます。コンバータからカスタムメソッドのコードに渡されるファイル名の想定値。カスタムコードで処理方法やファイルの保存先を決定するために使用できます。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | コンバータによって設定されます。保存されたファイルのバイナリコンテンツを表します。 |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | 何らかの理由で提案されたファイルがカスタムコードではなく、コンバータのコード自体で標準的な方法で処理されるべき場合、このフラグはカスタムコードで「true」に設定する必要があります。したがって、trueに設定されているということは、カスタムコードが参照されたファイルを処理せず、コンバータがそれを自分で処理しなければならないことを意味します（保存先や参照ファイル内の名前付けの両方の意味で）。 |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/htmlhostpagenumber) | 保存された画像が生成されたHTMLページファイルのどのページに関連しているかをカスタムコードに伝えます。ページ分割がオフになっている場合、この値は常に「1」を含みます。なぜなら、その場合は1つのHTMLページしか生成されないからです。 |
| [ImageType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/imagetype) | HTMLで参照される保存された画像のタイプを表します。コンバータによって設定され、カスタムコードで何をすべきかを決定するために使用できます。 |
| [ParentType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/parenttype) | 保存された画像はHTML自体に関連しているか、HTMLに埋め込まれたSVGから抽出されることがあります。このプロパティは、処理された画像の親のタイプが何であるかをカスタムコードに伝えることができます。コンバータによって設定され、カスタムコードでその画像に対して何をすべきかを決定するために使用できます（例えば、カスタムコードは画像をどこに保存するか、親のコンテンツ内でどのように参照するかを決定できます）。 |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/pdfhostpagenumber) | 保存された画像が元のPDF文書のどのページに関連しているかをカスタムコードに伝えます。元の文書のすべてのページが保存されるわけではないため、この値は元のPDF内のホストページ番号を示します。元のページ番号が何らかの理由で不明な場合、常に「1」を返します。 |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | コンバータによって設定されます。コンバータからカスタムメソッドのコードに渡されるファイル名の想定値。カスタムコードで処理方法やファイルの保存先を決定するために使用できます。 |

### 参照

* クラス [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* クラス [HtmlSaveOptions](../htmlsaveoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)