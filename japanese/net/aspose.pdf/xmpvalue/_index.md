---
title: Class XmpValue
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XmpValue クラス。XMP 値を表します
type: docs
weight: 11500
url: /ja/net/aspose.pdf/xmpvalue/
---
## XmpValue クラス

XMP 値を表します

```csharp
public class XmpValue
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [XmpValue](xmpvalue/#constructor_3)(DateTime) | 日付時刻値のコンストラクタ。 |
| [XmpValue](xmpvalue/#constructor_1)(double) | 浮動小数点値のコンストラクタ。 |
| [XmpValue](xmpvalue/#constructor_2)(int) | 整数値のコンストラクタ。 |
| [XmpValue](xmpvalue/#constructor_4)(string) | 文字列値のコンストラクタ。 |
| [XmpValue](xmpvalue/#constructor)(XmpValue[]) | 配列値のコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IsArray](../../aspose.pdf/xmpvalue/isarray/) { get; } | XmpValue が配列である場合は true を返します。 |
| [IsDateTime](../../aspose.pdf/xmpvalue/isdatetime/) { get; } | 値が DateTime の場合は true を返します。 |
| [IsDouble](../../aspose.pdf/xmpvalue/isdouble/) { get; } | 値が浮動小数点値の場合は true を返します。 |
| [IsField](../../aspose.pdf/xmpvalue/isfield/) { get; } | XmpValue がフィールドである場合は true を返します。 |
| [IsInteger](../../aspose.pdf/xmpvalue/isinteger/) { get; } | 値が整数の場合は true を返します。 |
| [IsNamedValue](../../aspose.pdf/xmpvalue/isnamedvalue/) { get; } | XmpValue が名前付き値である場合は true を返します。 |
| [IsNamedValues](../../aspose.pdf/xmpvalue/isnamedvalues/) { get; } | XmpValue が名前付き値を表す場合は true を返します。 |
| [IsRaw](../../aspose.pdf/xmpvalue/israw/) { get; } | 値がサポートされていない/不明であり、生の XML コードが提供されます。 |
| [IsString](../../aspose.pdf/xmpvalue/isstring/) { get; } | 値が文字列の場合は true を返します。 |
| [IsStructure](../../aspose.pdf/xmpvalue/isstructure/) { get; } | XmpValue が構造体を表す場合は true を返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ToArray](../../aspose.pdf/xmpvalue/toarray/)() | 配列を返します。 |
| [ToDateTime](../../aspose.pdf/xmpvalue/todatetime/)() | 日付時刻に変換します。 |
| [ToDictionary](../../aspose.pdf/xmpvalue/todictionary/)() | 名前付き値を含む辞書を返します。 |
| [ToDouble](../../aspose.pdf/xmpvalue/todouble/)() | double に変換します。 |
| [ToField](../../aspose.pdf/xmpvalue/tofield/)() | XMP 値を XMP フィールドとして返します。 |
| [ToInteger](../../aspose.pdf/xmpvalue/tointeger/)() | 整数に変換します。 |
| [ToNamedValue](../../aspose.pdf/xmpvalue/tonamedvalue/)() | XMP 値を名前付き値として返します。 |
| [ToNamedValues](../../aspose.pdf/xmpvalue/tonamedvalues/)() | XMP 値を名前付き値コレクションとして返します。 |
| [ToRaw](../../aspose.pdf/xmpvalue/toraw/)() | 不明/サポートされていない値の生の XML コード。 |
| override [ToString](../../aspose.pdf/xmpvalue/tostring/#tostring)() | XmpValue の文字列表現を返します。 |
| [ToString](../../aspose.pdf/xmpvalue/tostring/#tostring_1)(IFormatProvider) | 文字列表現を返します。 |
| [ToStringValue](../../aspose.pdf/xmpvalue/tostringvalue/)() | 文字列に変換します。 |
| [ToStructure](../../aspose.pdf/xmpvalue/tostructure/)() | XMP 値を構造体（フィールドのセット）として返します。 |
| [explicit operator](../../aspose.pdf/xmpvalue/op_explicit/#op_explicit) | XmpValue を配列に変換します。 (5 演算子) |
| [implicit operator](../../aspose.pdf/xmpvalue/op_implicit/#op_implicit_4) | 文字列を XmpValue に変換します。 (5 演算子) |

### 参照

* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)