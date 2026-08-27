---
title: "PdfFileEditor"
linktitle: "PdfFileEditor"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ファイルに対する操作（結合、分割、ページ抽出、ブックレット作成など）を実装します。"
type: docs
weight: 410
url: /ja/java/com.aspose.pdf.facades/pdffileeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfFileEditor

**All Implemented Interfaces:**
IPdfFileEditor

```
public final class PdfFileEditor extends Object implements IPdfFileEditor
```

PDF ファイルに対する操作（結合、分割、ページ抽出、ブックレット作成など）を実装します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfFileEditor](#PdfFileEditor--) | PdfFileEditor のコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | <p> ページ内容のサイズを変更し、指定された余白を追加します。余白はデフォルトの空間単位で指定されます。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMargins(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); dest.Close(); </pre> |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | <p> ページ内容のサイズを変更し、指定された余白を追加します。余白はデフォルトの空間単位で指定されます。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMargins(\"input.pdf\", \"output.pdf\", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); </pre> |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | <p> ページ内容のサイズを変更し、指定された余白を追加します。余白はページの初期サイズのパーセントで指定されます。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileInputStream(\"output.pdf\"); fileEditor.addMarginsPct(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); dest.close(); </pre> |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | <p> ページ内容のサイズを変更し、指定された余白を追加します。余白はページの初期サイズのパーセントで指定されます。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMarginsPct(\"input.pdf\", \"output.pdf\", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); </pre> |
| [addPageBreak](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | ドキュメントのページに改ページを追加します。 |
| [addPageBreak](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | ドキュメントのページに改ページを追加します。 |
| [addPageBreak](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | ドキュメントのページに改ページを追加します。 |
| [addPageBreak](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | ドキュメントのページに改ページを追加します。 |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | <p> ポートストリームのドキュメント配列から選択されたページを追加します。結果のドキュメントには firstInputFile と、portStreams のすべてのドキュメントの startPage から endPage の範囲のページが含まれます。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream(\"input.pdf\"); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OtputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream); </pre> |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | <p> portStream から startPage から endPage の範囲で選択されたページを、firstInputStream の末尾に追加します。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream(\"input.pdf\"); InputStream stream1 = new FileInputStream(\"file1.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.append(instream, stream1, 3, 5, outstream); </pre> |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | <p> portFiles のドキュメントから選択されたページを追加します。結果のドキュメントには firstInputFile と、portFiles のすべてのドキュメントの startPage から endPage の範囲のページが含まれます。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append(\"input.pdf\", new string[] { \"file1.pdf\", \"file2.pdf\"}, 3, 5, \"outfile.pdf\"); </pre> |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | <p> portFile から startPage から endPage の範囲で選択されたページを、firstInputFile の末尾に追加します。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append(\"input.pdf\", \"file1.pdf\", 3, 5, \"outfile.pdf\"); </pre> |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | ドキュメントを連結します。 |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | <p> ファイルを連結します </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream); </pre> |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> 2つの PDF ドキュメントを交互にページを配置し、空白の場所を空白ページで埋めて新しい PDF ドキュメントに結合します。例: document1 は 5 ページ: p1, p2, p3, p4, p5。document2 は 3 ページ: p1', p2', p3'。2 つの PDF ドキュメントを結合すると、結果のドキュメントはページ:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage の順になります。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); InputStream blank = new FileInputStream(\"blank.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream); </pre> |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> 2つのファイルを連結します。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(stream1, stream2, outstream); </pre> |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | <p> 複数のファイルを1つのファイルに連結します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(new String[] { \"src1.pdf\", \"src2.pdf\" }, \"dest.pdf\"); </pre> |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | <p> 2つのファイルを連結します。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.concatenate(\"file1.pdf\", \"file2.pdf\", \"outfile.pdf\"); </pre> |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | <p> 2つの PDF ドキュメントを交互にページを配置し、空白の場所を空白ページで埋めて新しい PDF ドキュメントに結合します。例: document1 は 5 ページ: p1, p2, p3, p4, p5。document2 は 3 ページ: p1', p2', p3'。2 つの PDF ドキュメントを結合すると、結果のドキュメントはページ:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage の順になります。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(\"src1.pdf\", \"src2.pdf\", \"blank.pdf\", \"dest.pdf\"); </pre> |
| [createArrayWithExclusion](#createArrayWithExclusion-int-int-) |  |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | <p> 入力ファイルから番号配列で指定されたページを削除し、新しい Pdf ファイルとして保存します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream intputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileInputStream(\"output.pdf\"); pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream); </pre> |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | <p> 入力ファイルから番号配列で指定されたページを削除し、新しい Pdf ファイルとして保存します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.delete(\"input.pdf\", new int[] { 2, 3 }, \"out.pdf\"); </pre> |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | <p> 数値配列で指定されたページを抽出し、新しい Pdf ファイルとして保存します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream); </pre> |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | <p> 入力ファイルからページを抽出し、新しい Pdf ファイルとして保存します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.extract(sourceStream, 1, 3, 6, outStream); </pre> |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | <p> 数値配列で指定されたページを抽出し、新しい PDF ファイルとして保存します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf"); </pre> |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | <p> 入力ファイルからページを抽出し、新しい Pdf ファイルとして保存します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.Extract("input.pdf", 3, 7, "output.pdf"); </pre> |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | <p> true に設定すると、エラーが発生した場合に例外がスローされます。false に設定すると例外はスローされず、失敗した場合はメソッドが false を返します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre> |
| [getAttachmentName](#getAttachmentName--) | 操作の結果が HttpServletResponse オブジェクトに添付ファイルとして格納されるときの添付ファイル名を取得します。 |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | true に設定すると、操作後にストリームが閉じられます。 |
| [getConcatenationPacketSize](#getConcatenationPacketSize--) | UseDiskBuffer が true に設定されている場合、連結中に新しい増分更新が行われるまでに連結されたドキュメント数を示します。 |
| [getContentDisposition](#getContentDisposition--) | 操作の結果が HttpServletResponse オブジェクトに格納されるときのコンテンツ保存方法を取得します。可能な値: inline / attachment。デフォルト: inline。 |
| [getConversionLog](#getConversionLog--) | 変換プロセスのログを取得します。 |
| [getCopyLogicalStructure](#getCopyLogicalStructure--) | true の場合、連結が実行されるときにファイルの論理構造がコピーされます。 |
| [getCopyOutlines](#getCopyOutlines--) | true の場合、アウトラインがコピーされます。 |
| [getCorruptedFileAction](#getCorruptedFileAction--) | このプロパティは、連結処理中に破損したファイルに遭遇したときの動作を定義します。可能な値は: StopWithError と ConcatenateIgnoringCorrupted です。 |
| [getCorruptedItems](#getCorruptedItems--) | <p> 連結が実行されたときに発生した問題の配列です。Concatenate() 関数に渡された破損したドキュメントごとに新しい CorruptedItem エントリが作成されます。このプロパティは CorruptedFileAction が ConcatenateIgnoringCorrupted の場合にのみ使用できます。 </p> <hr> <pre> //concatenate documents and show information about corrupted documents PdfFileEditor pfe = new PdfFileEditor(); pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted); {@code if (pfe.getCorruptedItems().length >0)} { for(PdfFileEditor.CorruptedItem item : pfe.getCorruptedItems()) { System.out.println(item.getIndex()+ " reason: " + item.getException()); } } </pre> |
| [getCustomProgressConcatenationHandler](#getCustomProgressConcatenationHandler--) | 連結中に動作し、内部連結ステージのイベントを外部顧客コードに変換する内部プログレスイベントプロセッサの表現です。 |
| [getIncrementalUpdates](#getIncrementalUpdates--) | true の場合、連結中に増分更新が行われます。 |
| [getKeepActions](#getKeepActions--) | true の場合、アクションがソースドキュメントからコピーされます。 |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | true の場合、フォームが連結される際にフィールド名が一意になるようにします。サフィックスがフィールド名に付加され、サフィックステンプレートは UniqueSuffix プロパティで指定できます。 |
| [getLastException](#getLastException--) | 最後に発生した例外を取得します。 |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | このプロパティが true の場合、同名の連結ドキュメントのオプションコンテンツが結果ドキュメントの1つのレイヤーにマージされます。 |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | true の場合、重複したアウトラインがマージされます。 |
| [getOptimizeSize](#getOptimizeSize--) | 最適化フラグを取得または設定します。 |
| [getOwnerPassword](#getOwnerPassword--) | ソース入力 Pdf ファイルが暗号化されている場合の所有者パスワードを取得します。このプロパティはまだ実装されていません。 |
| [getPreserveUserRights](#getPreserveUserRights--) | true の場合、最初のドキュメントのユーザー権限が連結ドキュメントに適用されます。 |
| [getRemoveSignatures](#getRemoveSignatures--) | true の場合、すべての署名がフィールドから削除されます（フィールドは残ります）。そうでない場合、無効な署名が残る可能性があります。 |
| [getSaveOptions](#getSaveOptions--) | 結果が HttpServletResponse として保存されるときの保存オプションを取得または設定します。デフォルト値: PdfSaveOptions。 |
| [getUniqueSuffix](#getUniqueSuffix--) | フィールド名が一意になるように連結されたフォームでフィールド名に付加されるサフィックスの形式を取得します。この文字列は %NUM% の部分文字列を含んでおり、数字に置き換えられます。例えば UniqueSuffix = "ABC%NUM%" の場合、フィールド "fieldName" の名前は: fieldNameABC1, fieldNameABC2, fieldNameABC3 などになります。 |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | <p> 他のファイルからページを挿入して、入力 PDF ファイルに追加します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileoutputStream("out.pdf"); pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream); </pre> |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | <p> 他のファイルからページを挿入して、入力 PDF ファイルに追加します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre> |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | <p> 他のファイルからページを挿入して、入力 PDF ファイルに追加します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre> |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | <p> 別のファイルからページを挿入して、PDF ファイルの指定位置に追加します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf"); </pre> |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | PDF には、ページや表セルの背景画像が、同一のタイル背景画像を複数隣り合わせに配置して構成されていることがあります。 |
| [isUseDiskBuffer](#isUseDiskBuffer--) | このオプションを使用すると、宛先ドキュメントが定期的にディスクに保存され、以降の連結は増分更新として適用されます。 |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | <p> InputStream から outputStream へブックレットを作成します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | <p> firstInputStream から outputStream へカスタマイズされたブックレットを作成します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | <p> 入力ストリームからブックレットを作成し、結果を出力ストリームに保存します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | <p> firstInputStream から outputStream へブックレットを作成します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | <p> 入力ファイルから出力ファイルへブックレットを作成します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf"); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | <p> firstInputFile から outputFile へカスタマイズされたブックレットを作成します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | <p> inputFile から outputFile へブックレットを作成します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | <p> firstInputFile から outputFile へカスタマイズされたブックレットを作成します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | <p> 複数の入力 PDF ストリームから outputStream へ N-Up ドキュメントを作成します。outputStream の各ページには、同じページ番号の入力ストリームのページと組み合わせた複数ページが含まれます。isSidewise が true の場合はページが横方向に積み重ねられ、false の場合は縦方向に積み重ねられます。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream stream1 = new FileInputStream("input1.pdf"); InputStream stream2 = new FileInputStream("input2.pdf"); InputStream stream3 = new FileInputStream("input3.pdf"); OutputStream output = new FileOutputStream("output.pdf"); pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> 2 つの入力 PDF ストリームから outputStream へ N-Up ドキュメントを作成します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream input1 = new FileInputStream("input1.pdf"); InputStream input2 = new FileInputStream("input2.pdf"); OutputStream output = new FileOutputStream("output.pdf"); pfe.makeNUp(input1, input2, output); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | <p> 入力ストリームから N-Up ドキュメントを作成し、結果を出力ストリームに保存します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeNUp(inputStream, outputStream, 3, 3); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | <p> 最初の入力ストリームから出力ストリームへ N-Up ドキュメントを作成します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4); </pre> |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | <p> 複数の入力 PDF ファイルから N-Up 文書を作成し、outputFile に出力します。outputFile の各ページは、同じページ番号の入力ファイルのページを組み合わせた複数ページを含みます。isSidewise が true の場合は横方向に、false の場合は縦方向にページが並べられます。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(new String[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | <p> 最初の入力ファイルから N-Up 文書を作成し、outputFile に出力します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input.pdf", "output.pdf", 3, 3); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | <p> 入力ファイルから N-Up 文書を作成し、outputFile に出力します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | <p> 2 つの入力 PDF ファイルから N-Up 文書を作成し、outputFile に出力します。outputFile の各ページは 2 ページを含み、1 ページは最初の入力ファイルから、もう 1 ページは 2 番目の入力ファイルから取得されます。これら 2 ページは横方向に並べられます。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input1.pdf", "input2.pdf", "output.pdf"); </pre> |
| [resizeContents](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | ドキュメントのページサイズを変更します。 |
| [resizeContents](#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | ドキュメントのページサイズを変更します。 |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | <p> ドキュメントページの内容をリサイズします。ページの内容を縮小し、余白を追加します。内容の新しいサイズはデフォルトの空間単位で指定されます。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileOutputStream("output.pdf"); fileEditor.resizeContents(src, dest, //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre> |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | ドキュメントのページの内容をリサイズします。 |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | <p> ドキュメントページの内容をリサイズします。ページの内容を縮小し、余白を追加します。内容の新しいサイズはデフォルトの空間単位で指定されます。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizeContents("input.pdf", "output.pdf", //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre> |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | ドキュメント内のページの内容をリサイズします。 |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | <p> ドキュメントページの内容をリサイズします。ページの内容を縮小し、余白を追加します。新しい内容サイズはパーセンテージで指定されます。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileOutputStream("output.pdf"); fileEditor.resizePct(src, dest, //resize all pages of document null, //new contents width = 60% of initial size 60, //new contents height = 60% of initial size 60); // Rest area of page will be empty (page margins). Size of left and right margins is (100% - 60%) / 2 = 20% // The same for top and bottom margins. </pre> |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | <p> ドキュメントページの内容をリサイズします。ページの内容を縮小し、余白を追加します。新しい内容サイズはパーセンテージで指定されます。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizePct("input.pdf", "output.pdf", //resize all pages of document null, //new contents width = 60% of initial size 60, //new contents height = 60% of initial size 60); // Rest area of page will be empty (page margins). Size of left and right margins is (100% - 60%) / 2 = 20% // The same for top and bottom margins. </pre> |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | ドキュメントのページサイズを変更します。 |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | ドキュメントのページサイズを変更します。 |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | <p> true に設定すると、エラーが発生した場合に例外がスローされます。false に設定すると、例外はスローされず、失敗した場合はメソッドが false を返します。 </p> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | 操作の結果が HttpServletResponse オブジェクトに添付ファイルとして保存されるときの添付ファイル名を設定します。 |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | <p> true に設定すると、操作後にストリームが閉じられます。 </p> |
| [setConcatenationPacketSize](#setConcatenationPacketSize-int-) | UseDiskBuffer が true に設定されている場合、連結中に新しい増分更新が行われるまでに連結されたドキュメント数を示します。 |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | 操作の結果が HttpServletResponse オブジェクトに保存されるときのコンテンツ保存方法を設定します。可能な値: inline / attachment。デフォルト: inline。 |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | PDF ファイル形式を設定します。結果ファイルは指定された形式で保存されます。このプロパティが指定されていない場合、ファイルは変換せずにデフォルトの PDF 形式で保存されます。 |
| [setCopyLogicalStructure](#setCopyLogicalStructure-boolean-) | true の場合、連結が実行されるときにファイルの論理構造がコピーされます。 |
| [setCopyOutlines](#setCopyOutlines-boolean-) | true の場合、アウトラインがコピーされます。 |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | このプロパティは、連結処理中に破損したファイルに遭遇したときの動作を定義します。可能な値は: StopWithError と ConcatenateIgnoringCorrupted です。 |
| [setCustomProgressConcatenationHandler](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | 連結中に動作し、内部連結ステージのイベントを外部顧客コードに変換する内部プログレスイベントプロセッサの表現です。 |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | true の場合、連結中に増分更新が行われます。 |
| [setKeepActions](#setKeepActions-boolean-) | true の場合、アクションがソースドキュメントからコピーされます。 |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | true の場合、フォームが連結される際にフィールド名が一意になるようにします。サフィックスがフィールド名に付加され、サフィックステンプレートは UniqueSuffix プロパティで指定できます。 |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | このプロパティが true の場合、同名の連結ドキュメントのオプションコンテンツが結果ドキュメントの1つのレイヤーにマージされます。 |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | true の場合、重複したアウトラインがマージされます。 |
| [setOptimizeSize](#setOptimizeSize-boolean-) | 最適化フラグを取得または設定します。 |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | ソース入力 PDF ファイルが暗号化されている場合の所有者パスワードを設定します。このプロパティはまだ実装されていません。 |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | true の場合、最初のドキュメントのユーザー権限が連結ドキュメントに適用されます。 |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | true の場合、すべての署名がフィールドから削除されます（フィールドは残ります）。そうでない場合、無効な署名が残る可能性があります。 |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 結果が HttpServletResponse として保存されるときの保存オプションを設定します。デフォルト値: PdfSaveOptions。 |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | PDF には、ページや表セルの背景画像が、同一のタイル背景画像を複数隣り合わせに配置して構成されていることがあります。 |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | <p> フィールド名に付加されて一意にするためのサフィックス形式を設定します。この文字列には %NUM% のサブストリングが含まれている必要があり、数字に置き換えられます。例えば UniqueSuffix = "ABC%NUM%" の場合、フィールド "fieldName" の名前は fieldNameABC1、fieldNameABC2、fieldNameABC3 などになります。 </p> <hr> <pre> PdfFileEditor ed = new PdfFileEditor(); ed.setUniqueSuffix ( "_%NUM%"); </pre> |
| [setUseDiskBuffer](#setUseDiskBuffer-boolean-) | このオプションを使用すると、宛先ドキュメントが定期的にディスクに保存され、以降の連結は増分更新として適用されます。 |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | <p> 開始位置から指定された位置まで分割し、前半部分を出力ストリームに保存します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.splitFromFirst(sourceStream, 5, outStream); </pre> <hr> この操作の後、ストリームは閉じられません。 |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | <p> PDF ファイルを最初のページから指定された位置まで分割し、前半部分を新しいファイルとして保存します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitFromFirst("input.pdf", 5, "out.pdf"); </pre> |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | PDF ファイルを複数のドキュメントに分割します。ドキュメントは単一ページまたは複数ページにできます。 |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | PDF ファイルを複数のドキュメントに分割します。ドキュメントは単一ページまたは複数ページにできます。 |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | <p> 指定された位置から分割し、後半部分を新しいファイルストリームとして保存します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.splitToEnd(sourceStream, 5, outStream); </pre> <hr> CloseConcatedStreams が指定されていない限り、この操作の後ストリームは閉じられません。 |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | <p> 指定された位置から分割し、後半部分を新しいファイルとして保存します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitToEnd("input.pdf", 5, "out.pdf"); </pre> |
| [splitToPages](#splitToPages-java.io.InputStream-) | PDF ファイルを単一ページのドキュメントに分割します。 |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | PDF ファイルを単一ページのドキュメントに分割し、指定されたパスに保存します。 |
| [splitToPages](#splitToPages-java.lang.String-) | PDFファイルを単一ページのドキュメントに分割します。 |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | PDF ファイルを単一ページのドキュメントに分割し、指定されたパスに保存します。 |

### PdfFileEditor {#PdfFileEditor--}
```
public PdfFileEditor()
```

PdfFileEditor のコンストラクタです。

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
<p> ページ内容のサイズを変更し、指定された余白を追加します。余白はデフォルトの空間単位で指定されます。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMargins(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); dest.Close(); </pre>

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
<p> ページ内容のサイズを変更し、指定された余白を追加します。余白はデフォルトの空間単位で指定されます。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMargins(\"input.pdf\", \"output.pdf\", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); </pre>

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
<p> ページ内容のサイズを変更し、指定された余白を追加します。余白はページの初期サイズのパーセントで指定されます。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileInputStream(\"output.pdf\"); fileEditor.addMarginsPct(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); dest.close(); </pre>

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
<p> ページ内容のサイズを変更し、指定された余白を追加します。余白はページの初期サイズのパーセントで指定されます。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMarginsPct(\"input.pdf\", \"output.pdf\", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); </pre>

### addPageBreak {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
ドキュメントのページに改ページを追加します。

### addPageBreak {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
ドキュメントのページに改ページを追加します。

### addPageBreak {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
ドキュメントのページに改ページを追加します。

### addPageBreak {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
ドキュメントのページに改ページを追加します。

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
<p> ポートストリームのドキュメント配列から選択されたページを追加します。結果のドキュメントには firstInputFile と、portStreams のすべてのドキュメントの startPage から endPage の範囲のページが含まれます。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream(\"input.pdf\"); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OtputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream); </pre>

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
<p> portStream から startPage から endPage の範囲で選択されたページを、firstInputStream の末尾に追加します。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream(\"input.pdf\"); InputStream stream1 = new FileInputStream(\"file1.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.append(instream, stream1, 3, 5, outstream); </pre>

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
<p> portFiles のドキュメントから選択されたページを追加します。結果のドキュメントには firstInputFile と、portFiles のすべてのドキュメントの startPage から endPage の範囲のページが含まれます。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append(\"input.pdf\", new string[] { \"file1.pdf\", \"file2.pdf\"}, 3, 5, \"outfile.pdf\"); </pre>

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
<p> portFile から startPage から endPage の範囲で選択されたページを、firstInputFile の末尾に追加します。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append(\"input.pdf\", \"file1.pdf\", 3, 5, \"outfile.pdf\"); </pre>

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
ドキュメントを連結します。

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
<p> ファイルを連結します </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream); </pre>

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> 2つの PDF ドキュメントを交互にページを配置し、空白の場所を空白ページで埋めて新しい PDF ドキュメントに結合します。例: document1 は 5 ページ: p1, p2, p3, p4, p5。document2 は 3 ページ: p1', p2', p3'。2 つの PDF ドキュメントを結合すると、結果のドキュメントはページ:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage の順になります。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); InputStream blank = new FileInputStream(\"blank.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream); </pre>

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> 2つのファイルを連結します。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(stream1, stream2, outstream); </pre>

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
<p> 複数のファイルを1つのファイルに連結します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(new String[] { \"src1.pdf\", \"src2.pdf\" }, \"dest.pdf\"); </pre>

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
<p> 2つのファイルを連結します。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.concatenate(\"file1.pdf\", \"file2.pdf\", \"outfile.pdf\"); </pre>

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
<p> 2つの PDF ドキュメントを交互にページを配置し、空白の場所を空白ページで埋めて新しい PDF ドキュメントに結合します。例: document1 は 5 ページ: p1, p2, p3, p4, p5。document2 は 3 ページ: p1', p2', p3'。2 つの PDF ドキュメントを結合すると、結果のドキュメントはページ:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage の順になります。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(\"src1.pdf\", \"src2.pdf\", \"blank.pdf\", \"dest.pdf\"); </pre>

### createArrayWithExclusion {#createArrayWithExclusion-int-int-}
```
public static Integer [] createArrayWithExclusion(int n, int y)
```



### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
<p> 入力ファイルから番号配列で指定されたページを削除し、新しい Pdf ファイルとして保存します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream intputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileInputStream(\"output.pdf\"); pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream); </pre>

### delete {#delete-java.lang.String-int:A-java.lang.String-}
<p> 入力ファイルから番号配列で指定されたページを削除し、新しい Pdf ファイルとして保存します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.delete(\"input.pdf\", new int[] { 2, 3 }, \"out.pdf\"); </pre>

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
<p> 数値配列で指定されたページを抽出し、新しい Pdf ファイルとして保存します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream); </pre>

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
<p> 入力ファイルからページを抽出し、新しい Pdf ファイルとして保存します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.extract(sourceStream, 1, 3, 6, outStream); </pre>

### extract {#extract-java.lang.String-int:A-java.lang.String-}
<p> 数値配列で指定されたページを抽出し、新しい PDF ファイルとして保存します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf"); </pre>

### extract {#extract-java.lang.String-int-int-java.lang.String-}
<p> 入力ファイルからページを抽出し、新しい Pdf ファイルとして保存します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.Extract("input.pdf", 3, 7, "output.pdf"); </pre>

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
@Deprecated public boolean getAllowConcatenateExceptions()
```

<p> true に設定すると、エラーが発生した場合に例外がスローされます。false に設定すると例外はスローされず、失敗した場合はメソッドが false を返します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre>

**Returns:**
boolean 値 @deprecated このプロパティは非推奨であり、例外をスローするために使用できません。

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

操作の結果が HttpServletResponse オブジェクトに添付ファイルとして格納されるときの添付ファイル名を取得します。

**Returns:**
文字列値

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
public boolean getCloseConcatenatedStreams()
```

true に設定すると、操作後にストリームが閉じられます。

**Returns:**
ブール値

### getConcatenationPacketSize {#getConcatenationPacketSize--}
```
public final int getConcatenationPacketSize()
```

UseDiskBuffer が true に設定されている場合、連結中に新しい増分更新が行われるまでに連結されたドキュメント数を示します。

**Returns:**
int 値です。

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

操作の結果が HttpServletResponse オブジェクトに格納されるときのコンテンツ保存方法を取得します。可能な値: inline / attachment。デフォルト: inline。

**Returns:**
ContentDisposition 要素 @see ContentDisposition

### getConversionLog {#getConversionLog--}
```
public String getConversionLog()
```

変換プロセスのログを取得します。

**Returns:**
string 値

### getCopyLogicalStructure {#getCopyLogicalStructure--}
```
public boolean getCopyLogicalStructure()
```

true の場合、連結が実行されるときにファイルの論理構造がコピーされます。

**Returns:**
ブール値

### getCopyOutlines {#getCopyOutlines--}
```
public boolean getCopyOutlines()
```

true の場合、アウトラインがコピーされます。

**Returns:**
ブール値

### getCorruptedFileAction {#getCorruptedFileAction--}
```
public int getCorruptedFileAction()
```

このプロパティは、連結処理中に破損したファイルに遭遇したときの動作を定義します。可能な値は: StopWithError と ConcatenateIgnoringCorrupted です。

**Returns:**
ConcatenateCorruptedFileAction 要素 @see ConcatenateCorruptedFileAction

### getCorruptedItems {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem [] getCorruptedItems()
```

<p> 連結が実行されたときに発生した問題の配列です。Concatenate() 関数に渡された破損したドキュメントごとに新しい CorruptedItem エントリが作成されます。このプロパティは CorruptedFileAction が ConcatenateIgnoringCorrupted の場合にのみ使用できます。 </p> <hr> <pre> //concatenate documents and show information about corrupted documents PdfFileEditor pfe = new PdfFileEditor(); pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted); {@code if (pfe.getCorruptedItems().length >0)} { for(PdfFileEditor.CorruptedItem item : pfe.getCorruptedItems()) { System.out.println(item.getIndex()+ " reason: " + item.getException()); } } </pre>

**Returns:**
PdfFileEditor.CorruptedItem の配列

### getCustomProgressConcatenationHandler {#getCustomProgressConcatenationHandler--}
```
public PdfFileEditor.ConcatenationProgressHandler getCustomProgressConcatenationHandler()
```

連結中に動作し、内部連結ステージのイベントを外部顧客コードに変換する内部プログレスイベントプロセッサの表現です。

**Returns:**
ConcatenationProgressHandler インスタンス

### getIncrementalUpdates {#getIncrementalUpdates--}
```
public boolean getIncrementalUpdates()
```

true の場合、連結中に増分更新が行われます。

**Returns:**
ブール値

### getKeepActions {#getKeepActions--}
```
public final boolean getKeepActions()
```

true の場合、アクションがソースドキュメントからコピーされます。

**Returns:**
ブール値

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
public boolean getKeepFieldsUnique()
```

true の場合、フォームが連結される際にフィールド名が一意になるようにします。サフィックスがフィールド名に付加され、サフィックステンプレートは UniqueSuffix プロパティで指定できます。

**Returns:**
ブール値

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

最後に発生した例外を取得します。

**Returns:**
java.lang.Exception オブジェクト

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
public boolean getMergeDuplicateLayers()
```

このプロパティが true の場合、同名の連結ドキュメントのオプションコンテンツが結果ドキュメントの1つのレイヤーにマージされます。

**Returns:**
ブール値

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
public boolean getMergeDuplicateOutlines()
```

true の場合、重複したアウトラインがマージされます。

**Returns:**
ブール値

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

最適化フラグを取得または設定します。

**Returns:**
ブール値

### getOwnerPassword {#getOwnerPassword--}
```
public String getOwnerPassword()
```

ソース入力 Pdf ファイルが暗号化されている場合の所有者パスワードを取得します。このプロパティはまだ実装されていません。

**Returns:**
文字列値

### getPreserveUserRights {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```

true の場合、最初のドキュメントのユーザー権限が連結ドキュメントに適用されます。

**Returns:**
ブール値

### getRemoveSignatures {#getRemoveSignatures--}
```
public final boolean getRemoveSignatures()
```

true の場合、すべての署名がフィールドから削除されます（フィールドは残ります）。そうでない場合、無効な署名が残る可能性があります。

**Returns:**
ブール値

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

結果が HttpServletResponse として保存されるときの保存オプションを取得または設定します。デフォルト値: PdfSaveOptions。

**Returns:**
SaveOptions オブジェクト

### getUniqueSuffix {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```

フィールド名が一意になるように連結されたフォームでフィールド名に付加されるサフィックスの形式を取得します。この文字列は %NUM% の部分文字列を含んでおり、数字に置き換えられます。例えば UniqueSuffix = "ABC%NUM%" の場合、フィールド "fieldName" の名前は: fieldNameABC1, fieldNameABC2, fieldNameABC3 などになります。

**Returns:**
文字列値

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
<p> 他のファイルからページを挿入して、入力 PDF ファイルに追加します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileoutputStream("out.pdf"); pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream); </pre>

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
<p> 他のファイルからページを挿入して、入力 PDF ファイルに追加します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre>

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
<p> 他のファイルからページを挿入して、入力 PDF ファイルに追加します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre>

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
<p> 別のファイルからページを挿入して、PDF ファイルの指定位置に追加します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf"); </pre>

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

PDF には、ページや表セルの背景画像が、同一のタイル背景画像を複数隣り合わせに配置して構成されていることがあります。

**Returns:**
ブール値

### isUseDiskBuffer {#isUseDiskBuffer--}
```
public final boolean isUseDiskBuffer()
```

このオプションを使用すると、宛先ドキュメントが定期的にディスクに保存され、以降の連結は増分更新として適用されます。

**Returns:**
ブール値

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
<p> InputStream から outputStream へブックレットを作成します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
<p> firstInputStream から outputStream へカスタマイズされたブックレットを作成します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
<p> 入力ストリームからブックレットを作成し、結果を出力ストリームに保存します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
<p> firstInputStream から outputStream へブックレットを作成します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
<p> 入力ファイルから出力ファイルへブックレットを作成します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf"); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
<p> firstInputFile から outputFile へカスタマイズされたブックレットを作成します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
<p> inputFile から outputFile へブックレットを作成します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
<p> firstInputFile から outputFile へカスタマイズされたブックレットを作成します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
<p> 複数の入力 PDF ストリームから outputStream へ N-Up ドキュメントを作成します。outputStream の各ページには、同じページ番号の入力ストリームのページと組み合わせた複数ページが含まれます。isSidewise が true の場合はページが横方向に積み重ねられ、false の場合は縦方向に積み重ねられます。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream stream1 = new FileInputStream("input1.pdf"); InputStream stream2 = new FileInputStream("input2.pdf"); InputStream stream3 = new FileInputStream("input3.pdf"); OutputStream output = new FileOutputStream("output.pdf"); pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> 2 つの入力 PDF ストリームから outputStream へ N-Up ドキュメントを作成します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream input1 = new FileInputStream("input1.pdf"); InputStream input2 = new FileInputStream("input2.pdf"); OutputStream output = new FileOutputStream("output.pdf"); pfe.makeNUp(input1, input2, output); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
<p> 入力ストリームから N-Up ドキュメントを作成し、結果を出力ストリームに保存します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeNUp(inputStream, outputStream, 3, 3); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
<p> 最初の入力ストリームから出力ストリームへ N-Up ドキュメントを作成します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4); </pre>

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
<p> 複数の入力 PDF ファイルから N-Up 文書を作成し、outputFile に出力します。outputFile の各ページは、同じページ番号の入力ファイルのページを組み合わせた複数ページを含みます。isSidewise が true の場合は横方向に、false の場合は縦方向にページが並べられます。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(new String[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
<p> 最初の入力ファイルから N-Up 文書を作成し、outputFile に出力します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input.pdf", "output.pdf", 3, 3); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
<p> 入力ファイルから N-Up 文書を作成し、outputFile に出力します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
<p> 2 つの入力 PDF ファイルから N-Up 文書を作成し、outputFile に出力します。outputFile の各ページは 2 ページを含み、1 ページは最初の入力ファイルから、もう 1 ページは 2 番目の入力ファイルから取得されます。これら 2 ページは横方向に並べられます。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input1.pdf", "input2.pdf", "output.pdf"); </pre>

### resizeContents {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
ドキュメントのページサイズを変更します。

### resizeContents {#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
ドキュメントのページサイズを変更します。

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
<p> ドキュメントページの内容をリサイズします。ページの内容を縮小し、余白を追加します。内容の新しいサイズはデフォルトの空間単位で指定されます。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileOutputStream("output.pdf"); fileEditor.resizeContents(src, dest, //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre>

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
ドキュメントのページの内容をリサイズします。

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
<p> ドキュメントページの内容をリサイズします。ページの内容を縮小し、余白を追加します。内容の新しいサイズはデフォルトの空間単位で指定されます。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizeContents("input.pdf", "output.pdf", //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre>

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
ドキュメント内のページの内容をリサイズします。

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
<p> ドキュメントページの内容をリサイズします。ページの内容を縮小し、余白を追加します。新しい内容サイズはパーセンテージで指定されます。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileOutputStream("output.pdf"); fileEditor.resizePct(src, dest, //resize all pages of document null, //new contents width = 60% of initial size 60, //new contents height = 60% of initial size 60); // Rest area of page will be empty (page margins). Size of left and right margins is (100% - 60%) / 2 = 20% // The same for top and bottom margins. </pre>

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
<p> ドキュメントページの内容をリサイズします。ページの内容を縮小し、余白を追加します。新しい内容サイズはパーセンテージで指定されます。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizePct("input.pdf", "output.pdf", //resize all pages of document null, //new contents width = 60% of initial size 60, //new contents height = 60% of initial size 60); // Rest area of page will be empty (page margins). Size of left and right margins is (100% - 60%) / 2 = 20% // The same for top and bottom margins. </pre>

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
ドキュメントのページサイズを変更します。

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
ドキュメントのページサイズを変更します。

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
@Deprecated public void setAllowConcatenateExceptions(boolean value)
```

<p> true に設定すると、エラーが発生した場合に例外がスローされます。false に設定すると、例外はスローされず、失敗した場合はメソッドが false を返します。 </p>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre> @deprecated このプロパティは非推奨であり、例外をスローできるようにするために使用できません。 |

### setAttachmentName {#setAttachmentName-java.lang.String-}
操作の結果が HttpServletResponse オブジェクトに添付ファイルとして保存されるときの添付ファイル名を設定します。

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```

<p> true に設定すると、操作後にストリームが閉じられます。 </p>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setCloseConcatenatedStreams (true); </pre> |

### setConcatenationPacketSize {#setConcatenationPacketSize-int-}
```
public final void setConcatenationPacketSize(int value)
```

UseDiskBuffer が true に設定されている場合、連結中に新しい増分更新が行われるまでに連結されたドキュメント数を示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
操作の結果が HttpServletResponse オブジェクトに保存されるときのコンテンツ保存方法を設定します。可能な値: inline / attachment。デフォルト: inline。

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
PDF ファイル形式を設定します。結果ファイルは指定された形式で保存されます。このプロパティが指定されていない場合、ファイルは変換せずにデフォルトの PDF 形式で保存されます。

### setCopyLogicalStructure {#setCopyLogicalStructure-boolean-}
```
public void setCopyLogicalStructure(boolean value)
```

true の場合、連結が実行されるときにファイルの論理構造がコピーされます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setCopyOutlines {#setCopyOutlines-boolean-}
```
public void setCopyOutlines(boolean value)
```

true の場合、アウトラインがコピーされます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
public void setCorruptedFileAction(int value)
```

このプロパティは、連結処理中に破損したファイルに遭遇したときの動作を定義します。可能な値は: StopWithError と ConcatenateIgnoringCorrupted です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値 @see ConcatenateCorruptedFileAction |

### setCustomProgressConcatenationHandler {#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-}
連結中に動作し、内部連結ステージのイベントを外部顧客コードに変換する内部プログレスイベントプロセッサの表現です。

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
public void setIncrementalUpdates(boolean value)
```

true の場合、連結中に増分更新が行われます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setKeepActions {#setKeepActions-boolean-}
```
public final void setKeepActions(boolean value)
```

true の場合、アクションがソースドキュメントからコピーされます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
public void setKeepFieldsUnique(boolean value)
```

true の場合、フォームが連結される際にフィールド名が一意になるようにします。サフィックスがフィールド名に付加され、サフィックステンプレートは UniqueSuffix プロパティで指定できます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
public void setMergeDuplicateLayers(boolean value)
```

このプロパティが true の場合、同名の連結ドキュメントのオプションコンテンツが結果ドキュメントの1つのレイヤーにマージされます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
public void setMergeDuplicateOutlines(boolean value)
```

true の場合、重複したアウトラインがマージされます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

最適化フラグを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
ソース入力 PDF ファイルが暗号化されている場合の所有者パスワードを設定します。このプロパティはまだ実装されていません。

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
public void setPreserveUserRights(boolean value)
```

true の場合、最初のドキュメントのユーザー権限が連結ドキュメントに適用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
public final void setRemoveSignatures(boolean value)
```

true の場合、すべての署名がフィールドから削除されます（フィールドは残ります）。そうでない場合、無効な署名が残る可能性があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
結果が HttpServletResponse として保存されるときの保存オプションを設定します。デフォルト値: PdfSaveOptions。

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

PDF には、ページや表セルの背景画像が、同一のタイル背景画像を複数隣り合わせに配置して構成されていることがあります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | ブール値 |

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
<p> フィールド名に付加されて一意にするためのサフィックス形式を設定します。この文字列には %NUM% のサブストリングが含まれている必要があり、数字に置き換えられます。例えば UniqueSuffix = "ABC%NUM%" の場合、フィールド "fieldName" の名前は fieldNameABC1、fieldNameABC2、fieldNameABC3 などになります。 </p> <hr> <pre> PdfFileEditor ed = new PdfFileEditor(); ed.setUniqueSuffix ( "_%NUM%"); </pre>

### setUseDiskBuffer {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```

このオプションを使用すると、宛先ドキュメントが定期的にディスクに保存され、以降の連結は増分更新として適用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
<p> 開始位置から指定された位置まで分割し、前半部分を出力ストリームに保存します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.splitFromFirst(sourceStream, 5, outStream); </pre> <hr> この操作の後、ストリームは閉じられません。

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
<p> PDF ファイルを最初のページから指定された位置まで分割し、前半部分を新しいファイルとして保存します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitFromFirst("input.pdf", 5, "out.pdf"); </pre>

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
PDF ファイルを複数のドキュメントに分割します。ドキュメントは単一ページまたは複数ページにできます。

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
PDF ファイルを複数のドキュメントに分割します。ドキュメントは単一ページまたは複数ページにできます。

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
<p> 指定された位置から分割し、後半部分を新しいファイルストリームとして保存します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.splitToEnd(sourceStream, 5, outStream); </pre> <hr> CloseConcatedStreams が指定されていない限り、この操作の後ストリームは閉じられません。

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
<p> 指定された位置から分割し、後半部分を新しいファイルとして保存します。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitToEnd("input.pdf", 5, "out.pdf"); </pre>

### splitToPages {#splitToPages-java.io.InputStream-}
PDF ファイルを単一ページのドキュメントに分割します。

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
PDF ファイルを単一ページのドキュメントに分割し、指定されたパスに保存します。

### splitToPages {#splitToPages-java.lang.String-}
PDFファイルを単一ページのドキュメントに分割します。

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
PDF ファイルを単一ページのドキュメントに分割し、指定されたパスに保存します。
