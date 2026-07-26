---
title: "PdfASymbolicFontEncodingStrategy"
linktitle: "PdfASymbolicFontEncodingStrategy"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "このクラスは、TrueType シンボリックフォントが複数のエンコーディングを持つ場合のエンコーディングデータのコピー処理を調整するために使用できる規則を記述します。いくつかの PDF ドキュメントはその後。"
type: docs
weight: 3690
url: /ja/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfASymbolicFontEncodingStrategy

```
public class PdfASymbolicFontEncodingStrategy extends Object
```

このクラスは、TrueType シンボリックフォントに複数のエンコーディングがある場合のエンコーディングデータコピー処理を調整するために使用できるルールを記述します。PDF/A 形式に変換した後、一部の PDF ドキュメントで「シンボリック TrueType フォントの cmap に複数のエンコーディングが存在します」というエラーが発生することがあります。このエラーの原因は何でしょうか？すべての TrueType シンボリックフォントは、内部データに特別なテーブル「cmap」を持っています。このテーブルは文字コードをグリフインデックスにマッピングします。このテーブルには、使用されるエンコーディングを記述した異なるエンコーディングサブテーブルが含まれることがあります。cmap テーブルに関する詳細情報は https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html を参照してください。通常、cmap テーブルには複数のエンコーディングサブテーブルが含まれますが、PDF/A 標準では、このフォントに対して PDF/A ドキュメント内で残すエンコーディングサブテーブルは 1 つだけであるか、フォントのサブテーブルの中に (3,0) エンコーディングサブテーブルが存在することが要求されます。ここでの重要な質問は、別のサブテーブルからどのデータを取得して宛先エンコーディングテーブル (3,0) にコピーすべきか、ということです。大多数のフォントは「整形式」の cmap テーブルを持ち、すべてのエンコーディングサブテーブルが他のサブテーブルと完全に一致しています。しかし、一部のフォントでは衝突が発生する cmap テーブルがあり、例えばあるサブテーブルが Unicode 100 に対してグリフインデックス 100 を持ち、別のサブテーブルが同じ Unicode 100 に対してグリフインデックス 200 を持つ場合があります。この問題を解決するには特別な戦略が必要です。デフォルトでは以下の戦略が使用されます：mac サブテーブル (1,0) が検索されます。このテーブルが見つかった場合、宛先テーブル (3,0) を埋めるためにこのデータのみが使用されます。mac サブテーブルが見つからない場合、(3,0) を除くすべてのサブテーブルが順に走査され、宛先 (3,0) サブテーブルにデータをコピーするために使用されます。また、各 Unicode（Unicode, グリフインデックス）のマッピングは、宛先テーブルに現在その Unicode が存在しない場合にのみコピーされます。したがって、例えば最初のサブテーブルが Unicode 100 に対してグリフインデックス 100 を持ち、次のサブテーブルが同じ Unicode 100 に対してグリフインデックス 200 を持つ場合、最初のサブテーブル（unicode=100、glyph index=100）のデータのみがコピーされます。このように、前のサブテーブルが次のサブテーブルよりも優先されます。このクラス { PdfASymbolicFontEncodingStrategy } のプロパティは、デフォルトの動作を調整するのに役立ちます。型が { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType } のプロパティ {PreferredCmapEncodingTable}（{ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable } / { PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable }）が設定されている場合、mac サブテーブル (1,0) よりも優先して該当サブテーブルが使用されます。列挙型 {PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} の値 'MacTable' は、この場合意味がなく、デフォルトで使用される mac サブテーブル (1,0) と同じものを指しています。プロパティ {CmapEncodingTablesPriorityQueue}（{ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue } / { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue }）は、すべてのサブテーブルに対する優先順位を破棄します。このプロパティが設定されている場合、宣言されたキューに含まれるサブテーブルのみが指定された順序で使用されます。指定されたサブテーブルが見つからない場合、上記で説明したデフォルトのすべてのサブテーブルの走査とコピー戦略が使用されます。オブジェクト { PdfASymbolicFontEncodingStrategy.QueueItem } は使用されるエンコーディングサブテーブルを指定します。このサブテーブルは、メンバー (PlatformID, PlatformSpecificId) の組み合わせまたは { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType } 列挙型を使用して設定できます。フォントに (3,0) サブテーブルがない場合、PDF/A 互換性を保つために別のサブテーブルが使用されます。使用するサブテーブルの選択は前述のルールに従って行われ、{@code PreferredCmapEncodingTable}（{ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable } / {PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}）および {@code CmapEncodingTablesPriorityQueue}（{ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue } / { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}）プロパティが結果のサブテーブルを決定するために使用されます。フォントが要求されたサブテーブルを持たない場合は、存在する任意のサブテーブルが使用されます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy--) | コンストラクタ。デフォルトのサブテーブル (mac 1,0) を設定します。 |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-) | コンストラクタ。デフォルトのサブテーブル (mac 1,0) を設定します。 |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy-short-) | コンストラクタ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCmapEncodingTablesPriorityQueue](#getCmapEncodingTablesPriorityQueue--) | 処理するエンコーディングサブテーブルのキューを指定します。 |
| [getPreferredCmapEncodingTable](#getPreferredCmapEncodingTable--) | mac サブテーブル (1,0) に優先して使用されるサブテーブルを指定します。このケースでは、列挙 {@code QueueItem.CMapEncodingTableType} の値 'MacTable' は意味がありません。 |
| [setCmapEncodingTablesPriorityQueue](#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-) | 処理するエンコーディングサブテーブルのキューを指定します。 |
| [setPreferredCmapEncodingTable](#setPreferredCmapEncodingTable-short-) | mac サブテーブル (1,0) に優先して使用されるサブテーブルを指定します。このケースでは、列挙 {@code QueueItem.CMapEncodingTableType} の値 'MacTable' は意味がありません。 |

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy()
```

コンストラクタ。デフォルトのサブテーブル (mac 1,0) を設定します。

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-}
コンストラクタ。デフォルトのサブテーブル (mac 1,0) を設定します。

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy-short-}
```
public PdfASymbolicFontEncodingStrategy(short preferredEncodingTable)
```

コンストラクタ

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| preferredEncodingTable |  | mac サブテーブル (1,0) に優先して使用されるエンコーディングサブテーブル @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType |

### getCmapEncodingTablesPriorityQueue {#getCmapEncodingTablesPriorityQueue--}
```
public com.aspose.ms.System.Collections.Generic.Queue< PdfASymbolicFontEncodingStrategy.QueueItem > getCmapEncodingTablesPriorityQueue()
```

処理するエンコーディングサブテーブルのキューを指定します。

**Returns:**
QueueItem のキュー

### getPreferredCmapEncodingTable {#getPreferredCmapEncodingTable--}
```
public short getPreferredCmapEncodingTable()
```

mac サブテーブル (1,0) に優先して使用されるサブテーブルを指定します。このケースでは、列挙 {@code QueueItem.CMapEncodingTableType} の値 'MacTable' は意味がありません。

**Returns:**
CMapEncodingTableType 要素 @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType

### setCmapEncodingTablesPriorityQueue {#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-}
処理するエンコーディングサブテーブルのキューを指定します。

### setPreferredCmapEncodingTable {#setPreferredCmapEncodingTable-short-}
```
public void setPreferredCmapEncodingTable(short value)
```

mac サブテーブル (1,0) に優先して使用されるサブテーブルを指定します。このケースでは、列挙 {@code QueueItem.CMapEncodingTableType} の値 'MacTable' は意味がありません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | preferredEncodingTable は、mac サブテーブル (1,0) に優先して使用されるエンコーディングサブテーブルです @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType |
