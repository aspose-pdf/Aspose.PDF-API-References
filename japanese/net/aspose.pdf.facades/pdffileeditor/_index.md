---
title: Class PdfFileEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileEditor クラス。PDFファイルの結合、分割、ページ抽出、ブックレット作成などの操作を実装します
type: docs
weight: 4460
url: /ja/net/aspose.pdf.facades/pdffileeditor/
---
## PdfFileEditor クラス

PDFファイルに対する操作を実装します: 結合、分割、ページ抽出、ブックレット作成など。

```csharp
public sealed class PdfFileEditor
```

## コンストラクタ

| Name | Description |
| --- | --- |
| [PdfFileEditor](pdffileeditor/)() | デフォルトコンストラクタ。 |

## プロパティ

| Name | Description |
| --- | --- |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams/) { get; set; } | true に設定されている場合、操作後にストリームが閉じられます。 |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize/) { get; set; } | UseDiskBuffer が true に設定されている場合、結合時に新しいインクリメンタルアップデートが行われる前に連結される文書の数。 |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog/) { get; } | 変換プロセスのログを取得します。 |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto/) { set; } | PDFファイル形式を設定します。結果ファイルは指定されたファイル形式で保存されます。このプロパティが指定されていない場合、ファイルは変換なしでデフォルトのPDF形式で保存されます。 |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure/) { get; set; } | true の場合、結合時にファイルの論理構造がコピーされます。 |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines/) { get; set; } | true の場合、アウトラインがコピーされます。 |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction/) { get; set; } | 結合プロセス中に破損したファイルに遭遇した場合の動作を定義します。可能な値は: StopWithError と ConcatenateIgnoringCorrupted です。 |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems/) { get; } | 結合が実行された際に発生した問題の配列です。Concatenate() 関数に渡された各破損ドキュメントごとに、新しい CorruptedItem エントリが作成されます。このプロパティは、CorruptedFileAction が ConcatenateIgnoringCorrupted の場合にのみ使用できます。 |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates/) { get; set; } | true の場合、結合中にインクリメンタルアップデートが行われます。 |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions/) { get; set; } | true の場合、アクションがソースドキュメントからコピーされます。デフォルト値 : true. |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique/) { get; set; } | true の場合、フォームが結合される際にフィールド名が一意になるように変更されます。フィールド名にはサフィックスが追加され、UniqueSuffix プロパティでサフィックスのテンプレートを指定できます。 |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception/) { get; } | 最後に発生した例外を取得します。失敗の理由を確認するために使用できます。 |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers/) { get; set; } | このプロパティが true の場合、同じ名前の結合されたドキュメントのオプションコンテンツが結果ドキュメント内で1つのレイヤーに統合されます。そうでない場合、同じ名前のレイヤーは結果ドキュメント内で別個のレイヤーとして保存されます。 |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines/) { get; set; } | true の場合、重複するアウトラインが統合されます。 |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize/) { get; set; } | 最適化フラグを取得または設定します。このフラグが設定されている場合、結果ファイル内の同一のリソースストリームは1つのPDFオブジェクトに統合されます。これにより、結果ファイルのサイズを削減できますが、実行が遅くなり、メモリ要件が増加する可能性があります。デフォルト値: false. |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword/) { get; set; } | ソースの入力PDFファイルが暗号化されている場合、所有者のパスワードを設定します。このプロパティはまだ実装されていません。 |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights/) { get; set; } | true の場合、最初のドキュメントのユーザー権限が結合されたドキュメントに適用され、他のドキュメントのユーザー権限は無視されます。 |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures/) { get; set; } | true の場合、署名はすべてフィールドから削除されます（フィールド自体は残ります）。さもなければ、無効な署名が残る可能性があります。 |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix/) { get; set; } | フォームが結合される際にフィールド名を一意にするために追加されるサフィックスの形式です。この文字列には、数字に置き換えられる %NUM% の部分文字列が含まれている必要があります。たとえば、UniqueSuffix = "ABC%NUM%" の場合、フィールド "fieldName" の名前は次のようになります: fieldNameABC1, fieldNameABC2, fieldNameABC3 など。 |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer/) { get; set; } | このオプションが使用される場合、出力ドキュメントは定期的にディスクに保存され、その後の結合はインクリメンタルアップデートとして適用されます。 |

## メソッド

| Name | Description |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins)(Stream, Stream, int[], double, double, double, double) | ページの内容のサイズを変更し、指定された余白を追加します。余白はデフォルトの単位で指定されます。 |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins_1)(string, string, int[], double, double, double, double) | ページの内容のサイズを変更し、指定された余白を追加します。余白はデフォルトの単位で指定されます。 |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct)(Stream, Stream, int[], double, double, double, double) | ページの内容のサイズを変更し、指定された余白を追加します。余白は初期ページサイズのパーセントで指定されます。 |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct_1)(string, string, int[], double, double, double, double) | ページの内容のサイズを変更し、指定された余白を追加します。余白は初期ページサイズのパーセントで指定されます。 |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak)(Document, Document, PageBreak[]) | ドキュメントのページにページブレークを追加します。 |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_1)(Stream, Stream, PageBreak[]) | ドキュメントのページにページブレークを追加します。 |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_2)(string, string, PageBreak[]) | ドキュメントのページにページブレークを追加します。 |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append)(Stream, Stream, int, int, Stream) | portStream から開始ページから終了ページまでの範囲で選択されたページを、firstInputStream の末尾に追加します。 |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_1)(Stream, Stream[], int, int, Stream) | portStreams のドキュメント配列から選択されたページを追加します。結果のドキュメントには、firstInputFile と portStreams のすべてのドキュメントの開始ページから終了ページまでのページが含まれます。 |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_2)(string, string, int, int, string) | portFile から開始ページから終了ページまでの範囲で選択されたページを、firstInputFile の末尾に追加します。 |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_3)(string, string[], int, int, string) | portFiles のドキュメントから選択されたページを追加します。結果のドキュメントには、firstInputFile と portFiles のすべてのドキュメントの開始ページから終了ページまでのページが含まれます。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate)(Document[], Document) | 文書を連結します。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_3)(Stream[], Stream) | ファイルを連結します。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_6)(string[], string) | ファイルを1つのファイルに連結します。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_1)(Stream, Stream, Stream) | 2つのファイルを連結します。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_4)(string, string, string) | 2つのファイルを連結します。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_2)(Stream, Stream, Stream, Stream) | 2つのPDFドキュメントを交互に配置し、空白ページで空欄を埋める新しいPDFドキュメントとして結合します。例: document1 が 5 ページ (p1, p2, p3, p4, p5) 、document2 が 3 ページ (p1', p2', p3') の場合、結合すると結果のドキュメントは p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage となります。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_5)(string, string, string, string) | 2つのPDFドキュメントを交互に配置し、空白ページで空欄を埋める新しいPDFドキュメントとして結合します。例: document1 が 5 ページ (p1, p2, p3, p4, p5) 、document2 が 3 ページ (p1', p2', p3') の場合、結合すると結果のドキュメントは p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage となります。 |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete)(Stream, int[], Stream) | 入力ファイルから指定された番号のページを削除し、新しいPDFファイルとして保存します。 |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete_1)(string, int[], string) | 入力ファイルから指定された番号のページを削除し、新しいPDFファイルとして保存します。 |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_1)(Stream, int[], Stream) | 指定された番号のページを抽出し、新しいPDFファイルとして保存します。 |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_3)(string, int[], string) | 指定された番号のページを抽出し、新しいPDFファイルとして保存します。 |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract)(Stream, int, int, Stream) | 入力ファイルからページを抽出し、新しいPDFファイルとして保存します。 |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_2)(string, int, int, string) | 入力ファイルからページを抽出し、新しいPDFファイルとして保存します。 |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_1)(Stream, int, Stream, int[], Stream) | 別のファイルからページを入力PDFファイルに挿入します。 |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_3)(string, int, string, int[], string) | 別のファイルからページを入力PDFファイルに挿入します。 |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert)(Stream, int, Stream, int, int, Stream) | 別のファイルからページを入力PDFファイルに挿入します。 |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_2)(string, int, string, int, int, string) | 指定した位置に別のファイルからページをPDFファイルに挿入します。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet)(Stream, Stream) | InputStream から outputStream にブックレットを作成します。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_4)(string, string) | 入力ファイルから出力ファイルへブックレットを作成します。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_1)(Stream, Stream, PageSize) | 入力ストリームからブックレットを作成し、結果を outputStream に保存します。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_5)(string, string, PageSize) | 入力ファイルから出力ファイルへブックレットを作成します。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_3)(Stream, Stream, int[], int[]) | firstInputStream から outputStream にカスタマイズされたブックレットを作成します。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_7)(string, string, int[], int[]) | firstInputFile から outputFile にカスタマイズされたブックレットを作成します。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_2)(Stream, Stream, PageSize, int[], int[]) | firstInputStream から outputStream にブックレットを作成します。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_6)(string, string, PageSize, int[], int[]) | firstInputFile から outputFile にカスタマイズされたブックレットを作成します。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_2)(Stream, Stream, Stream) | 2つの入力PDFストリームから outputStream にN-Upドキュメントを作成します。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_3)(Stream[], Stream, bool) | 複数の入力PDFストリームから outputStream にN-Upドキュメントを作成します。outputStream の各ページには、同じページ番号の入力ストリームのページが組み合わされた複数のページが含まれます。isSidewise が true の場合は水平に、false の場合は垂直に積み重ねられます。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_6)(string, string, string) | 2つの入力PDFファイルから outputFile にN-Upドキュメントを作成します。outputFile の各ページには、1つは最初の入力ファイル、もう1つは2番目の入力ファイルのページが含まれ、これらのページは水平に積み重ねられます。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_7)(string[], string, bool) | 複数の入力PDFファイルから outputFile にN-Upドキュメントを作成します。outputFile の各ページには、同じページ番号の入力ファイルのページが組み合わされた複数のページが含まれます。isSidewise が true の場合は水平に、false の場合は垂直に積み重ねられます。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup)(Stream, Stream, int, int) | 入力ストリームからN-Upドキュメントを作成し、結果を出力ストリームに保存します。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_4)(string, string, int, int) | firstInputFile から outputFile にN-Upドキュメントを作成します。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_1)(Stream, Stream, int, int, PageSize) | 最初の入力ストリームから出力ストリームにN-Upドキュメントを作成します。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_5)(string, string, int, int, PageSize) | 入力ファイルから outputFile にN-Upドキュメントを作成します。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_4)(Document, ContentsResizeParameters) | ドキュメントのページのサイズを変更します。縮小されたページの周囲に空白の余白が追加されます。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_5)(Document, int[], ContentsResizeParameters) | ドキュメントのページのサイズを変更します。縮小されたページの周囲に空白の余白が追加されます。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents)(Stream, Stream, int[], ContentsResizeParameters) | ドキュメントのページの内容のサイズを変更します。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_2)(string, string, int[], ContentsResizeParameters) | ドキュメント内のページの内容のサイズを変更します。ページが縮小される場合、ページの周囲に空白の余白が追加されます。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_1)(Stream, Stream, int[], double, double) | ドキュメントのページの内容のサイズを変更します。ページの内容を縮小し、余白を追加します。新しい内容のサイズはデフォルトの単位で指定されます。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_3)(string, string, int[], double, double) | ドキュメントのページの内容のサイズを変更します。ページの内容を縮小し、余白を追加します。新しい内容のサイズはデフォルトの単位で指定されます。 |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct)(Stream, Stream, int[], double, double) | ドキュメントのページの内容のサイズを変更します。ページの内容を縮小し、余白を追加します。新しい内容のサイズはパーセントで指定されます。 |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct_1)(string, string, int[], double, double) | ドキュメントのページの内容のサイズを変更します。ページの内容を縮小し、余白を追加します。新しい内容のサイズはパーセントで指定されます。 |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst)(Stream, int, Stream) | 開始から指定された位置までを分割し、前半部を出力ストリームに保存します。 |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst_1)(string, int, string) | PDFファイルを最初のページから指定された位置まで分割し、前半部を新しいファイルとして保存します。 |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks)(Stream, int[][]) | PDFファイルを複数のドキュメントに分割します。ドキュメントは単一ページまたは複数ページとなる場合があります。 |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks_1)(string, int[][]) | PDFファイルを複数のドキュメントに分割します。ドキュメントは単一ページまたは複数ページとなる場合があります。 |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend)(Stream, int, Stream) | 指定された位置から分割し、後半部を新しいファイルストリームとして保存します。 |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend_1)(string, int, string) | 指定された位置から分割し、後半部を新しいファイルとして保存します。 |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages)(Stream) | PDFファイルを単一ページのドキュメントに分割します。 |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_1)(string) | PDFファイルを単一ページのドキュメントに分割します。 |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_2)(Stream, string) | PDFファイルを単一ページのドキュメントに分割し、指定されたパスに保存します。パスはフィールド名テンプレートで指定されます。 |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_3)(string, string) | PDFファイルを単一ページのドキュメントに分割し、指定されたパスに保存します。パスはフィールド名テンプレートで指定されます。 |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend)(Stream, Stream[], int, int, Stream) | portStreams のドキュメント配列から選択されたページを追加します。結果のドキュメントには、firstInputFile と portStreams のすべてのドキュメントの開始ページから終了ページまでのページが含まれます。 |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend_1)(string, string[], int, int, string) | portFiles のドキュメントから選択されたページを追加します。結果のドキュメントには、firstInputFile と portFiles のすべてのドキュメントの開始ページから終了ページまでのページが含まれます。 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate)(Document[], Document) | ドキュメントを連結します。 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_2)(Stream[], Stream) | ファイルを連結します。 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_5)(string[], string) | ファイルを1つのファイルに連結します。 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_3)(string, string, string) | 2つのファイルを連結します。 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_1)(Stream, Stream, Stream, Stream) | 2つのPDFドキュメントを交互に配置し、空白ページで空欄を埋める新しいPDFドキュメントとして結合します。例: document1 が 5 ページ (p1, p2, p3, p4, p5) 、document2 が 3 ページ (p1', p2', p3') の場合、結合すると結果のドキュメントは p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage となります。 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_4)(string, string, string, string) | 2つのPDFドキュメントを交互に配置し、空白ページで空欄を埋める新しいPDFドキュメントとして結合します。例: document1 が 5 ページ (p1, p2, p3, p4, p5) 、document2 が 3 ページ (p1', p2', p3') の場合、結合すると結果のドキュメントは p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage となります。 |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete)(Stream, int[], Stream) | 入力ファイルから指定された番号のページを削除し、新しいPDFファイルとして保存します。 |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete_1)(string, int[], string) | 入力ファイルから指定された番号のページを削除し、新しいPDFファイルとして保存します。 |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract)(Stream, int[], Stream) | 指定された番号のページを抽出し、新しいPDFファイルとして保存します。 |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_2)(string, int[], string) | 指定された番号のページを抽出し、新しいPDFファイルとして保存します。 |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_1)(string, int, int, string) | 入力ファイルからページを抽出し、新しいPDFファイルとして保存します。 |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert)(Stream, int, Stream, int[], Stream) | 別のファイルからページを入力PDFファイルに挿入します。 |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert_1)(string, int, string, int[], string) | 別のファイルからページを入力PDFファイルに挿入します。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet)(Stream, Stream) | InputStream から outputStream にブックレットを作成します。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_4)(string, string) | 入力ファイルから出力ファイルへブックレットを作成します。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_1)(Stream, Stream, PageSize) | 入力ストリームからブックレットを作成し、結果を outputStream に保存します。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_5)(string, string, PageSize) | 入力ファイルから出力ファイルへブックレットを作成します。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_3)(Stream, Stream, int[], int[]) | firstInputStream から outputStream にカスタマイズされたブックレットを作成します。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_7)(string, string, int[], int[]) | firstInputFile から outputFile にカスタマイズされたブックレットを作成します。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_2)(Stream, Stream, PageSize, int[], int[]) | firstInputStream から outputStream にブックレットを作成します。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_6)(string, string, PageSize, int[], int[]) | firstInputFile から outputFile にカスタマイズされたブックレットを作成します。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_2)(Stream, Stream, Stream) | 2つの入力PDFストリームから outputStream にN-Upドキュメントを作成します。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_3)(Stream[], Stream, bool) | 複数の入力PDFストリームから outputStream にN-Upドキュメントを作成します。outputStream の各ページには、同じページ番号の入力ストリームのページが組み合わされた複数のページが含まれます。isSidewise が true の場合は水平に、false の場合は垂直に積み重ねられます。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_6)(string, string, string) | 2つの入力PDFファイルから outputFile にN-Upドキュメントを作成します。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_7)(string[], string, bool) | 複数の入力PDFファイルから outputFile にN-Upドキュメントを作成します。outputFile の各ページには、同じページ番号の入力ファイルのページが組み合わされた複数のページが含まれます。isSidewise が true の場合は水平に、false の場合は垂直に積み重ねられます。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup)(Stream, Stream, int, int) | 入力ストリームからN-Upドキュメントを作成し、結果を出力ストリームに保存します。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_4)(string, string, int, int) | firstInputFile から outputFile にN-Upドキュメントを作成します。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_1)(Stream, Stream, int, int, PageSize) | 最初の入力ストリームから出力ストリームにN-Upドキュメントを作成します。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_5)(string, string, int, int, PageSize) | 入力ファイルから outputFile にN-Upドキュメントを作成します。 |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents)(Stream, Stream, int[], ContentsResizeParameters) | ドキュメントのページの内容のサイズを変更します。 |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_2)(string, string, int[], ContentsResizeParameters) | ドキュメント内のページの内容のサイズを変更します。ページが縮小される場合、ページの周囲に空白の余白が追加されます。 |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_1)(Stream, Stream, int[], double, double) | ドキュメントのページの内容のサイズを変更します。ページの内容を縮小し、余白を追加します。新しい内容のサイズはデフォルトの単位で指定されます。 |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst)(Stream, int, Stream) | 開始から指定された位置までを分割し、前半部を出力ストリームに保存します。 |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst_1)(string, int, string) | PDFファイルを最初のページから指定された位置まで分割し、前半部を新しいファイルとして保存します。 |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend)(Stream, int, Stream) | 指定された位置から分割し、後半部を新しいファイルストリームとして保存します。 |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend_1)(string, int, string) | 指定された位置から分割し、後半部を新しいファイルとして保存します。 |

## その他のメンバー

| Name | Description |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](../../aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction) | 連結プロセス中に破損したファイルに遭遇した場合に実行されるアクション。 |
| class [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters) | ページリサイズパラメーターを指定するためのクラスです。以下のパラメーターを設定できます: 結果ページのサイズ（幅、高さ）をデフォルトの単位または初期ページサイズのパーセントで指定；左、上、下、右の余白をデフォルトの単位または初期ページサイズのパーセントで指定；一部の値は自動計算のために null のままにすることができます。これらの値は、明示的に指定された値の計算後に残りのページサイズから計算されます。例: ページ幅が 100 で新しいページ幅が 60 単位と指定された場合、左右の余白は自動的に (100 - 60) / 2 = 15 と計算されます。このクラスは ResizeContents メソッドで使用されます。 |
| class [ContentsResizeValue](../../aspose.pdf.facades/pdffileeditor.contentsresizevalue) | デフォルトの単位のパーセントで指定された余白またはコンテンツサイズの値。このクラスは ContentsResizeParameters で使用されます。 |
| class [CorruptedItem](../../aspose.pdf.facades/pdffileeditor.corrupteditem) | 連結時に破損したファイルに関する情報を提供するクラス。 |
| class [PageBreak](../../aspose.pdf.facades/pdffileeditor.pagebreak) | ページブレーク位置のデータ。 |

### 参照

* 名前空間 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../)