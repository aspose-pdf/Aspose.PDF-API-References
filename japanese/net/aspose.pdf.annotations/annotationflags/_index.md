---
title: "列挙体 AnnotationFlags"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Annotations.AnnotationFlags 列挙体。Annotation のさまざまな特性を指定するフラグの集合です。"
type: docs
weight: 1530
url: /ja/net/aspose.pdf.annotations/annotationflags/
---
## AnnotationFlags enumeration

注釈のさまざまな特性を指定するフラグの集合です。

```csharp
[Flags]
public enum AnnotationFlags
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Default | `0` | デフォルト値。 |
| Invisible | `1` | 設定されている場合、標準の Annotation タイプのいずれにも属さず、Annotation ハンドラが利用できない場合は、その Annotation を表示しません。クリアされている場合、存在する場合は、その外観辞書で指定された外観ストリームを使用して、未知の Annotation を表示します。 |
| Hidden | `2` | 設定されている場合、Annotation のタイプや Annotation ハンドラの有無に関係なく、Annotation を表示・印刷せず、ユーザーとの相互作用も許可しません。画面スペースが限られている場合、外観ストリームと組み合わせて選択的に Annotation を非表示・表示する機能を使用し、オンラインヘルプシステムに似た機能の補助的なポップアップ情報を表示できます。 |
| Print | `4` | 設定されている場合、Page が印刷されるときに Annotation を印刷します。クリアされている場合、画面に表示されているかどうかに関係なく、Annotation を決して印刷しません。たとえば、インタラクティブなプッシュボタンを表す Annotation など、印刷されたページでは意味を持たない場合に有用です。 |
| NoZoom | `8` | 設定されている場合、ページの拡大率に合わせて Annotation の外観をスケーリングしません。Annotation のページ上の位置（Annotation 矩形の左上隅で定義される）は、ページの拡大率に関係なく固定されたままです。 |
| NoRotate | `10` | 設定されている場合、ページの回転に合わせて Annotation の外観を回転させません。Annotation 矩形の左上隅は、ページの回転に関係なくページ上の固定位置に留まります。 |
| NoView | `20` | 設定されている場合、画面上に注釈を表示せず、ユーザーとの対話を許可しません。注釈は印刷される場合があります（Print フラグの設定に依存します）が、画面表示およびユーザー対話の目的では非表示とみなすべきです。 |
| ReadOnly | `40` | 設定されている場合、注釈がユーザーと対話することを許可しません。注釈は表示または印刷される場合があります（NoView および Print フラグの設定に依存します）が、マウスクリックに応答したり、マウスの動きに応じて外観を変えたりしないようにします。このフラグはウィジェット注釈には無視されます。その機能は関連するフォームフィールドの ReadOnly フラグに置き換えられます。 |
| Locked | `80` | 設定されている場合、注釈の削除やプロパティ（位置やサイズを含む）の変更をユーザーが行うことを許可しません。ただし、このフラグは注釈の内容、例えばフォームフィールドの値の変更は制限しません。 |
| ToggleNoView | `100` | 設定されている場合、特定のイベントに対して NoView フラグの解釈を逆転させます。典型的な使用例は、マウスカーソルが上に乗っているときだけ表示される注釈です。 |
| LockedContents | `200` | 設定されている場合、ユーザーが注釈の内容を変更することを許可しません。このフラグは注釈の削除や、位置やサイズなど他のプロパティの変更を制限しません。 |

### 関連項目

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


