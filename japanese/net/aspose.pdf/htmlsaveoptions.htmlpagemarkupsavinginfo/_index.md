---
title: "クラス HtmlSaveOptions.HtmlPageMarkupSavingInfo"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.HtmlSaveOptionsHtmlPageMarkupSavingInfo クラス。HtmlSaveOptions の SplitToPages プロパティが有効な場合、PDF を HTML に変換する際に、変換されたページごとに 1 つの HTML ファイルが作成され、複数の HTML ファイルが生成されます。このクラスは、PDF から HTML への変換中に 1 つの HTML ページのマークアップをカスタム保存するために関連するデータのセットを表します。"
type: docs
weight: 5800
url: /ja/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## HtmlSaveOptions.HtmlPageMarkupSavingInfo class

HtmlSaveOptions の SplitToPages プロパティが有効な場合、PDF を HTML に変換する際に、変換されたページごとに 1 つの HTML ファイルが作成され、複数の HTML ファイルが生成されます。このクラスは、PDF から HTML への変換中に 1 つの HTML ページのマークアップをカスタム保存するために関連するデータのセットを表します。

```csharp
public class HtmlPageMarkupSavingInfo
```

## フィールド

| 名前 | 説明 |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/contentstream) | コンバータによって設定されます。保存された HTML をストリームとして表します。 |
| [CustomProcessingCancelled](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/customprocessingcancelled) | 必要に応じてカスタムコードで設定すべきです。このフラグは、何らかの理由で提供された html マークアップをカスタムコードではなく、コンバータのコード自体で標準的に処理する場合、カスタムコードで "true" に設定する必要があります。したがって、カスタムコードでこのフラグを設定すると、カスタムコードが参照ファイルを処理せず、コンバータが自ら処理することを意味します。 |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/htmlhostpagenumber) | コンバータによって設定されます。SplitToPages プロパティが設定されている場合、変換中に変換されたページごとに 1 つの HTML ファイルが作成され、複数の HTML ファイルが生成されます。このプロパティは、保存された HTML ページファイルの順序番号を保持します。このプロパティは、カスタムコードのロジックで HTML ページの処理方法や保存場所を決定するために使用できます。ページ分割が無効になっている場合、この値は常に '1' を含みます。なぜなら、その場合はソース文書全体に対して 1 つの大きな HTML ページが生成されるからです。 |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/pdfhostpagenumber) | コンバータによって設定されます。SplitToPages プロパティが設定されている場合、変換中に変換されたページごとに 1 つの HTML ファイルが作成され、複数の HTML ファイルが生成されます。このプロパティは、元の PDF のどのページから保存された HTML マークアップが作成されたかをカスタムコードに知らせます。元のページ番号が何らかの理由で不明、または SplitToPages が false の場合、このプロパティは常に '0' を含み、コンバータが提供された HTML マークアップファイルに対して正確な元 PDF のページ番号を示せないことを示します。 |
| [SupposedFileName](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/supposedfilename) | コンバータによって設定されます。コンバータからカスタムメソッドのコードに渡される想定ファイル名で、カスタムコードでコンテンツの処理方法や保存場所を決定するために使用できます。 |

### 関連項目

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


