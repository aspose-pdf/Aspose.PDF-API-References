---
title: "クラス StructureTypeStandard"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.LogicalStructure.StructureTypeStandard クラス。標準構造タイプを表します"
type: docs
weight: 6870
url: /ja/net/aspose.pdf.logicalstructure/structuretypestandard/
---
## StructureTypeStandard class

標準構造タイプを表します。

```csharp
public sealed class StructureTypeStandard
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Category](../../aspose.pdf.logicalstructure/structuretypestandard/category/) { get; } | 標準構造タイプのカテゴリを取得します。 |
| [Tag](../../aspose.pdf.logicalstructure/structuretypestandard/tag/) { get; } | [`StructureElement`](../structureelement/) のタグ名を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [ToString](../../aspose.pdf.logicalstructure/structuretypestandard/tostring/)() | 現在のオブジェクトを表す文字列を返します。 |
| [explicit operator](../../aspose.pdf.logicalstructure/structuretypestandard/op_explicit/) | String から `StructureTypeStandard` への明示的な変換を実行します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| static readonly [Annot](../../aspose.pdf.logicalstructure/structuretypestandard/annot/) | (Annotation; PDF 1.5) ILSE のコンテンツの一部と対応する PDF アノテーションとの関連付けです。Annot はリンクアノテーションとウィジェットアノテーションを除くすべての PDF アノテーションに使用されるべきです。 |
| static readonly [Art](../../aspose.pdf.logicalstructure/structuretypestandard/art/) | (Article) 単一の物語または説明からなる、比較的自己完結型のテキスト本文です。記事は互いに重複しないようにすべきで、他の文章を構成要素として含んではいけません。 |
| static readonly [BibEntry](../../aspose.pdf.logicalstructure/structuretypestandard/bibentry/) | (Bibliography entry) 引用されたコンテンツの外部ソースを特定する参照です。子要素としてラベル（構造タイプ Lbl）を含むことがあります。 |
| static readonly [BlockQuote](../../aspose.pdf.logicalstructure/structuretypestandard/blockquote/) | (Block quotation) 複数の段落からなるテキストで、周囲のテキストの作者とは別の人物に帰属されます。 |
| static readonly [Caption](../../aspose.pdf.logicalstructure/structuretypestandard/caption/) | (Caption) 表や図を説明する短いテキストです。 |
| static readonly [Code](../../aspose.pdf.logicalstructure/structuretypestandard/code/) | (Code) コンピュータプログラムのテキスト断片です。 |
| static readonly [Div](../../aspose.pdf.logicalstructure/structuretypestandard/div/) | (Division) 汎用的なブロックレベル要素または要素のグループです。 |
| static readonly [Document](../../aspose.pdf.logicalstructure/structuretypestandard/document/) | (Document) 完全な文書です。これは複数のパートまたは複数の記事を含む任意の構造ツリーのルート要素です。 |
| static readonly [Figure](../../aspose.pdf.logicalstructure/structuretypestandard/figure/) | (Figure) グラフィックコンテンツの項目です。その配置は Placement レイアウト属性で指定できる場合があります。 |
| static readonly [Form](../../aspose.pdf.logicalstructure/structuretypestandard/form/) | (Form) インタラクティブなフォームフィールドを表すウィジェットアノテーションです。 |
| static readonly [Formula](../../aspose.pdf.logicalstructure/structuretypestandard/formula/) | (Formula) 数学的な式です。 |
| static readonly [H](../../aspose.pdf.logicalstructure/structuretypestandard/h/) | (Heading) 文書のコンテンツのサブディビジョンのラベルです。見出しが付くセクションの最初の子要素である必要があります。 |
| static readonly [H1](../../aspose.pdf.logicalstructure/structuretypestandard/h1/) | レベル 1 見出し。階層的にセクションを入れ子にできない準拠ライターで使用され、入れ子のレベルから見出しのレベルを判定できない場合に使用します。 |
| static readonly [H2](../../aspose.pdf.logicalstructure/structuretypestandard/h2/) | レベル 2 見出し。階層的にセクションを入れ子にできない準拠ライターで使用され、入れ子のレベルから見出しのレベルを判定できない場合に使用します。 |
| static readonly [H3](../../aspose.pdf.logicalstructure/structuretypestandard/h3/) | レベル 3 見出し。階層的にセクションを入れ子にできない準拠ライターで使用され、入れ子のレベルから見出しのレベルを判定できない場合に使用します。 |
| static readonly [H4](../../aspose.pdf.logicalstructure/structuretypestandard/h4/) | レベル 4 見出し。階層的にセクションを入れ子にできない準拠ライターで使用され、入れ子のレベルから見出しのレベルを判定できない場合に使用します。 |
| static readonly [H5](../../aspose.pdf.logicalstructure/structuretypestandard/h5/) | レベル 5 見出し。階層的にセクションを入れ子にできない準拠ライターで使用され、入れ子のレベルから見出しのレベルを判定できない場合に使用します。 |
| static readonly [H6](../../aspose.pdf.logicalstructure/structuretypestandard/h6/) | レベル 6 見出し。階層的にセクションを入れ子にできない準拠ライターで使用され、入れ子のレベルから見出しのレベルを判定できない場合に使用します。 |
| static readonly [Index](../../aspose.pdf.logicalstructure/structuretypestandard/index/) | (Index) 文書本体の指定されたテキストの出現箇所を指し示す参照要素を伴う、識別テキストを含むエントリのシーケンスです。 |
| static readonly [L](../../aspose.pdf.logicalstructure/structuretypestandard/l/) | (List) 同等の意味と重要性を持つ項目のシーケンスです。その直下の子要素はオプションのキャプション（構造タイプ Caption）に続き、1 つ以上のリスト項目（構造タイプ LI）である必要があります。 |
| static readonly [Lbl](../../aspose.pdf.logicalstructure/structuretypestandard/lbl/) | (Label) 同じリストまたは同種の項目グループ内で、特定の項目を他と区別する名前または番号です。 |
| static readonly [LBody](../../aspose.pdf.logicalstructure/structuretypestandard/lbody/) | (List body) リスト項目の記述内容です。たとえば辞書リストでは、用語の定義が含まれます。コンテンツを直接含むことも、他のBLSEを子として持つこともでき、ネストされたリストを含む場合もあります。 |
| static readonly [LI](../../aspose.pdf.logicalstructure/structuretypestandard/li/) | (List item) リストの個々のメンバーです。その子要素はラベル、リスト本文のいずれか、または両方（構造タイプ Lbl または LBody）になることがあります。 |
| static readonly [Link](../../aspose.pdf.logicalstructure/structuretypestandard/link/) | (Link) ILSE のコンテンツの一部と対応するリンクアノテーションまたは複数のリンクアノテーションとの関連付けです。その子要素は、1つ以上のコンテンツ項目または子 ILSE と、関連付けられたリンクアノテーションを特定するオブジェクト参照が1つ以上含まれる必要があります。 |
| static readonly [NonStruct](../../aspose.pdf.logicalstructure/structuretypestandard/nonstruct/) | (Nonstructural element) 本質的な構造的意味を持たないグルーピング要素で、単にグループ化の目的で使用されます。この種の要素は、分割（構造タイプ Div）とは異なり、他の文書形式へ解釈またはエクスポートされるべきではありませんが、子孫要素は通常通り処理されます。 |
| static readonly [Note](../../aspose.pdf.logicalstructure/structuretypestandard/note/) | (Note) 文書本文から参照される説明テキスト項目（脚注や文末脚注など）です。子要素としてラベル（構造タイプ Lbl）を持つことがあります。ノートはそれを参照する本文テキスト内の構造要素の子として含めることも、別の場所（例：文末脚注セクション）に配置し、参照（構造タイプ Reference）によってアクセスすることもできます。 |
| static readonly [P](../../aspose.pdf.logicalstructure/structuretypestandard/p/) | (Paragraph) テキストの低レベルの区分です。 |
| static readonly [Part](../../aspose.pdf.logicalstructure/structuretypestandard/part/) | (Part) 文書の大規模な区分です。この種の要素は記事やセクションをグループ化するのに適しています。 |
| static readonly [Private](../../aspose.pdf.logicalstructure/structuretypestandard/private/) | (Private element) 生成アプリケーションに属するプライベートコンテンツを含むグルーピング要素です。この種の要素の構造的意味は未定義で、準拠する作成者が完全に決定します。Private element およびその子孫は、他の文書形式へ解釈またはエクスポートされてはなりません。 |
| static readonly [Quote](../../aspose.pdf.logicalstructure/structuretypestandard/quote/) | (Quotation) 周囲のテキストの作者以外の人物に帰属するインラインテキストです。 |
| static readonly [RB](../../aspose.pdf.logicalstructure/structuretypestandard/rb/) | (Ruby base text) ルビ注釈が適用される全サイズのテキストです。RB はテキスト、他のインライン要素、またはその混合を含むことができます。RubyAlign属性を持つことがあります。 |
| static readonly [Reference](../../aspose.pdf.logicalstructure/structuretypestandard/reference/) | (Reference) 文書内の他の場所のコンテンツへの引用です。 |
| static readonly [RP](../../aspose.pdf.logicalstructure/structuretypestandard/rp/) | (Ruby punctuation) ルビ注釈テキストを囲む句読点です。ルビスタイルで正しくフォーマットできない場合に通常のコメントとして、または割注としてフォーマットされるときに使用されます。テキスト（通常は単一の左括弧または右括弧などの括弧文字）を含みます。 |
| static readonly [RT](../../aspose.pdf.logicalstructure/structuretypestandard/rt/) | (Ruby annotation text) ルビベーステキストに隣接して配置される小さいサイズのテキストです。テキスト、他のインライン要素、またはその混合を含むことができます。RubyAlign および RubyPosition 属性を持つことがあります。 |
| static readonly [Ruby](../../aspose.pdf.logicalstructure/structuretypestandard/ruby/) | (Ruby; PDF 1.5) 参照先のベーステキストに隣接して配置される、より小さい文字サイズで書かれたサイドノート（アノテーション）です。Ruby 要素は RB、RT、RP 要素を含むこともあります。 |
| static readonly [Sect](../../aspose.pdf.logicalstructure/structuretypestandard/sect/) | (Section) 関連するコンテンツ要素をグループ化するコンテナです。 |
| static readonly [Span](../../aspose.pdf.logicalstructure/structuretypestandard/span/) | (Span) 特定の固有特性を持たない汎用的なインラインテキストです。たとえば、特定のスタイリング属性セットでテキスト範囲を区切るために使用できます。 |
| static readonly [Table](../../aspose.pdf.logicalstructure/structuretypestandard/table/) | (Table) 長方形のデータセルからなる二次元レイアウトで、複雑なサブ構造を持つことがあります。子要素として1つ以上のテーブル行（構造タイプ TR）を含むか、オプションのテーブルヘッド（構造タイプ THead）に続いて1つ以上のテーブルボディ要素（構造タイプ TBody）とオプションのテーブルフッター（構造タイプ TFoot）を持ちます。さらに、テーブルは最初または最後の子としてキャプション（構造タイプ Caption）を持つことがあります。 |
| static readonly [TBody](../../aspose.pdf.logicalstructure/structuretypestandard/tbody/) | (Table body row group; PDF 1.5) テーブルの主本文部分を構成する行のグループです。テーブルが複数ページにまたがる場合、本文領域は行境界で分割されることがあります。テーブルは複数の TBody 要素を持ち、行のセットに対して枠線や背景を描画できるようにします。 |
| static readonly [TD](../../aspose.pdf.logicalstructure/structuretypestandard/td/) | (Table data cell) テーブルのコンテンツの一部であるデータを含むテーブルセルです。 |
| static readonly [TFoot](../../aspose.pdf.logicalstructure/structuretypestandard/tfoot/) | (Table footer row group; PDF 1.5) テーブルのフッターを構成する行のグループです。テーブルが複数ページに分割される場合、これらの行は各テーブル断片の下部に再描画されることがあります（ただし TFoot 要素は1つだけです）。 |
| static readonly [TH](../../aspose.pdf.logicalstructure/structuretypestandard/th/) | (Table header cell) テーブルの1つ以上の行または列を説明するヘッダーテキストを含むテーブルセルです。 |
| static readonly [THead](../../aspose.pdf.logicalstructure/structuretypestandard/thead/) | (Table header row group; PDF 1.5) テーブルのヘッダーを構成する行のグループです。テーブルが複数ページに分割される場合、これらの行は各テーブル断片の上部に再描画されることがあります（ただし THead 要素は1つだけです）。 |
| static readonly [TOC](../../aspose.pdf.logicalstructure/structuretypestandard/toc/) | (Table of contents) 目次項目エントリ（構造タイプ TOCI）や他の入れ子になった目次エントリ（TOC）から構成されるリストです。 |
| static readonly [TOCI](../../aspose.pdf.logicalstructure/structuretypestandard/toci/) | (Table of contents item) 目次の個々のメンバーです。このエントリの子要素は以下の構造タイプのいずれかになる可能性があります： |
| static readonly [TR](../../aspose.pdf.logicalstructure/structuretypestandard/tr/) | (Table row) テーブル内の見出しまたはデータの行です。テーブルヘッダーセルとテーブルデータセル（構造タイプ TH と TD）を含むことがあります。 |
| static readonly [Warichu](../../aspose.pdf.logicalstructure/structuretypestandard/warichu/) | (Warichu; PDF 1.5) 基本テキストに続く（インラインで）参照先のテキスト行の高さ内に、より小さい文字サイズで2行にフォーマットされたコメントまたは注釈です。Warichu 要素は WT および WP 要素を含むこともあります。 |
| static readonly [WP](../../aspose.pdf.logicalstructure/structuretypestandard/wp/) | (Warichu punctuation) WT テキストを囲む句読点です。通常は単一の左括弧または右括弧などの括弧文字が含まれます。JIS X 4051-1995 によれば、Warichu を囲む括弧はフォーマッタの判断でスペース（幅は名目上 1/4 EM）に変換できる場合があります。 |
| static readonly [WT](../../aspose.pdf.logicalstructure/structuretypestandard/wt/) | (Warichu text) Warichu コメントの小さい文字サイズのテキストで、2 行にフォーマットされ、周囲の WP 要素の間に配置されます。 |

### 関連項目

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


