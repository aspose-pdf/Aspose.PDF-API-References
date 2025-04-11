---
title: SvgSaveOptions.TreatTargetFileNameAsDirectory
second_title: Aspose.PDF for .NET API Reference
description: SvgSaveOptions フィールド。このオプションは、要求された出力ファイルと同じ名前のターゲットディレクトリがまだ存在しない場合に作成されるかどうかを定義します。これにより、ディレクトリには以下に説明するように、ページのすべての出力 SVG 画像が含まれます。最初のページ以外のページの出力ファイルは、メイン出力ファイルと同じ要求されたディレクトリに正確に作成されますが、ファイル名にはページ番号によって定義されるサフィックス _2...n が含まれます。例えば、出力ファイルを "C:\AsposeTests\output.svg" と定義し、出力に複数のページの svg ファイルが含まれる場合、ページのファイルも "C:\AsposeTests\" ディレクトリに作成され、名前は 'output.svg', 'output_2.svg', 'output_3.svg' などになります。
type: docs
weight: 50
url: /ja/net/aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/
---
## SvgSaveOptions.TreatTargetFileNameAsDirectory フィールド

このオプションは、要求された出力ファイルと同じ名前のターゲットディレクトリ（まだ存在しない場合）が作成されるかどうかを定義します。これにより、ディレクトリにはページのすべての出力 SVG 画像が含まれます（以下に説明するように）。そうでない場合、最初のページ以外のページの出力ファイルは、メイン出力ファイルと同じ要求されたディレクトリに正確に作成されますが、ファイル名にはページ番号によって定義されるサフィックス _[2...n] が含まれます。例えば、出力ファイルを "C:\AsposeTests\output.svg" と定義し、出力に複数のページの svg ファイルが含まれる場合、ページのファイルも "C:\AsposeTests\" ディレクトリに作成され、名前は 'output.svg', 'output_2.svg', 'output_3.svg' などになります。

```csharp
public bool TreatTargetFileNameAsDirectory;
```

### 参照

* クラス [SvgSaveOptions](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)