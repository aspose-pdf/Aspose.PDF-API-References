---
title: "クラス PdfASymbolicFontEncodingStrategy"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.PdfASymbolicFontEncodingStrategy クラスです。このクラスは、TrueType シンボリックフォントに複数のエンコーディングがある場合のエンコーディングデータのコピー処理を調整できるルールを記述します。PDF を PDF/A 形式に変換した後、一部の PDF ドキュメントで「シンボリック TrueType フォントの cmap に複数のエンコーディングが存在する」というエラーが発生することがあります。このエラーの原因は、すべての TrueType シンボリックフォントが内部データに特別な cmap テーブルを持っていることです。このテーブルは文字コードをグリフインデックスにマッピングします。また、このテーブルは使用されるエンコーディングを記述した複数のエンコーディングサブテーブルを含むことがあります。cmap テーブルに関する詳細情報は https//developer.apple.com/fonts/TrueTypeReferenceManual/RM06/Chap6cmap.html を参照してください。通常、cmap テーブルは複数のエンコーディングサブテーブルを含みますが、PDF/A 標準では、このフォントに対して PDF/A ドキュメント内に残すエンコーディングサブテーブルは 1 つだけであるか、フォントのサブテーブルの中に 30 エンコーディングサブテーブルが存在しなければなりません。ここでの重要な質問は、どのデータを他のサブテーブルから取得して宛先エンコーディングテーブル 30 にコピーすべきか、ということです。ほとんどのフォントは、すべてのエンコーディングサブテーブルが他のサブテーブルと完全に一致している整合性の取れた cmap テーブルを持っています。しかし、一部のフォントでは衝突が発生し、例えばあるサブテーブルが Unicode 100 に対してグリフインデックス 100 を持ち、別のサブテーブルが同じ Unicode 100 に対してグリフインデックス 200 を持つことがあります。この問題を解決するには特別な戦略が必要です。デフォルトでは、mac サブテーブル10 が検索されます。このテーブルが見つかった場合、そのデータだけが宛先テーブル 30 を埋めるために使用されます。mac サブテーブルが見つからない場合、30 以外のすべてのサブテーブルが順に走査され、宛先 30 サブテーブルにデータがコピーされます。また、各 Unicode のグリフインデックスのマッピングは、宛先テーブルにその Unicode が現在存在しない場合にのみコピーされます。したがって、例えば最初のサブテーブルが Unicode 100 に対してグリフインデックス 100 を持ち、次のサブテーブルが同じ Unicode 100 に対してグリフインデックス 200 を持つ場合、最初のサブテーブルのデータ（Unicode100 のグリフインデックス 100）のみがコピーされます。各前のサブテーブルが次のサブテーブルよりも優先されます。クラス PdfASymbolicFontEncodingStrategy のプロパティは、デフォルト動作を調整するのに役立ちます。プロパティ PreferredCmapEncodingTable（型は CMapEncodingTableType）を設定すると、mac サブテーブル10 に対する優先順位で該当サブテーブルが使用されます。列挙体 CMapEncodingTableType の値 MacTable は、この場合意味がなく、デフォルトで使用される mac サブテーブル10 と同じものを指します。プロパティ CmapEncodingTablesPriorityQueue は、任意のサブテーブルに対するすべての優先順位を破棄します。このプロパティが設定されている場合、宣言されたキューに含まれるサブテーブルのみが指定された順序で使用されます。指定されたサブテーブルが見つからない場合、上記のデフォルトのすべてのサブテーブルの走査とコピー戦略が使用されます。オブジェクト QueueItem は使用されるエンコーディングサブテーブルを指定します。このサブテーブルは membersPlatformID、PlatformSpecificId の組み合わせ、または CMapEncodingTableType 列挙体によって設定できます。フォントに 30 サブテーブルがない場合、PDF/A 互換性を維持するために別のサブテーブルが使用されます。使用するサブテーブルの選択は、前述のルールに従って行われ、PreferredCmapEncodingTable と CmapEncodingTablesPriorityQueue のプロパティが結果のサブテーブルを決定するために使用され、要求されたサブテーブルがフォントに存在しない場合は、存在する任意のサブテーブルが使用されます。"
type: docs
weight: 8470
url: /ja/net/aspose.pdf/pdfasymbolicfontencodingstrategy/
---
## PdfASymbolicFontEncodingStrategy class

This class describes rules which can be used to tune process of copying encoding data for cases when TrueType symbolic font has more than one encoding. Some PDF documents after conversion into PDF/A format could give an error "More than one encoding in symbolic TrueType font's cmap". What is a reason of this error? All TrueType symbolic fonts have special table "cmap" in it's internal data. This table maps character codes to glyph indices. And this table could contain different encoding subtables which describe encodings used. See advanced info about cmap tables at https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Usually cmap table contains several encoding subtables, but PDF/A standard requires that either only one encoding subtable must be left for this font in PDF/A document or there must be a (3,0) encoding subtable among this font subtables. And key question here - what data must be taken from another subtables to copy into destination encoding table (3,0)? Majority of fonts have 'well-formed' cmap tables where every encoding subtable is fully consistent with another subtable. But some fonts have cmap tables with collisions - where for example one subtable has glyph index 100 for unicode 100, but another subtable has glyph index 200 for the same unicode 100. To solve this problems special strategy needed. By default following strategy used: mac subtable(1,0) is looked for. If this table is found, only this data used to fill destination table (3,0). If mac subtable is not found then all subtables except (3,0) are iterated and used to copy data into destination (3,0) subtable. Also mapping for every unicode(unicode, glyph index) is copied into destination table only if destination table does not have this unicode at current moment. So, for example if first subtabe has glyph index 100 for unicode 100, and next subtable has glyph index 200 for the same unicode 100, only data from first subtable (unicode=100, glyph index = 100) will be copied. So each previous subtable takes precedence over the next. Properties of this class `PdfASymbolicFontEncodingStrategy` help tune default behaviour. If property [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/) of type [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) is set, then relevant subtable will be used in precedence to mac subtable(1,0). Value 'MacTable' from enumeration [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) has no sense in this case, cause it points on the same mac subtable (1,0) which will be used by default. Property [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) discards all priorities for any subtable. If this property is set, then only subtables from declared queue will be used in specified order. If subtables specified are not found then default iteration of all subtables and copy strategy described above will be used. Object [`QueueItem`](../pdfasymbolicfontencodingstrategy.queueitem/) specifies encoding subtable used. This subtable can be set via combination of members(PlatformID, PlatformSpecificId) or via [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) enumeration. In case when the font has no (3,0) subtable some other subtable will be used to maintain the PDF/A compatibility. The choice of the subtable to use is made under the same rules as described earlier, so that [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/) and [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) properties are used to determine the resultant subtable, and if the font doesn't have the requested subtable(s) either then any existant subtable will be used.

```csharp
public class PdfASymbolicFontEncodingStrategy
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor)() | コンストラクタ。デフォルトのサブテーブル (mac 1,0) を設定します。 |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_1)(CMapEncodingTableType) | コンストラクタ |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_2)(Queue&lt;QueueItem&gt;) | コンストラクタ |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CmapEncodingTablesPriorityQueue](../../aspose.pdf/pdfasymbolicfontencodingstrategy/cmapencodingtablespriorityqueue/) { get; set; } | 処理対象となるエンコーディングサブテーブルのキューを指定します。 |
| [PreferredCmapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy/preferredcmapencodingtable/) { get; set; } | mac サブテーブル (1,0) に優先して使用されるサブテーブルを指定します。このケースでは、列挙体 [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) の値 'MacTable' は意味がありません。 |

### 関連項目

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


