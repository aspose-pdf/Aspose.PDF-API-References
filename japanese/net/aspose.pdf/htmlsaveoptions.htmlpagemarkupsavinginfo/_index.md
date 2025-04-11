---
title: Class HtmlSaveOptions.HtmlPageMarkupSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsHtmlPageMarkupSavingInfo クラス。HtmlSaveOptions の SplitToPages プロパティが有効な場合、PDF から HTML への変換中に複数の HTML ファイル（変換されたページごとに 1 つの HTML ファイル）が作成されます。このクラスは、PDF から HTML への変換中に 1 つの HTML ページのマークアップをカスタム保存することに関連するデータのセットを表します。
type: docs
weight: 5670
url: /ja/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## HtmlSaveOptions.HtmlPageMarkupSavingInfo クラス

HtmlSaveOptions の SplitToPages プロパティが有効な場合、PDF から HTML への変換中に複数の HTML ファイル（変換されたページごとに 1 つの HTML ファイル）が作成されます。このクラスは、PDF から HTML への変換中に 1 つの HTML ページのマークアップをカスタム保存することに関連するデータのセットを表します。

```csharp
public class HtmlPageMarkupSavingInfo
```

## フィールド

| 名前 | 説明 |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/contentstream) | コンバータによって設定されます。ストリームとして保存された HTML を表します。 |
| [CustomProcessingCancelled](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/customprocessingcancelled) | 必要に応じてカスタムコードで設定する必要があります。このフラグは、何らかの理由で提供された HTML マークアップがカスタムコードではなく、コンバータのコード自体で標準的な方法で処理されるべき場合、カスタムコードで "true" に設定する必要があります。したがって、このフラグをカスタムコードで設定することは、カスタムコードが参照されたファイルを処理せず、コンバータがそれを自分で処理しなければならないことを意味します。 |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/htmlhostpagenumber) | コンバータによって設定されます。SplitToPages プロパティが設定されている場合、複数の HTML ファイル（変換されたページごとに 1 つの HTML ファイル）が作成されます。このプロパティは、保存された HTML ページのファイルの順序を含みます。このプロパティは、カスタムコードのロジックで HTML ページをどのように処理するか、またはどこに保存するかを決定するために使用できます。また、ページの分割がオフになっている場合、この値は常に '1' を含みます。なぜなら、その場合、全体のソースドキュメントに対して 1 つの大きな HTML ページのみが生成されるからです。 |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/pdfhostpagenumber) | コンバータによって設定されます。SplitToPages プロパティが設定されている場合、複数の HTML ファイル（変換されたページごとに 1 つの HTML ファイル）が作成されます。このプロパティは、保存された HTML マークアップが元の PDF のどのページから作成されたかをカスタムコードに伝えます。元のページ番号が何らかの理由で不明な場合や、SplitOnPages=false の場合、このプロパティは常に '0' を含み、コンバータが提供された HTML マークアップファイルに対して正確な元の PDF のページ番号を供給できないことを示します。 |
| [SupposedFileName](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/supposedfilename) | コンバータによって設定されます。コンバータからカスタムメソッドのコードに渡される想定ファイル名。カスタムコードでコンテンツをどのように処理するか、またはどこに保存するかを決定するために使用できます。 |

### 参照

* クラス [HtmlSaveOptions](../htmlsaveoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)