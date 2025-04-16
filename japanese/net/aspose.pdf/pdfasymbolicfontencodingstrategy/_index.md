---
title: Class PdfASymbolicFontEncodingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfASymbolicFontEncodingStrategy クラス。TrueType シンボリックフォントが複数のエンコーディングを持つ場合のエンコーディングデータのコピー処理を調整するために使用できるルールを記述します。一部の PDF ドキュメントは PDF/A 形式に変換後、「More than one encoding in symbolic TrueType font's cmap」というエラーを出す場合があります。このエラーの原因は何でしょうか？すべての TrueType シンボリックフォントは内部データに特別なテーブル "cmap" を持っており、このテーブルは文字コードをグリフインデックスにマッピングします。そして、このテーブルには使用されるエンコーディングを記述する複数のエンコーディングサブテーブルが含まれる場合があります。cmap テーブルに関する詳細情報は https://developer.apple.com/fonts/TrueTypeReferenceManual/RM06/Chap6cmap.html を参照してください。通常、cmap テーブルにはいくつかのエンコーディングサブテーブルが含まれますが、PDF/A 規格では PDF/A ドキュメント内のこのフォントに対して、エンコーディングサブテーブルが 1 つのみ残されるか、またはこのフォントのサブテーブルの中に （3,0） エンコーディングサブテーブルが存在しなければなりません。そして、ここでの重要な疑問は、別のサブテーブルからどのデータを取り出して宛先エンコーディングテーブル （3,0） にコピーするべきか、ということです。ほとんどのフォントは、すべてのエンコーディングサブテーブルが互いに完全に一貫している「整形式」の cmap テーブルを持っています。しかし、一部のフォントでは、たとえばあるサブテーブルでユニコード 100 に対してグリフインデックス 100 を持ち、別のサブテーブルで同じユニコード 100 に対してグリフインデックス 200 を持つ、といった衝突が発生する場合があります。この問題を解決するためには特別な戦略が必要です。デフォルトでは、次の戦略が使用されます。まず、mac サブテーブル （1,0） が探され、もしこのテーブルが見つかった場合、そのデータのみが宛先テーブル （3,0） の埋め込みに使用されます。mac サブテーブルが見つからない場合は、（3,0） 以外のすべてのサブテーブルが列挙され、データが宛先 （3,0） サブテーブルにコピーされます。また、各ユニコード（ユニコード、グリフインデックス）のマッピングは、宛先テーブルにそのユニコードが存在しない場合にのみコピーされます。たとえば、最初のサブテーブルでユニコード 100 に対してグリフインデックス 100 があり、次のサブテーブルで同じユニコード 100 に対してグリフインデックス 200 があった場合、最初のサブテーブルのデータ（ユニコード 100、グリフインデックス 100）のみがコピーされます。つまり、前のサブテーブルが後のサブテーブルよりも優先されます。`PdfASymbolicFontEncodingStrategy` クラスのプロパティは、デフォルトの動作を調整するのに役立ちます。もしプロパティ [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/)（型 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/)）が設定されていれば、mac サブテーブル （1,0） よりも優先して関連するサブテーブルが使用されます。列挙 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) の 'MacTable' の値は、デフォルトで使用される同じ mac サブテーブル （1,0） を指すため、この場合は意味を持ちません。プロパティ [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) は、任意のサブテーブルに対するすべての優先順位を無効にします。このプロパティが設定されると、宣言されたキュー内のサブテーブルのみが指定された順序で使用されます。指定されたサブテーブルが見つからない場合は、上述の全サブテーブルのデフォルトの列挙とコピー戦略が使用されます。[`QueueItem`](../pdfasymbolicfontencodingstrategy.queueitem/) オブジェクトは使用されるエンコーディングサブテーブルを指定します。このサブテーブルは、メンバー (PlatformID, PlatformSpecificId) の組み合わせ、または [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) 列挙を介して設定できます。フォントに （3,0） サブテーブルが存在しない場合は、PDF/A 互換性を維持するために他のサブテーブルが使用されます。使用するサブテーブルの選択は、前述のルールに従って行われ、[`PreferredCmapEncodingTable`](./preferredcmapencodingtable/) および [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) プロパティによって結果のサブテーブルが決定され、フォントに要求されたサブテーブルが存在しない場合は、存在する任意のサブテーブルが使用されます。
type: docs
weight: 8330
url: /ja/net/aspose.pdf/pdfasymbolicfontencodingstrategy/
---
## PdfASymbolicFontEncodingStrategy クラス

このクラスは、TrueType シンボリックフォントが複数のエンコーディングを持つ場合のエンコーディングデータのコピー処理を調整するために使用できるルールを記述します。一部の PDF ドキュメントは PDF/A 形式に変換後、「More than one encoding in symbolic TrueType font's cmap」というエラーを出す場合があります。このエラーの原因は何でしょうか？すべての TrueType シンボリックフォントは内部データに特別なテーブル "cmap" を持っており、このテーブルは文字コードをグリフインデックスにマッピングします。そして、このテーブルには使用されるエンコーディングを記述する複数のエンコーディングサブテーブルが含まれる場合があります。cmap テーブルに関する詳細情報は https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html を参照してください。通常、cmap テーブルにはいくつかのエンコーディングサブテーブルが含まれますが、PDF/A 規格では、このフォントについて PDF/A ドキュメント内にエンコーディングサブテーブルが 1 つのみ残されるか、もしくはフォントのサブテーブルの中に (3,0) エンコーディングサブテーブルが存在しなければなりません。ここでの重要な疑問は、別のサブテーブルからどのデータを取り出して宛先エンコーディングテーブル (3,0) にコピーするべきか、ということです。ほとんどのフォントは、すべてのエンコーディングサブテーブルが互いに完全に一貫している「整形式」の cmap テーブルを持っています。しかし、一部のフォントでは、たとえばあるサブテーブルでユニコード 100 に対してグリフインデックス 100 を持ち、別のサブテーブルで同じユニコード 100 に対してグリフインデックス 200 を持つ、といった衝突が発生する場合があります。この問題を解決するためには特別な戦略が必要です。デフォルトでは、次の戦略が使用されます。まず、mac サブテーブル (1,0) が探され、もしこのテーブルが見つかった場合、そのデータのみが宛先テーブル (3,0) に使用されます。mac サブテーブルが見つからない場合は、(3,0) 以外のすべてのサブテーブルが列挙され、データが宛先 (3,0) サブテーブルにコピーされます。また、各ユニコード（ユニコード、グリフインデックス）のマッピングは、宛先テーブルにそのユニコードが存在しない場合にのみコピーされます。たとえば、最初のサブテーブルでユニコード 100 に対してグリフインデックス 100 があり、次のサブテーブルで同じユニコード 100 に対してグリフインデックス 200 があった場合、最初のサブテーブルのデータ（ユニコード=100、グリフインデックス=100）のみがコピーされます。つまり、前のサブテーブルが後のサブテーブルよりも優先されます。`PdfASymbolicFontEncodingStrategy` クラスのプロパティは、デフォルトの動作を調整するのに役立ちます。もしプロパティ [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/)（型 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/)）が設定されていれば、mac サブテーブル (1,0) よりも優先して関連するサブテーブルが使用されます。列挙 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) の 'MacTable' の値は、デフォルトで使用される同じ mac サブテーブル (1,0) を指すため、この場合は意味を持ちません。プロパティ [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) は、任意のサブテーブルに対するすべての優先順位を無効にします。このプロパティが設定されると、宣言されたキュー内のサブテーブルのみが指定された順序で使用されます。指定されたサブテーブルが見つからない場合は、上述の全サブテーブルのデフォルトの列挙とコピー戦略が使用されます。[`QueueItem`](../pdfasymbolicfontencodingstrategy.queueitem/) オブジェクトは使用されるエンコーディングサブテーブルを指定します。このサブテーブルは、メンバー (PlatformID, PlatformSpecificId) の組み合わせ、または [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) 列挙を介して設定できます。フォントに (3,0) サブテーブルが存在しない場合は、PDF/A 互換性を維持するために他のサブテーブルが使用されます。使用するサブテーブルの選択は、前述のルールに従って行われ、[`PreferredCmapEncodingTable`](./preferredcmapencodingtable/) および [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) プロパティによって結果のサブテーブルが決定され、フォントに要求されたサブテーブルが存在しない場合は、存在する任意のサブテーブルが使用されます。

```csharp
public class PdfASymbolicFontEncodingStrategy
```

## コンストラクター

| Name | Description |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor)() | コンストラクター。デフォルトのサブテーブル (mac 1,0) を設定します |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_1)(CMapEncodingTableType) | コンストラクター |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_2)(Queue&lt;QueueItem&gt;) | コンストラクター |

## プロパティ

| Name | Description |
| --- | --- |
| [CmapEncodingTablesPriorityQueue](../../aspose.pdf/pdfasymbolicfontencodingstrategy/cmapencodingtablespriorityqueue/) { get; set; } | 処理するエンコーディングサブテーブルのキューを指定します。 |
| [PreferredCmapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy/preferredcmapencodingtable/) { get; set; } | mac サブテーブル (1,0) に優先して使用されるサブテーブルを指定します。列挙 [CMapEncodingTableType](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) の 'MacTable' の値は、この場合意味を持ちません。 |

### 参照先

* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)