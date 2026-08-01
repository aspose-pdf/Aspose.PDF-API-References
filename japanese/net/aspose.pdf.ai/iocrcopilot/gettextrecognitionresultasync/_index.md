---
title: "IOcrCopilot.GetTextRecognitionResultAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "IOcrCopilot メソッド。PDF ドキュメントと画像ファイルのテキスト認識結果を非同期で取得します。サポートされている画像タイプは PNG .png、JPEG .jpeg および .jpg、WEBP .webp、アニメーションでない GIF .gif です。"
type: docs
weight: 10
url: /ja/net/aspose.pdf.ai/iocrcopilot/gettextrecognitionresultasync/
---
## IOcrCopilot.GetTextRecognitionResultAsync method

PDF ドキュメントと画像ファイルのテキスト認識結果を非同期で取得します。サポートされている画像タイプ: PNG (.png)、JPEG (.jpeg および .jpg)、WEBP (.webp)、アニメーションなし GIF (.gif)。

```csharp
public Task<List<TextRecognitionResult>> GetTextRecognitionResultAsync(
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのオプションのキャンセルトークンです。 |

### 戻り値

非同期操作を表すタスクです。タスクの結果には [`TextRecognitionResult`](../../textrecognitionresult/) のリストが含まれます。

### 関連項目

* class [TextRecognitionResult](../../textrecognitionresult/)
* interface [IOcrCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


