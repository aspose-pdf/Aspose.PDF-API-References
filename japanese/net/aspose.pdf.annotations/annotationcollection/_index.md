---
title: Class AnnotationCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.AnnotationCollection クラス。アノテーションコレクションを表すクラス
type: docs
weight: 1430
url: /ja/net/aspose.pdf.annotations/annotationcollection/
---
## AnnotationCollection クラス

アノテーションコレクションを表すクラス。

```csharp
public sealed class AnnotationCollection : ICollection<Annotation>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../aspose.pdf.annotations/annotationcollection/count/) { get; } | コレクション内のアノテーションの数を取得します。 |
| [IsReadOnly](../../aspose.pdf.annotations/annotationcollection/isreadonly/) { get; } | コレクションが読み取り専用かどうかを示す値を取得します。 |
| [IsSynchronized](../../aspose.pdf.annotations/annotationcollection/issynchronized/) { get; } | Aspose.Pdf.Annotations.AnnotationCollection へのアクセスが同期されているかどうか（スレッドセーフ）を示す値を取得します。 |
| [Item](../../aspose.pdf.annotations/annotationcollection/item/) { get; } | 取得する要素のインデックス。 |
| [SyncRoot](../../aspose.pdf.annotations/annotationcollection/syncroot/) { get; } | Aspose.Pdf.Annotations.AnnotationCollection へのアクセスを同期するために使用できるオブジェクトを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Accept](../../aspose.pdf.annotations/annotationcollection/accept/)(AnnotationSelector) | アノテーションを処理するためのビジターを受け入れます。 |
| [Add](../../aspose.pdf.annotations/annotationcollection/add/#add)(Annotation) | コレクションにアノテーションを追加します。 |
| [Add](../../aspose.pdf.annotations/annotationcollection/add/#add_1)(Annotation, bool) | コレクションにアノテーションを追加します。ページが回転している場合、アノテーションの矩形はそれに応じて再計算されます。 |
| [Clear](../../aspose.pdf.annotations/annotationcollection/clear/)() | コレクションからすべてのアノテーションを削除します。 |
| [Contains](../../aspose.pdf.annotations/annotationcollection/contains/)(Annotation) | 指定されたアノテーションがコレクションに属しているかどうかを確認します。 |
| [CopyTo](../../aspose.pdf.annotations/annotationcollection/copyto/)(Annotation[], int) | アノテーションの配列をコレクションにコピーします。 |
| [Delete](../../aspose.pdf.annotations/annotationcollection/delete/#delete)() | コレクションからすべてのアノテーションを削除します。 |
| [Delete](../../aspose.pdf.annotations/annotationcollection/delete/#delete_1)(Annotation) | 指定されたアノテーションをコレクションから削除します。 |
| [Delete](../../aspose.pdf.annotations/annotationcollection/delete/#delete_2)(int) | インデックスによってコレクションからアノテーションを削除します。 |
| [FindByName](../../aspose.pdf.annotations/annotationcollection/findbyname/)(string) | 名前によってアノテーションを返します。 |
| [GetEnumerator](../../aspose.pdf.annotations/annotationcollection/getenumerator/)() | コレクションの列挙子を返します。 |
| [Remove](../../aspose.pdf.annotations/annotationcollection/remove/)(Annotation) | 指定されたアノテーションをコレクションから削除します。 |

### 参照

* クラス [Annotation](../annotation/)
* 名前空間 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* アセンブリ [Aspose.PDF](../../)