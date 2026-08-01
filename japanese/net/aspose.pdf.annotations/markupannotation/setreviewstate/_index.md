---
title: "MarkupAnnotation.SetReviewState"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "MarkupAnnotation メソッド。アノテーションのレビュー ステートを設定します。Marked および Unmarked ステートは Review StateModel に属さないため無視されます。ステートとステートモデルキーを持つ他のテキストアノテーションに保存されているステートに注意してください。"
type: docs
weight: 140
url: /ja/net/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## SetReviewState(AnnotationState, string) {#setreviewstate_1}

アノテーションのレビュー状態を設定します。Marked と Unmarked の状態は Review StateModel に属さないため無視されます。注：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。

```csharp
public void SetReviewState(AnnotationState state, string userName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| state | AnnotationState | 割り当て用ステータス。 |
| userName | String | コメントヘッダーに表示されるユーザー名です。名前は対象アノテーションのタイトルにある名前と同じにすることも、ステータスが別のユーザーによって設定された場合は異なる名前にすることもできます。 |

### 関連項目

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetReviewState(AnnotationState) {#setreviewstate}

アノテーションのレビュー状態を設定します。Marked と Unmarked の状態は Review StateModel に属さないため無視されます。状態は対象アノテーションを作成したユーザーによって設定され、値は対象アノテーションの Title プロパティから取得されます。注：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。

```csharp
public void SetReviewState(AnnotationState state)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| state | AnnotationState | 割り当て用ステータス。 |

### 関連項目

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


