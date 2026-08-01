---
title: "XImage.TrySetAlternativeText"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "XImage メソッド。ページ上の XImage の代替テキストを設定します"
type: docs
weight: 180
url: /ja/net/aspose.pdf/ximage/trysetalternativetext/
---
## XImage.TrySetAlternativeText method

ページ上の XImage の代替テキストを設定します。

```csharp
public bool TrySetAlternativeText(string alternativeText, Page page)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| alternativeText | String | 指定する代替テキスト。 |
| ページ | ページ | XImage が配置されているページ。 |

### 戻り値

XImage の alternativeText が設定されている場合は True。設定されていない場合は False。

## 備考

メソッドは次の場合に false を返します: - 指定されたページに XImage が見つからない場合。 - ページ上に XImage が複数回出現し、構造要素が異なるため、どのインスタンスに代替テキストを設定すべきかが曖昧な場合。

### 関連項目

* class [Page](../../page/)
* class [XImage](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


