---
title: "ExportFieldsOptions"
linktitle: "ExportFieldsOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "フォームフィールドのエクスポートオプションの基底クラスを表します。"
type: docs
weight: 1310
url: /ja/java/com.aspose.pdf/exportfieldsoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExportFieldsOptions

```
public abstract class ExportFieldsOptions extends Object
```

フォームフィールドのエクスポートオプションの基底クラスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ExportFieldsOptions](#ExportFieldsOptions--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getExportPasswordValue](#getExportPasswordValue--) | パスワード値をエクスポートすべきかどうかを示す値を取得または設定します。値: {@code true} はパスワード値をエクスポートすべきことを示し、{@code false} はそれ以外を示します。 |
| [getFieldSelector](#getFieldSelector--) | 特定のフィールドをエクスポートすべきかどうかを決定するデリゲートを取得します。デリゲートが {@code null} の場合、すべてのフィールドがエクスポートされます（既定の動作）。 |
| [setExportPasswordValue](#setExportPasswordValue-boolean-) | パスワード値をエクスポートすべきかどうかを示す値を取得または設定します。値: {@code true} はパスワード値をエクスポートすべきことを示し、{@code false} はそれ以外を示します。 |
| [setFieldSelector](#setFieldSelector-com.aspose.ms.System.Predicate-) | 特定のフィールドをエクスポートすべきかどうかを決定するデリゲートを設定します。 |

### ExportFieldsOptions {#ExportFieldsOptions--}
```
public ExportFieldsOptions()
```



### getExportPasswordValue {#getExportPasswordValue--}
```
public final boolean getExportPasswordValue()
```

パスワード値をエクスポートすべきかどうかを示す値を取得または設定します。値: {@code true} はパスワード値をエクスポートすべきことを示し、{@code false} はそれ以外を示します。

**Returns:**
ブール値

### getFieldSelector {#getFieldSelector--}
```
public final com.aspose.ms.System.Predicate< Field > getFieldSelector()
```

特定のフィールドをエクスポートすべきかどうかを決定するデリゲートを取得します。デリゲートが {@code null} の場合、すべてのフィールドがエクスポートされます（既定の動作）。

**Returns:**
特定のフィールドをエクスポートすべきかどうかを決定するデリゲート。

### setExportPasswordValue {#setExportPasswordValue-boolean-}
```
public final void setExportPasswordValue(boolean value)
```

パスワード値をエクスポートすべきかどうかを示す値を取得または設定します。値: {@code true} はパスワード値をエクスポートすべきことを示し、{@code false} はそれ以外を示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setFieldSelector {#setFieldSelector-com.aspose.ms.System.Predicate-}
特定のフィールドをエクスポートすべきかどうかを決定するデリゲートを設定します。
