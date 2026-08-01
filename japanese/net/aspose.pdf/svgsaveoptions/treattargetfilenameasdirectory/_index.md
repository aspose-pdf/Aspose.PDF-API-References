---
title: "SvgSaveOptions.TreatTargetFileNameAsDirectory"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "SvgSaveOptions フィールド。このオプションは、要求された出力ファイルと同名のディレクトリがまだ存在しない場合に、出力ファイル自体の代わりにそのディレクトリを作成するかどうかを定義します。その結果、ディレクトリには以下に説明するようにページのすべての出力 SVG 画像が格納されます。最初のページ以外のページの出力ファイルが要求されたディレクトリ内にメインの出力ファイルとして正確に作成される場合、ファイル名に _2...n のサフィックスが付加され、ページ番号に基づいて決定されます。例えば、出力ファイルを CAsposeTestsoutput.svg と定義し、複数のページの svg ファイルが出力に含まれる場合、ページのファイルはディレクトリ CAsposeTests にも作成され、output.svg、output_2.svg、output_3.svg などの名前になります。"
type: docs
weight: 50
url: /ja/net/aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/
---
## SvgSaveOptions.TreatTargetFileNameAsDirectory field

このオプションは、要求された出力ファイル自体ではなく、同名のターゲットディレクトリ（まだ存在しない場合）を作成するかどうかを定義します。その場合、ディレクトリにはページごとのすべての出力 SVG 画像が格納されます（以下参照）。「いいえ」の場合、最初のページ以外のページの出力ファイルはメインの出力ファイルと同じディレクトリに作成されますが、ファイル名に _[2...n] のサフィックスが付加され、ページ番号で決まります。例えば、出力ファイルを "C:\\AsposeTests\\output.svg" と定義し、複数のページの svg ファイルが出力される場合、ページのファイルはディレクトリ "C:\\AsposeTests\\" にも作成され、'output.svg', 'output_2.svg', 'output_3.svg' などの名前になります。

```csharp
public bool TreatTargetFileNameAsDirectory;
```

### 関連項目

* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


