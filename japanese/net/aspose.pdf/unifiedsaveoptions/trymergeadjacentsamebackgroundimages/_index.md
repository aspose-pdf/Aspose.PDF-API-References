---
title: "UnifiedSaveOptions.TryMergeAdjacentSameBackgroundImages"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "UnifiedSaveOptions フィールド。PDF には、ページや表セルの背景画像が、同一のタイル背景画像を複数隣接させて構成されていることがあります。そのような場合、対象フォーマットのレンダラ（例：DOCS 形式の MsWord）では、Acrobat Reader とは異なる画像エッジのスムージングやアンチエイリアス手法により、背景画像の部分間に目に見える境界が生成されることがあります。エクスポートされたドキュメントに同一背景画像の部分間に目に見える境界があるように見える場合は、この設定を使用して不要な効果を取り除いてください。注意：この品質最適化は通常、変換速度を大幅に低下させるため、必要なときにのみこのオプションを使用してください。"
type: docs
weight: 40
url: /ja/net/aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/
---
## UnifiedSaveOptions.TryMergeAdjacentSameBackgroundImages field

PDF には、ページや表セルの背景画像が、同じタイル背景画像を複数組み合わせて隣接させて構成されていることがあります。そのような場合、対象フォーマットのレンダラ（例：DOCS 形式の MsWord）では、背景画像の各部分間に目に見える境界が生成されることがあります。これは、画像エッジの平滑化（アンチエイリアス）手法が Acrobat Reader と異なるためです。エクスポートされた文書に同じ背景画像の部分間に目に見える境界があるように見える場合は、この設定を使用して不要な効果を取り除いてください。注意！この品質最適化は通常、変換速度を大幅に低下させるため、実際に必要なときにのみこのオプションを使用してください。

```csharp
public bool TryMergeAdjacentSameBackgroundImages;
```

### 関連項目

* class [UnifiedSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


