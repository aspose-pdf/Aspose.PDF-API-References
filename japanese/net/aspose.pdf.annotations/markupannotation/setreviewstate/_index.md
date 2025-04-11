---
title: MarkupAnnotation.SetReviewState
second_title: Aspose.PDF for .NET API Reference
description: MarkupAnnotation メソッド。注釈のレビュー状態を設定します。マーク済みおよび未マークの状態は、レビュー状態モデルに属さないため無視されます。他のテキスト注釈に保存されている状態には、state および statemodel キーがあります。
type: docs
weight: 140
url: /ja/net/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## SetReviewState(AnnotationState, string) {#setreviewstate_1}

注釈のレビュー状態を設定します。マーク済みおよび未マークの状態は、レビュー状態モデルに属さないため無視されます。他のテキスト注釈に保存されている状態には、state および statemodel キーがあります。

```csharp
public void SetReviewState(AnnotationState state, string userName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| state | AnnotationState | 割り当ての状態。 |
| userName | String | コメントヘッダーに表示されるユーザー名。名前は、ターゲット注釈のタイトルにある名前と同じか、別のユーザーによって状態が設定された場合は異なることがあります。 |

### 関連項目

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetReviewState(AnnotationState) {#setreviewstate}

注釈のレビュー状態を設定します。マーク済みおよび未マークの状態は、レビュー状態モデルに属さないため無視されます。状態は、ターゲット注釈を作成したユーザーによって設定されます。値は、ターゲット注釈の Title プロパティから取得されます。他のテキスト注釈に保存されている状態には、state および statemodel キーがあります。

```csharp
public void SetReviewState(AnnotationState state)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| state | AnnotationState | 割り当ての状態。 |

### 関連項目

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)