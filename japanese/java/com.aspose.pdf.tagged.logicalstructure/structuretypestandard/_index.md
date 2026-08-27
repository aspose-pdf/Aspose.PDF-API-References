---
title: "StructureTypeStandard"
linktitle: "StructureTypeStandard"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "標準構造タイプを表します。"
type: docs
weight: 130
url: /ja/java/com.aspose.pdf.tagged.logicalstructure/structuretypestandard/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard

```
public final class StructureTypeStandard extends Object
```

標準構造タイプを表します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [Annot](#Annot) | (Annotation; PDF 1.5) ILSE のコンテンツの一部と対応する PDF アノテーションとの関連付けです。Annot はリンクアノテーションとウィジェットアノテーションを除くすべての PDF アノテーションに使用されるものとします。 |
| [Art](#Art) | (Article) 単一の物語または説明を構成する、比較的自立したテキスト本文です。記事は互いに重複しないようにすべきで、つまり他の記事を構成要素として含んではいけません。 |
| [BibEntry](#BibEntry) | (Bibliography entry) 引用されたコンテンツの外部ソースを特定する参照です。子要素としてラベル（構造タイプ Lbl）を含むことがあります。文献エントリは通常、引用されたコンテンツの著者、作品、出版社などを示す構成要素を含む可能性がありますが、この詳細レベルでは標準の構造タイプは定義されていません。 |
| [BlockQuote](#BlockQuote) | (Block quotation) 周囲のテキストの作者とは別の人物に帰属する、1つ以上の段落からなるテキストの一部です。 |
| [Caption](#Caption) | (Caption) 表または図を説明する簡潔なテキストです。 |
| [Code](#Code) | (Code) コンピュータプログラムのテキストの断片です。 |
| [Div](#Div) | (Division) 汎用的なブロックレベル要素または要素のグループです。 |
| [Document](#Document) | (Document) 完全な文書です。これは複数のパートまたは複数の記事を含む任意の構造ツリーのルート要素です。 |
| [Figure](#Figure) | (Figure) グラフィックコンテンツの項目です。その配置は Placement レイアウト属性で指定できる場合があります。 |
| [Form](#Form) | (Form) インタラクティブなフォームフィールドを表すウィジェットアノテーションです。 |
| [Formula](#Formula) | (Formula) 数学的な式です。この構造タイプは、コンテンツ要素全体を式として識別する場合にのみ有用です。式内の個々の構成要素を識別するための標準構造タイプは定義されていません。書式設定の観点から、式は図（構造タイプ Figure）と同様に扱われるものとします。 |
| [H](#H) | (Heading) 文書コンテンツの細分化のラベルです。見出しが付くセクションの最初の子要素であるべきです。 |
| [H1](#H1) | レベル 1 見出し：階層的にセクションを入れ子にできず、入れ子のレベルから見出しのレベルを判断できない準拠ライターで使用します。 |
| [H2](#H2) | レベル 2 見出し：階層的にセクションを入れ子にできず、入れ子のレベルから見出しのレベルを判断できない準拠ライターで使用します。 |
| [H3](#H3) | Level 3 Heading、階層的にセクションを入れ子にできず、入れ子のレベルから見出しのレベルを判断できない準拠ライターで使用するためのものです。 |
| [H4](#H4) | Level 4 Heading、階層的にセクションを入れ子にできず、入れ子のレベルから見出しのレベルを判断できない準拠ライターで使用するためのものです。 |
| [H5](#H5) | Level 5 Heading、階層的にセクションを入れ子にできず、入れ子のレベルから見出しのレベルを判断できない準拠ライターで使用するためのものです。 |
| [H6](#H6) | Level 6 Heading、階層的にセクションを入れ子にできず、入れ子のレベルから見出しのレベルを判断できない準拠ライターで使用するためのものです。 |
| [Index](#Index) | (Index) 識別テキストを含むエントリのシーケンスで、文書本体内で指定されたテキストの出現箇所を指し示す参照要素が付随しています。 |
| [L](#L) | (List) 同等の意味と重要性を持つ項目のシーケンスです。直下の子要素は、オプションのキャプション（構造タイプ Caption）と、1つ以上のリスト項目（構造タイプ LI）で構成すべきです。 |
| [Lbl](#Lbl) | (Label) 同じリストまたは同種の項目グループ内で、特定の項目を他と区別する名前または番号です。 |
| [LBody](#LBody) | (List body) リスト項目の記述内容です。例えば辞書リストでは、用語の定義が含まれます。コンテンツを直接含む場合もあれば、他のBLSE（入れ子リストを含む可能性あり）を子要素として持つ場合もあります。 |
| [LI](#LI) | (List item) リストの個々のメンバーです。その子要素は1つ以上のラベル、リスト本文、またはその両方（構造タイプ Lbl または LBody）で構成され得ます。 |
| [Link](#Link) | (Link) ILSE のコンテンツの一部と対応するリンクアノテーション（または複数）との関連付けです。その子要素は、1つ以上のコンテンツ項目または子 ILSE と、関連するリンクアノテーションを特定するオブジェクト参照が1つ以上含まれるべきです。 |
| [NonStruct](#NonStruct) | (Nonstructural element) 固有の構造的意味を持たないグルーピング要素で、純粋にグループ化の目的で使用されます。この要素は、分割（構造タイプ Div）とは異なり、他の文書形式へ解釈またはエクスポートされるべきではありませんが、子孫要素は通常通り処理されます。 |
| [Note](#Note) | (Note) 文書本文から参照される脚注や文末脚注などの説明テキスト項目です。子要素としてラベル（構造タイプ Lbl）を持つことがあります。ノートはそれを参照する本文テキスト内の構造要素の子として含めることも、別の場所（例：文末脚注セクション）に配置し、参照（構造タイプ Reference）でアクセスすることもできます。Tagged PDF はページコンテンツ順における脚注の配置を規定しておらず、インラインまたはページ末尾のいずれかは準拠ライターの裁量です。 |
| [P](#P) | (Paragraph) テキストの低レベルな区分です。 |
| [Part](#Part) | (Part) 文書の大規模な区分です。この種の要素は記事やセクションをグループ化するのに適しています。 |
| [Private](#Private) | (Private element) 生成アプリケーション固有のプライベートコンテンツを含むグルーピング要素です。この要素の構造的意味は未定義で、完全に準拠ライターが決定します。Private element およびその子孫は、他の文書形式へ解釈またはエクスポートされてはなりません。 |
| [Quote](#Quote) | (Quotation) 周囲のテキストの作者以外の人物に帰属するインラインテキストです。引用文は単一の段落内にインラインで収める必要があります。これは、1つ以上の完全な段落（または段落として扱われる他の要素）で構成されるブロックレベル要素 BlockQuote とは異なります。 |
| [RB](#RB) | (Ruby base text) ルビ注釈が適用される全サイズのテキストです。RB はテキスト、他のインライン要素、またはその混合を含むことができ、RubyAlign 属性を持つことがあります。 |
| [Reference](#Reference) | (Reference) 文書内の他の場所のコンテンツへの引用です。 |
| [RP](#RP) | (Ruby punctuation) ルビ注釈テキストを囲む句読点です。ルビが正しくルビスタイルでフォーマットできず、通常のコメントとして、または割注（割注）としてフォーマットされる場合にのみ使用されます。通常、単一の左括弧または右括弧などの括弧文字が含まれます。 |
| [RT](#RT) | (Ruby annotation text) ルビベーステキストに隣接して配置される小サイズのテキストです。テキスト、他のインライン要素、またはその混合を含むことができ、RubyAlign および RubyPosition 属性を持つことがあります。 |
| [Ruby](#Ruby) | (Ruby; PDF 1.5) 参照先のベーステキストに隣接して配置される、小さな文字サイズで書かれたサイドノート（アノテーション）です。Ruby 要素は RB、RT、RP 要素を含むことがあります。(Ruby) ルビ全体を包むラッパーで、1つの RB 要素の後に RT 要素、または RP、RT、RP の3要素グループが続きます。Ruby 要素およびそのコンテンツ要素は複数行にまたがってはなりません。 |
| [Sect](#Sect) | (Section) 関連するコンテンツ要素をグループ化するためのコンテナです。 |
| [Span](#Span) | (Span) 特定の固有特性を持たない汎用的なインラインテキストです。例えば、特定のスタイル属性セットでテキスト範囲を区切る際に使用できます。 |
| [Table](#Table) | (Table) 矩形データセルの二次元レイアウトで、複雑なサブ構造を持つことがあります。子要素として1つ以上のテーブル行（構造タイプ TR）を含むか、オプションのテーブルヘッド（構造タイプ THead）に続いて1つ以上のテーブルボディ要素（構造タイプ TBody）とオプションのテーブルフッター（構造タイプ TFoot）を持ちます。さらに、テーブルは最初または最後の子要素としてキャプション（構造タイプ Caption）を持つことがあります。 |
| [TBody](#TBody) | (Table body row group; PDF 1.5) テーブルの主要な本体部分を構成する行のグループです。テーブルが複数ページにまたがる場合、本体領域は行境界で分割されることがあります。テーブルは複数の TBody 要素を持ち、行のセットに対して枠線や背景を描画できるようにします。 |
| [TD](#TD) | (Table data cell) テーブルのコンテンツの一部であるデータを含むテーブルセル。 |
| [TFoot](#TFoot) | (Table footer row group; PDF 1.5) テーブルのフッターを構成する行のグループ。テーブルが複数ページに分割される場合、これらの行は各テーブルフラグメントの下部に再描画されることがあります（ただし TFoot 要素は1つだけです）。 |
| [TH](#TH) | (Table header cell) テーブルの1つまたは複数の行または列を説明するヘッダー文字列を含むテーブルセル。 |
| [THead](#THead) | (Table header row group; PDF 1.5) テーブルのヘッダーを構成する行のグループ。テーブルが複数ページに分割される場合、これらの行は各テーブルフラグメントの上部に再描画されることがあります（ただし THead 要素は1つだけです）。 |
| [TOC](#TOC) | (Table of contents) 目次項目エントリ（構造タイプ TOCI）や他の入れ子になった目次エントリ（TOC）で構成されたリスト。TOCI エントリのみを含む目次エントリはフラットな階層を表し、他の入れ子 TOC エントリ（場合によっては TOCI エントリも）を含む目次エントリはより複雑な階層を表します。理想的には、最上位の目次エントリの階層は文書本体の構造を反映します。 |
| [TOCI](#TOCI) | (Table of contents item) 目次の個々のメンバー。このエントリの子要素は以下の構造タイプのいずれかになる可能性があります：Lbl - ラベル、Reference - タイトルとページ番号への参照、NonStruct - リーダーアーティファクトをラップする非構造要素、P - 説明テキスト、TOC - 目次エントリで説明されているように階層的目次のための目次要素。 |
| [TR](#TR) | (Table row) テーブル内の見出しまたはデータの行。テーブルヘッダーセルとテーブルデータセル（構造タイプ TH と TD）を含むことがあります。 |
| [Warichu](#Warichu) | (Warichu; PDF 1.5) 基本テキストに続く（インラインで）参照先のテキスト行の高さ内に、より小さい文字サイズで2行にフォーマットされたコメントまたは注釈。Warichu 要素は WT および WP 要素を含むことがあります。(Warichu) Warichu 全体アセンブリを囲むラッパー。WP、WT、WP の3要素グループを含むことがあります。Warichu 要素（およびその内容要素）は、日本工業規格 (JIS) X 4051-1995 で定義された warichu 改行規則に従って複数行に折り返すことができます。 |
| [WP](#WP) | (Warichu punctuation) WT テキストを囲む句読点。通常は単一の左括弧または右括弧などの括弧文字を含みます。JIS X 4051-1995 によれば、warichu を囲む括弧はフォーマッタの判断でスペース（幅は名目上 1/4 EM）に変換されることがあります。 |
| [WT](#WT) | (Warichu text) 2 行にフォーマットされ、周囲の WP 要素の間に配置される、warichu コメントの小さいサイズのテキスト。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [canBeAppended](#canBeAppended-com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard-) |  |
| [createElement](#createElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |
| [getCategory](#getCategory--) | 標準構造タイプのカテゴリを取得します。 |
| [getTag](#getTag--) | {@code StructureElement} のタグ名を取得します。 |
| [to_StructureTypeStandard](#to_StructureTypeStandard-java.lang.String-) | {@link String} から {@link StructureTypeStandard} への明示的な変換を実行します。 |
| [toString](#toString--) | 現在のオブジェクトを表す文字列を返します。 |

### Annot {#Annot}
```
public static final StructureTypeStandard Annot
```

(Annotation; PDF 1.5) ILSE のコンテンツの一部と対応する PDF アノテーションとの関連付けです。Annot はリンクアノテーションとウィジェットアノテーションを除くすべての PDF アノテーションに使用されるものとします。

### Art {#Art}
```
public static final StructureTypeStandard Art
```

(Article) 単一の物語または説明を構成する、比較的自立したテキスト本文です。記事は互いに重複しないようにすべきで、つまり他の記事を構成要素として含んではいけません。

### BibEntry {#BibEntry}
```
public static final StructureTypeStandard BibEntry
```

(Bibliography entry) 引用されたコンテンツの外部ソースを特定する参照です。子要素としてラベル（構造タイプ Lbl）を含むことがあります。文献エントリは通常、引用されたコンテンツの著者、作品、出版社などを示す構成要素を含む可能性がありますが、この詳細レベルでは標準の構造タイプは定義されていません。

### BlockQuote {#BlockQuote}
```
public static final StructureTypeStandard BlockQuote
```

(Block quotation) 周囲のテキストの作者とは別の人物に帰属する、1つ以上の段落からなるテキストの一部です。

### Caption {#Caption}
```
public static final StructureTypeStandard Caption
```

(Caption) 表または図を説明する簡潔なテキストです。

### Code {#Code}
```
public static final StructureTypeStandard Code
```

(Code) コンピュータプログラムのテキストの断片です。

### Div {#Div}
```
public static final StructureTypeStandard Div
```

(Division) 汎用的なブロックレベル要素または要素のグループです。

### Document {#Document}
```
public static final StructureTypeStandard Document
```

(Document) 完全な文書です。これは複数のパートまたは複数の記事を含む任意の構造ツリーのルート要素です。

### Figure {#Figure}
```
public static final StructureTypeStandard Figure
```

(Figure) グラフィックコンテンツの項目です。その配置は Placement レイアウト属性で指定できる場合があります。

### Form {#Form}
```
public static final StructureTypeStandard Form
```

(Form) インタラクティブなフォームフィールドを表すウィジェットアノテーションです。

### Formula {#Formula}
```
public static final StructureTypeStandard Formula
```

(Formula) 数学的な式です。この構造タイプは、コンテンツ要素全体を式として識別する場合にのみ有用です。式内の個々の構成要素を識別するための標準構造タイプは定義されていません。書式設定の観点から、式は図（構造タイプ Figure）と同様に扱われるものとします。

### H {#H}
```
public static final StructureTypeStandard H
```

(Heading) 文書コンテンツの細分化のラベルです。見出しが付くセクションの最初の子要素であるべきです。

### H1 {#H1}
```
public static final StructureTypeStandard H1
```

レベル 1 見出し：階層的にセクションを入れ子にできず、入れ子のレベルから見出しのレベルを判断できない準拠ライターで使用します。

### H2 {#H2}
```
public static final StructureTypeStandard H2
```

レベル 2 見出し：階層的にセクションを入れ子にできず、入れ子のレベルから見出しのレベルを判断できない準拠ライターで使用します。

### H3 {#H3}
```
public static final StructureTypeStandard H3
```

Level 3 Heading、階層的にセクションを入れ子にできず、入れ子のレベルから見出しのレベルを判断できない準拠ライターで使用するためのものです。

### H4 {#H4}
```
public static final StructureTypeStandard H4
```

Level 4 Heading、階層的にセクションを入れ子にできず、入れ子のレベルから見出しのレベルを判断できない準拠ライターで使用するためのものです。

### H5 {#H5}
```
public static final StructureTypeStandard H5
```

Level 5 Heading、階層的にセクションを入れ子にできず、入れ子のレベルから見出しのレベルを判断できない準拠ライターで使用するためのものです。

### H6 {#H6}
```
public static final StructureTypeStandard H6
```

Level 6 Heading、階層的にセクションを入れ子にできず、入れ子のレベルから見出しのレベルを判断できない準拠ライターで使用するためのものです。

### Index {#Index}
```
public static final StructureTypeStandard Index
```

(Index) 識別テキストを含むエントリのシーケンスで、文書本体内で指定されたテキストの出現箇所を指し示す参照要素が付随しています。

### L {#L}
```
public static final StructureTypeStandard L
```

(List) 同等の意味と重要性を持つ項目のシーケンスです。直下の子要素は、オプションのキャプション（構造タイプ Caption）と、1つ以上のリスト項目（構造タイプ LI）で構成すべきです。

### Lbl {#Lbl}
```
public static final StructureTypeStandard Lbl
```

(Label) 同じリストまたは同種の項目グループ内で、特定の項目を他と区別する名前または番号です。

### LBody {#LBody}
```
public static final StructureTypeStandard LBody
```

(List body) リスト項目の記述内容です。例えば辞書リストでは、用語の定義が含まれます。コンテンツを直接含む場合もあれば、他のBLSE（入れ子リストを含む可能性あり）を子要素として持つ場合もあります。

### LI {#LI}
```
public static final StructureTypeStandard LI
```

(List item) リストの個々のメンバーです。その子要素は1つ以上のラベル、リスト本文、またはその両方（構造タイプ Lbl または LBody）で構成され得ます。

### Link {#Link}
```
public static final StructureTypeStandard Link
```

(Link) ILSE のコンテンツの一部と対応するリンクアノテーション（または複数）との関連付けです。その子要素は、1つ以上のコンテンツ項目または子 ILSE と、関連するリンクアノテーションを特定するオブジェクト参照が1つ以上含まれるべきです。

### NonStruct {#NonStruct}
```
public static final StructureTypeStandard NonStruct
```

(Nonstructural element) 固有の構造的意味を持たないグルーピング要素で、純粋にグループ化の目的で使用されます。この要素は、分割（構造タイプ Div）とは異なり、他の文書形式へ解釈またはエクスポートされるべきではありませんが、子孫要素は通常通り処理されます。

### Note {#Note}
```
public static final StructureTypeStandard Note
```

(Note) 文書本文から参照される脚注や文末脚注などの説明テキスト項目です。子要素としてラベル（構造タイプ Lbl）を持つことがあります。ノートはそれを参照する本文テキスト内の構造要素の子として含めることも、別の場所（例：文末脚注セクション）に配置し、参照（構造タイプ Reference）でアクセスすることもできます。Tagged PDF はページコンテンツ順における脚注の配置を規定しておらず、インラインまたはページ末尾のいずれかは準拠ライターの裁量です。

### P {#P}
```
public static final StructureTypeStandard P
```

(Paragraph) テキストの低レベルな区分です。

### Part {#Part}
```
public static final StructureTypeStandard Part
```

(Part) 文書の大規模な区分です。この種の要素は記事やセクションをグループ化するのに適しています。

### Private {#Private}
```
public static final StructureTypeStandard Private
```

(Private element) 生成アプリケーション固有のプライベートコンテンツを含むグルーピング要素です。この要素の構造的意味は未定義で、完全に準拠ライターが決定します。Private element およびその子孫は、他の文書形式へ解釈またはエクスポートされてはなりません。

### Quote {#Quote}
```
public static final StructureTypeStandard Quote
```

(Quotation) 周囲のテキストの作者以外の人物に帰属するインラインテキストです。引用文は単一の段落内にインラインで収める必要があります。これは、1つ以上の完全な段落（または段落として扱われる他の要素）で構成されるブロックレベル要素 BlockQuote とは異なります。

### RB {#RB}
```
public static final StructureTypeStandard RB
```

(Ruby base text) ルビ注釈が適用される全サイズのテキストです。RB はテキスト、他のインライン要素、またはその混合を含むことができ、RubyAlign 属性を持つことがあります。

### Reference {#Reference}
```
public static final StructureTypeStandard Reference
```

(Reference) 文書内の他の場所のコンテンツへの引用です。

### RP {#RP}
```
public static final StructureTypeStandard RP
```

(Ruby punctuation) ルビ注釈テキストを囲む句読点です。ルビが正しくルビスタイルでフォーマットできず、通常のコメントとして、または割注（割注）としてフォーマットされる場合にのみ使用されます。通常、単一の左括弧または右括弧などの括弧文字が含まれます。

### RT {#RT}
```
public static final StructureTypeStandard RT
```

(Ruby annotation text) ルビベーステキストに隣接して配置される小サイズのテキストです。テキスト、他のインライン要素、またはその混合を含むことができ、RubyAlign および RubyPosition 属性を持つことがあります。

### Ruby {#Ruby}
```
public static final StructureTypeStandard Ruby
```

(Ruby; PDF 1.5) 参照先のベーステキストに隣接して配置される、小さな文字サイズで書かれたサイドノート（アノテーション）です。Ruby 要素は RB、RT、RP 要素を含むことがあります。(Ruby) ルビ全体を包むラッパーで、1つの RB 要素の後に RT 要素、または RP、RT、RP の3要素グループが続きます。Ruby 要素およびそのコンテンツ要素は複数行にまたがってはなりません。

### Sect {#Sect}
```
public static final StructureTypeStandard Sect
```

(Section) 関連するコンテンツ要素をグループ化するためのコンテナです。

### Span {#Span}
```
public static final StructureTypeStandard Span
```

(Span) 特定の固有特性を持たない汎用的なインラインテキストです。例えば、特定のスタイル属性セットでテキスト範囲を区切る際に使用できます。

### Table {#Table}
```
public static final StructureTypeStandard Table
```

(Table) 矩形データセルの二次元レイアウトで、複雑なサブ構造を持つことがあります。子要素として1つ以上のテーブル行（構造タイプ TR）を含むか、オプションのテーブルヘッド（構造タイプ THead）に続いて1つ以上のテーブルボディ要素（構造タイプ TBody）とオプションのテーブルフッター（構造タイプ TFoot）を持ちます。さらに、テーブルは最初または最後の子要素としてキャプション（構造タイプ Caption）を持つことがあります。

### TBody {#TBody}
```
public static final StructureTypeStandard TBody
```

(Table body row group; PDF 1.5) テーブルの主要な本体部分を構成する行のグループです。テーブルが複数ページにまたがる場合、本体領域は行境界で分割されることがあります。テーブルは複数の TBody 要素を持ち、行のセットに対して枠線や背景を描画できるようにします。

### TD {#TD}
```
public static final StructureTypeStandard TD
```

(Table data cell) テーブルのコンテンツの一部であるデータを含むテーブルセル。

### TFoot {#TFoot}
```
public static final StructureTypeStandard TFoot
```

(Table footer row group; PDF 1.5) テーブルのフッターを構成する行のグループ。テーブルが複数ページに分割される場合、これらの行は各テーブルフラグメントの下部に再描画されることがあります（ただし TFoot 要素は1つだけです）。

### TH {#TH}
```
public static final StructureTypeStandard TH
```

(Table header cell) テーブルの1つまたは複数の行または列を説明するヘッダー文字列を含むテーブルセル。

### THead {#THead}
```
public static final StructureTypeStandard THead
```

(Table header row group; PDF 1.5) テーブルのヘッダーを構成する行のグループ。テーブルが複数ページに分割される場合、これらの行は各テーブルフラグメントの上部に再描画されることがあります（ただし THead 要素は1つだけです）。

### TOC {#TOC}
```
public static final StructureTypeStandard TOC
```

(Table of contents) 目次項目エントリ（構造タイプ TOCI）や他の入れ子になった目次エントリ（TOC）で構成されたリスト。TOCI エントリのみを含む目次エントリはフラットな階層を表し、他の入れ子 TOC エントリ（場合によっては TOCI エントリも）を含む目次エントリはより複雑な階層を表します。理想的には、最上位の目次エントリの階層は文書本体の構造を反映します。

### TOCI {#TOCI}
```
public static final StructureTypeStandard TOCI
```

(Table of contents item) 目次の個々のメンバー。このエントリの子要素は以下の構造タイプのいずれかになる可能性があります：Lbl - ラベル、Reference - タイトルとページ番号への参照、NonStruct - リーダーアーティファクトをラップする非構造要素、P - 説明テキスト、TOC - 目次エントリで説明されているように階層的目次のための目次要素。

### TR {#TR}
```
public static final StructureTypeStandard TR
```

(Table row) テーブル内の見出しまたはデータの行。テーブルヘッダーセルとテーブルデータセル（構造タイプ TH と TD）を含むことがあります。

### Warichu {#Warichu}
```
public static final StructureTypeStandard Warichu
```

(Warichu; PDF 1.5) 基本テキストに続く（インラインで）参照先のテキスト行の高さ内に、より小さい文字サイズで2行にフォーマットされたコメントまたは注釈。Warichu 要素は WT および WP 要素を含むことがあります。(Warichu) Warichu 全体アセンブリを囲むラッパー。WP、WT、WP の3要素グループを含むことがあります。Warichu 要素（およびその内容要素）は、日本工業規格 (JIS) X 4051-1995 で定義された warichu 改行規則に従って複数行に折り返すことができます。

### WP {#WP}
```
public static final StructureTypeStandard WP
```

(Warichu punctuation) WT テキストを囲む句読点。通常は単一の左括弧または右括弧などの括弧文字を含みます。JIS X 4051-1995 によれば、warichu を囲む括弧はフォーマッタの判断でスペース（幅は名目上 1/4 EM）に変換されることがあります。

### WT {#WT}
```
public static final StructureTypeStandard WT
```

(Warichu text) 2 行にフォーマットされ、周囲の WP 要素の間に配置される、warichu コメントの小さいサイズのテキスト。

### canBeAppended {#canBeAppended-com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard-}


### createElement {#createElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### getCategory {#getCategory--}
```
public final StructureTypeCategory getCategory()
```

標準構造タイプのカテゴリを取得します。

**Returns:**
値: 標準構造タイプのカテゴリ。

### getTag {#getTag--}
```
public final String getTag()
```

{@code StructureElement} のタグ名を取得します。

**Returns:**
{@code StructureElement} のタグ名。

### to_StructureTypeStandard {#to_StructureTypeStandard-java.lang.String-}
{@link String} から {@link StructureTypeStandard} への明示的な変換を実行します。

### toString {#toString--}
```
public String toString()
```

現在のオブジェクトを表す文字列を返します。

**Returns:**
現在のオブジェクトを表す文字列。
