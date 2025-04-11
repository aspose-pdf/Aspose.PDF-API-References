---
title: PageCollectionExtensions.AddBatesNumbering
second_title: Aspose.PDF for .NET API Reference
description: PageCollectionExtensions メソッド。指定されたアクションを使用して、指定されたページコレクションの各ページにベイツ番号を追加します。
type: docs
weight: 10
url: /ja/net/aspose.pdf/pagecollectionextensions/addbatesnumbering/
---
## AddBatesNumbering(this PageCollection, Action&lt;BatesNArtifact&gt;) {#addbatesnumbering_1}

指定されたアクションを使用して、指定されたページコレクションの各ページにベイツ番号を追加します。

```csharp
public static void AddBatesNumbering(this PageCollection pageCollection, 
    Action<BatesNArtifact> action)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageCollection | PageCollection | ベイツ番号が追加されるページのコレクション。 |
| action | Action`1 | 各ページに追加する前にBatesNArtifactを構成するアクション。 |

### 参照

* クラス [PageCollection](../../pagecollection/)
* クラス [BatesNArtifact](../../batesnartifact/)
* クラス [PageCollectionExtensions](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## AddBatesNumbering(this PageCollection, BatesNArtifact) {#addbatesnumbering}

指定されたベイツ番号アーティファクトを、指定されたページコレクションの各ページに追加します。

```csharp
public static void AddBatesNumbering(this PageCollection pageCollection, BatesNArtifact artifact)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageCollection | PageCollection | ベイツ番号アーティファクトが追加されるページのコレクション。 |
| artifact | BatesNArtifact | 各ページに追加されるBatesNArtifactインスタンス。 |

### 参照

* クラス [PageCollection](../../pagecollection/)
* クラス [BatesNArtifact](../../batesnartifact/)
* クラス [PageCollectionExtensions](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)