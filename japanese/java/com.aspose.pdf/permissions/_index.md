---
title: "権限"
linktitle: "権限"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "Binary Flag この列挙体は PDF のユーザー権限を表します。"
type: docs
weight: 3830
url: /ja/java/com.aspose.pdf/permissions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.Permissions, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.Permissions, com.aspose.ms.System.Enum, com.aspose.pdf.Permissions

```
public final class Permissions extends com.aspose.ms.System.Enum
```

Binary Flag この列挙体は PDF のユーザー権限を表します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [AssembleDocument](#AssembleDocument) | (リビジョン 3 以上のセキュリティハンドラ) ドキュメントを組み立てます (ページの挿入、回転、または削除やブックマークやサムネイル画像の作成)、{@code ModifyContent} がクリアされていても。 |
| [ExtractContent](#ExtractContent) | (リビジョン2のセキュリティハンドラ) 文書からテキストとグラフィックをコピーまたはその他の方法で抽出すること、障害を持つユーザーへのアクセシビリティ支援やその他の目的のためにテキストとグラフィックを抽出することを含みます。(リビジョン3以上のセキュリティハンドラ) {@code ExtractContentWithDisabilities} によって制御される操作以外で文書からテキストとグラフィックをコピーまたは抽出します。 |
| [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | (リビジョン3以上のセキュリティハンドラ) テキストとグラフィックを抽出します（障害を持つユーザーへのアクセシビリティ支援やその他の目的のため）。 |
| [FillForm](#FillForm) | (リビジョン3以上のセキュリティハンドラ) 既存のインタラクティブフォームフィールド（署名フィールドを含む）に入力します。{@code ModifyTextAnnotations} がクリアされていても適用されます。 |
| [ModifyContent](#ModifyContent) | 文書の内容を、{@code ModifyTextAnnotations}、{@code FillForm}、および 11 によって制御される操作以外の方法で変更します。 |
| [ModifyTextAnnotations](#ModifyTextAnnotations) | テキスト注釈を追加または変更し、インタラクティブフォームフィールドに入力し、さらに {@code ModifyContent} が設定されている場合は、インタラクティブフォームフィールド（署名フィールドを含む）を作成または変更します。 |
| [PrintDocument](#PrintDocument) | (リビジョン2のセキュリティハンドラ) 文書を印刷します。(リビジョン3以上のセキュリティハンドラ) 文書を印刷します（{@code PrintingQuality} が設定されているかどうかに応じて、最高品質でない場合があります）。 |
| [PrintingQuality](#PrintingQuality) | (リビジョン3以上のセキュリティハンドラ) PDF コンテンツの忠実なデジタルコピーを生成できる表現に文書を印刷します。このビットがクリアされ（ビット3が設定されている）場合、印刷は外観の低レベル表現に制限され、品質が低下する可能性があります。 |

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

(リビジョン 3 以上のセキュリティハンドラ) ドキュメントを組み立てます (ページの挿入、回転、または削除やブックマークやサムネイル画像の作成)、{@code ModifyContent} がクリアされていても。

### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```

(リビジョン2のセキュリティハンドラ) 文書からテキストとグラフィックをコピーまたはその他の方法で抽出すること、障害を持つユーザーへのアクセシビリティ支援やその他の目的のためにテキストとグラフィックを抽出することを含みます。(リビジョン3以上のセキュリティハンドラ) {@code ExtractContentWithDisabilities} によって制御される操作以外で文書からテキストとグラフィックをコピーまたは抽出します。

### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```

(リビジョン3以上のセキュリティハンドラ) テキストとグラフィックを抽出します（障害を持つユーザーへのアクセシビリティ支援やその他の目的のため）。

### FillForm {#FillForm}
```
public static final int FillForm
```

(リビジョン3以上のセキュリティハンドラ) 既存のインタラクティブフォームフィールド（署名フィールドを含む）に入力します。{@code ModifyTextAnnotations} がクリアされていても適用されます。

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

文書の内容を、{@code ModifyTextAnnotations}、{@code FillForm}、および 11 によって制御される操作以外の方法で変更します。

### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```

テキスト注釈を追加または変更し、インタラクティブフォームフィールドに入力し、さらに {@code ModifyContent} が設定されている場合は、インタラクティブフォームフィールド（署名フィールドを含む）を作成または変更します。

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

(リビジョン2のセキュリティハンドラ) 文書を印刷します。(リビジョン3以上のセキュリティハンドラ) 文書を印刷します（{@code PrintingQuality} が設定されているかどうかに応じて、最高品質でない場合があります）。

### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```

(リビジョン3以上のセキュリティハンドラ) PDF コンテンツの忠実なデジタルコピーを生成できる表現に文書を印刷します。このビットがクリアされ（ビット3が設定されている）場合、印刷は外観の低レベル表現に制限され、品質が低下する可能性があります。
