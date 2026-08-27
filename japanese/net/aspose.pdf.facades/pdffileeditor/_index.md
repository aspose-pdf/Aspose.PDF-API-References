---
title: "クラス PdfFileEditor"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Facades.PdfFileEditor クラス。PDF ファイルの結合、分割、ページ抽出、ブックレット作成などの操作を実装します。"
type: docs
weight: 4580
url: /ja/net/aspose.pdf.facades/pdffileeditor/
---
## PdfFileEditor class

PDF ファイルに対する操作（結合、分割、ページ抽出、ブックレット作成など）を実装します。

```csharp
public sealed class PdfFileEditor
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfFileEditor](pdffileeditor/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams/) { get; set; } | true に設定すると、操作後にストリームが閉じられます。 |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize/) { get; set; } | UseDiskBuffer が true に設定されている間に結合中に新しい増分更新が行われる前に結合されたドキュメントの数。 |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog/) { get; } | 変換プロセスのログを取得します。 |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto/) { set; } | PDF ファイル形式を設定します。結果ファイルは指定された形式で保存されます。このプロパティが指定されていない場合、ファイルは変換なしでデフォルトの PDF 形式で保存されます。 |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure/) { get; set; } | true の場合、結合が実行されるとファイルの論理構造がコピーされます。 |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines/) { get; set; } | true の場合、アウトラインがコピーされます。 |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction/) { get; set; } | このプロパティは、結合プロセスで破損したファイルに遭遇したときの動作を定義します。可能な値は: StopWithError と ConcatenateIgnoringCorrupted です。 |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems/) { get; } | 結合が実行されたときに発生した問題の配列です。Concatenate() 関数に渡された破損したドキュメントごとに新しい CorruptedItem エントリが作成されます。このプロパティは CorruptedFileAction が ConcatenateIgnoringCorrupted の場合にのみ使用できます。 |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates/) { get; set; } | true の場合、結合中に増分更新が行われます。 |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions/) { get; set; } | true の場合、アクションがソースドキュメントからコピーされます。デフォルト値: true。 |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique/) { get; set; } | true の場合、フォームが結合されるとフィールド名が一意にされます。フィールド名にサフィックスが追加され、サフィックスのテンプレートは UniqueSuffix プロパティで指定できます。 |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception/) { get; } | 最後に発生した例外を取得します。失敗の原因を確認するために使用できます。 |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers/) { get; set; } | このプロパティが true の場合、同名の結合されたドキュメントのオプションコンテンツは結果ドキュメントの 1 つのレイヤーにマージされます。false の場合、同名のレイヤーは別々のレイヤーとして結果ドキュメントに保存されます。 |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines/) { get; set; } | true の場合、重複したアウトラインがマージされます。 |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize/) { get; set; } | 最適化フラグを取得または設定します。このフラグが設定されている場合、結果ファイル内の同一リソースストリームは 1 つの PDF オブジェクトにマージされます。これにより結果ファイルのサイズを減らすことができますが、実行が遅くなりメモリ使用量が増加する可能性があります。デフォルト値: false。 |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword/) { get; set; } | ソース入力 PDF ファイルが暗号化されている場合に所有者パスワードを設定します。このプロパティはまだ実装されていません。 |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights/) { get; set; } | true の場合、最初のドキュメントのユーザー権限が結合されたドキュメントに適用されます。他のすべてのドキュメントのユーザー権限は無視されます。 |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures/) { get; set; } | true の場合、すべての署名がフィールドから削除されます（フィールドは残ります）。false の場合、無効な署名が残る可能性があります。 |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix/) { get; set; } | フォームが結合される際にフィールド名を一意にするために追加されるサフィックスの形式。この文字列は %NUM% サブストリングを含む必要があり、数字に置き換えられます。例えば UniqueSuffix = \"ABC%NUM%\" の場合、フィールド \"fieldName\" の名前は fieldNameABC1、fieldNameABC2、fieldNameABC3 などになります。 |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer/) { get; set; } | このオプションを使用すると、宛先ドキュメントが定期的にディスクに保存され、以降の結合は増分更新として適用されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins)(Stream, Stream, int[], double, double, double, double) | ページ内容のサイズを変更し、指定された余白を追加します。余白はデフォルトの空間単位で指定されます。 |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins_1)(string, string, int[], double, double, double, double) | ページ内容のサイズを変更し、指定された余白を追加します。余白はデフォルトの空間単位で指定されます。 |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct)(Stream, Stream, int[], double, double, double, double) | ページ内容のサイズを変更し、指定された余白を追加します。余白は初期ページサイズのパーセンテージで指定されます。 |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct_1)(string, string, int[], double, double, double, double) | ページ内容のサイズを変更し、指定された余白を追加します。余白は初期ページサイズのパーセンテージで指定されます。 |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak)(Document, Document, PageBreak[]) | ドキュメントページに改ページを追加します。 |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_1)(Stream, Stream, PageBreak[]) | ドキュメントページに改ページを追加します。 |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_2)(string, string, PageBreak[]) | ドキュメントページに改ページを追加します。 |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append)(Stream, Stream, int, int, Stream) | portStream から startPage から endPage の範囲で選択されたページを、firstInputStream の末尾にある portStream に追加します。 |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_1)(Stream, Stream[], int, int, Stream) | portStreams のドキュメント配列から選択されたページを追加します。結果のドキュメントには firstInputFile と、portStreams のすべてのドキュメントの startPage から endPage の範囲のページが含まれます。 |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_2)(string, string, int, int, string) | portFile から startPage から endPage の範囲で選択されたページを、firstInputFile の末尾にある portFile に追加します。 |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_3)(string, string[], int, int, string) | portFiles のドキュメントから選択されたページを追加します。結果のドキュメントには firstInputFile と、portFiles のすべてのドキュメントの startPage から endPage の範囲のページが含まれます。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate)(Document[], Document) | ドキュメントを連結します。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_3)(Stream[], Stream) | ファイルを連結します。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_6)(string[], string) | ファイルを1つのファイルに連結します。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_1)(Stream, Stream, Stream) | 2つのファイルを連結します。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_4)(string, string, string) | 2つのファイルを連結します。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_2)(Stream, Stream, Stream, Stream) | 2つの Pdf ドキュメントを交互にページを配置し、空白の場所を空白ページで埋めた新しい Pdf ドキュメントに結合します。例: document1 は 5 ページ (p1, p2, p3, p4, p5) を持ち、document2 は 3 ページ (p1', p2', p3') を持ちます。2つの Pdf ドキュメントを結合すると、結果のドキュメントはページ順に p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage となります。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_5)(string, string, string, string) | 2つの Pdf ドキュメントを交互にページを配置し、空白の場所を空白ページで埋めた新しい Pdf ドキュメントに結合します。例: document1 は 5 ページ (p1, p2, p3, p4, p5) を持ち、document2 は 3 ページ (p1', p2', p3') を持ちます。2つの Pdf ドキュメントを結合すると、結果のドキュメントはページ順に p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage となります。 |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete)(Stream, int[], Stream) | 入力ファイルから番号配列で指定されたページを削除し、新しい Pdf ファイルとして保存します。 |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete_1)(string, int[], string) | 入力ファイルから番号配列で指定されたページを削除し、新しい Pdf ファイルとして保存します。 |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_1)(Stream, int[], Stream) | 番号配列で指定されたページを抽出し、新しい Pdf ファイルとして保存します。 |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_3)(string, int[], string) | 番号配列で指定されたページを抽出し、新しい PDF ファイルとして保存します。 |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract)(Stream, int, int, Stream) | 入力ファイルからページを抽出し、新しい Pdf ファイルとして保存します。 |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_2)(string, int, int, string) | 入力ファイルからページを抽出し、新しい Pdf ファイルとして保存します。 |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_1)(Stream, int, Stream, int[], Stream) | 別のファイルからページを挿入し、入力 Pdf ファイルに追加します。 |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_3)(string, int, string, int[], string) | 別のファイルからページを挿入し、入力 Pdf ファイルに追加します。 |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert)(Stream, int, Stream, int, int, Stream) | 別のファイルからページを挿入し、入力 Pdf ファイルに追加します。 |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_2)(string, int, string, int, int, string) | 別のファイルからページを挿入し、Pdf ファイルの指定位置に追加します。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet)(Stream, Stream) | InputStream から outputStream へブックレットを作成します。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_4)(string, string) | 入力ファイルから出力ファイルへブックレットを作成します。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_1)(Stream, Stream, PageSize) | 入力ストリームからブックレットを作成し、結果を出力ストリームに保存します。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_5)(string, string, PageSize) | inputFile から outputFile へブックレットを作成します。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_3)(Stream, Stream, int[], int[]) | firstInputStream から outputStream へカスタマイズされたブックレットを作成します。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_7)(string, string, int[], int[]) | firstInputFile から outputFile へカスタマイズされたブックレットを作成します。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_2)(Stream, Stream, PageSize, int[], int[]) | firstInputStream から outputStream へブックレットを作成します。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_6)(string, string, PageSize, int[], int[]) | firstInputFile から outputFile へカスタマイズされたブックレットを作成します。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_2)(Stream, Stream, Stream) | 2つの入力 PDF ストリームから outputStream へ N-Up ドキュメントを作成します。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_3)(Stream[], Stream, bool) | 複数の入力 PDF ストリームから outputStream へ N-Up ドキュメントを作成します。outputStream の各ページは、同じページ番号の入力ストリームのページを組み合わせた複数ページを含みます。isSidewise が true の場合は横方向に、false の場合は縦方向にページが積み重ねられます。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_6)(string, string, string) | 2つの入力 PDF ファイルから outputFile へ N-Up ドキュメントを作成します。outputFile の各ページは2ページを含み、1ページは最初の入力ファイルから、もう1ページは2番目の入力ファイルから取られます。これらの2ページは横方向に並べられます。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_7)(string[], string, bool) | 複数の入力 PDF ファイルから N-Up ドキュメントを作成し、outputFile に出力します。outputFile の各ページには、同じページ番号の入力ファイルのページを組み合わせた複数ページが含まれます。isSidewise が true の場合はページが横方向に積み重ねられ、false の場合は縦方向に積み重ねられます。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup)(Stream, Stream, int, int) | 入力ストリームから N-Up ドキュメントを作成し、結果を出力ストリームに保存します。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_4)(string, string, int, int) | firstInputFile から N-Up ドキュメントを作成し、outputFile に出力します。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_1)(Stream, Stream, int, int, PageSize) | 最初の入力ストリームから N-Up ドキュメントを作成し、出力ストリームに出力します。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_5)(string, string, int, int, PageSize) | 入力ファイルから N-Up ドキュメントを作成し、outputFile に出力します。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_4)(Document, ContentsResizeParameters) | ドキュメントのページサイズを変更します。縮小されたページの周囲に空白の余白が追加されます。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_5)(Document, int[], ContentsResizeParameters) | ドキュメントのページサイズを変更します。縮小されたページの周囲に空白の余白が追加されます。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents)(Stream, Stream, int[], ContentsResizeParameters) | ドキュメントのページ内容のサイズを変更します。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_2)(string, string, int[], ContentsResizeParameters) | ドキュメント内のページ内容のサイズを変更します。ページが縮小された場合、ページの周囲に空白の余白が追加されます。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_1)(Stream, Stream, int[], double, double) | ドキュメントページの内容のサイズを変更します。ページの内容を縮小し、余白を追加します。新しい内容のサイズはデフォルトの空間単位で指定されます。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_3)(string, string, int[], double, double) | ドキュメントページの内容のサイズを変更します。ページの内容を縮小し、余白を追加します。新しい内容のサイズはデフォルトの空間単位で指定されます。 |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct)(Stream, Stream, int[], double, double) | ドキュメントページの内容のサイズを変更します。ページの内容を縮小し、余白を追加します。新しい内容のサイズはパーセンテージで指定されます。 |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct_1)(string, string, int[], double, double) | ドキュメントページの内容のサイズを変更します。ページの内容を縮小し、余白を追加します。新しい内容のサイズはパーセンテージで指定されます。 |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst)(Stream, int, Stream) | 開始位置から指定された位置まで分割し、前半部分を出力ストリームに保存します。 |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst_1)(string, int, string) | Pdf ファイルを最初のページから指定された位置まで分割し、前半部分を新しいファイルとして保存します。 |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks)(Stream, int[][]) | Pdf ファイルを複数のドキュメントに分割します。ドキュメントは単一ページまたは複数ページにすることができます。 |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks_1)(string, int[][]) | Pdf ファイルを複数のドキュメントに分割します。ドキュメントは単一ページまたは複数ページにすることができます。 |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend)(Stream, int, Stream) | 指定された位置から分割し、後半部分を新しいファイルストリームとして保存します。 |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend_1)(string, int, string) | 位置から分割し、後半部分を新しいファイルとして保存します。 |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages)(Stream) | Pdf ファイルを単一ページのドキュメントに分割します。 |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_1)(string) | PDF ファイルを単一ページのドキュメントに分割します。 |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_2)(Stream, string) | Pdf ファイルを単一ページのドキュメントに分割し、指定されたパスに保存します。パスはフィールド名 temaplate によって指定されます。 |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_3)(string, string) | Pdf ファイルを単一ページのドキュメントに分割し、指定されたパスに保存します。パスはフィールド名 temaplate によって指定されます。 |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend)(Stream, Stream[], int, int, Stream) | portStreams のドキュメント配列から選択されたページを追加します。結果のドキュメントには firstInputFile と、portStreams のすべてのドキュメントの startPage から endPage の範囲のページが含まれます。 |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend_1)(string, string[], int, int, string) | portFiles のドキュメントから選択されたページを追加します。結果のドキュメントには firstInputFile と、portFiles のすべてのドキュメントの startPage から endPage の範囲のページが含まれます。 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate)(Document[], Document) | ドキュメントを連結します。 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_2)(Stream[], Stream) | ファイルを連結します。 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_5)(string[], string) | ファイルを1つのファイルに連結します。 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_3)(string, string, string) | 2つのファイルを連結します。 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_1)(Stream, Stream, Stream, Stream) | 2つの Pdf ドキュメントを交互にページを配置し、空白の場所を空白ページで埋めた新しい Pdf ドキュメントに結合します。例: document1 は 5 ページ (p1, p2, p3, p4, p5) を持ち、document2 は 3 ページ (p1', p2', p3') を持ちます。2つの Pdf ドキュメントを結合すると、結果のドキュメントはページ順に p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage となります。 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_4)(string, string, string, string) | 2つの Pdf ドキュメントを交互にページを配置し、空白の場所を空白ページで埋めた新しい Pdf ドキュメントに結合します。例: document1 は 5 ページ (p1, p2, p3, p4, p5) を持ち、document2 は 3 ページ (p1', p2', p3') を持ちます。2つの Pdf ドキュメントを結合すると、結果のドキュメントはページ順に p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage となります。 |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete)(Stream, int[], Stream) | 入力ファイルから番号配列で指定されたページを削除し、新しい Pdf ファイルとして保存します。 |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete_1)(string, int[], string) | 入力ファイルから番号配列で指定されたページを削除し、新しい Pdf ファイルとして保存します。 |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract)(Stream, int[], Stream) | 番号配列で指定されたページを抽出し、新しい Pdf ファイルとして保存します。 |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_2)(string, int[], string) | 番号配列で指定されたページを抽出し、新しい PDF ファイルとして保存します。 |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_1)(string, int, int, string) | 入力ファイルからページを抽出し、新しい Pdf ファイルとして保存します。 |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert)(Stream, int, Stream, int[], Stream) | 別のファイルからページを挿入し、入力 Pdf ファイルに追加します。 |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert_1)(string, int, string, int[], string) | 別のファイルからページを挿入し、入力 Pdf ファイルに追加します。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet)(Stream, Stream) | InputStream から outputStream へブックレットを作成します。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_4)(string, string) | 入力ファイルから出力ファイルへブックレットを作成します。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_1)(Stream, Stream, PageSize) | 入力ストリームからブックレットを作成し、結果を出力ストリームに保存します。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_5)(string, string, PageSize) | inputFile から outputFile へブックレットを作成します。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_3)(Stream, Stream, int[], int[]) | firstInputStream から outputStream へカスタマイズされたブックレットを作成します。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_7)(string, string, int[], int[]) | firstInputFile から outputFile へカスタマイズされたブックレットを作成します。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_2)(Stream, Stream, PageSize, int[], int[]) | firstInputStream から outputStream へブックレットを作成します。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_6)(string, string, PageSize, int[], int[]) | firstInputFile から outputFile へカスタマイズされたブックレットを作成します。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_2)(Stream, Stream, Stream) | 2つの入力 PDF ストリームから outputStream へ N-Up ドキュメントを作成します。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_3)(Stream[], Stream, bool) | 複数の入力 PDF ストリームから outputStream へ N-Up ドキュメントを作成します。outputStream の各ページは、同じページ番号の入力ストリームのページを組み合わせた複数ページを含みます。isSidewise が true の場合は横方向に、false の場合は縦方向にページが積み重ねられます。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_6)(string, string, string) | 2つの入力 PDF ファイルから outputFile へ N-Up ドキュメントを作成します。outputFile の各ページは2ページを含み、1ページは最初の入力ファイルから、もう1ページは2番目の入力ファイルから取られます。これらの2ページは横方向に並べられます。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_7)(string[], string, bool) | 複数の入力 PDF ファイルから N-Up ドキュメントを作成し、outputFile に出力します。outputFile の各ページには、同じページ番号の入力ファイルのページを組み合わせた複数ページが含まれます。isSidewise が true の場合はページが横方向に積み重ねられ、false の場合は縦方向に積み重ねられます。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup)(Stream, Stream, int, int) | 入力ストリームから N-Up ドキュメントを作成し、結果を出力ストリームに保存します。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_4)(string, string, int, int) | firstInputFile から N-Up ドキュメントを作成し、outputFile に出力します。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_1)(Stream, Stream, int, int, PageSize) | 最初の入力ストリームから N-Up ドキュメントを作成し、出力ストリームに出力します。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_5)(string, string, int, int, PageSize) | 入力ファイルから N-Up ドキュメントを作成し、outputFile に出力します。 |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents)(Stream, Stream, int[], ContentsResizeParameters) | ドキュメントのページ内容のサイズを変更します。 |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_2)(string, string, int[], ContentsResizeParameters) | ドキュメント内のページ内容のサイズを変更します。ページが縮小された場合、ページの周囲に空白の余白が追加されます。 |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_1)(Stream, Stream, int[], double, double) | ドキュメントページの内容のサイズを変更します。ページの内容を縮小し、余白を追加します。新しい内容のサイズはデフォルトの空間単位で指定されます。 |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst)(Stream, int, Stream) | 開始位置から指定された位置まで分割し、前半部分を出力ストリームに保存します。 |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst_1)(string, int, string) | Pdf ファイルを最初のページから指定された位置まで分割し、前半部分を新しいファイルとして保存します。 |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend)(Stream, int, Stream) | 指定された位置から分割し、後半部分を新しいファイルストリームとして保存します。 |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend_1)(string, int, string) | 位置から分割し、後半部分を新しいファイルとして保存します。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](../../aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction) | 結合プロセスで破損したファイルに遭遇したときに実行されるアクションです。 |
| class [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters) | ページサイズ変更パラメータを指定するクラスです。次のパラメータを設定できます：結果ページのサイズ（幅、高さ）をデフォルトの空間単位または元のページサイズのパーセンテージで指定；左、上、下、右の余白をデフォルトの空間単位または元のページサイズのパーセンテージで指定；自動計算のために null のままにできる値があります。これらの値は、明示的に指定された値を除いた残りのページサイズから計算されます。例：ページ幅が 100 で新しいページ幅が 60 単位の場合、左と右の余白は自動的に (100 - 60) / 2 = 15 と計算されます。このクラスは ResizeContents メソッドで使用されます。 |
| class [ContentsResizeValue](../../aspose.pdf.facades/pdffileeditor.contentsresizevalue) | デフォルト空間単位のパーセントで指定された余白またはコンテンツサイズの値。このクラスは ContentsResizeParameters で使用されます。 |
| class [CorruptedItem](../../aspose.pdf.facades/pdffileeditor.corrupteditem) | 連結時に破損したファイルに関する情報を提供するクラスです。 |
| class [PageBreak](../../aspose.pdf.facades/pdffileeditor.pagebreak) | ページ区切り位置のデータです。 |

### 関連項目

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


