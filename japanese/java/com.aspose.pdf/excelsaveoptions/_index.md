---
title: "ExcelSaveOptions"
linktitle: "ExcelSaveOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "Excel 形式へのエクスポート用保存オプション"
type: docs
weight: 1260
url: /ja/java/com.aspose.pdf/excelsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.ExcelSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.ExcelSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.ExcelSaveOptions

```
public class ExcelSaveOptions extends UnifiedSaveOptions
```

Excel 形式へのエクスポート用保存オプション

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ExcelSaveOptions](#ExcelSaveOptions--) | コンストラクタ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFormat](#getFormat--) | / * / * 変換時に (仮想) フォントサイズのスケーリングに適用される係数を取得または設定します（Excel テーブルへの変換）/ * レガシーエンジンで。値を小さく設定すると列の検索が容易になり、いくつかの / * ドキュメントで列の結合を防止します。デフォルト値は 0.9; 値を 0 に設定するとアルゴリズムが自動的にスケーリングを選択します。/ * / * / * |
| [getMinimizeTheNumberOfWorksheets](#getMinimizeTheNumberOfWorksheets--) | 結果のブックでワークシートの数を最小化する必要がある場合は true に設定します。デフォルト値は false です; これは各 PDF ページを個別のワークシートとして保存することを意味します。 |
| [isInsertBlankColumnAtFirst](#isInsertBlankColumnAtFirst--) | ワークシートの最初の列として空白列の挿入を抑制する必要がある場合は false に設定します。デフォルト値は true です; これは空白列が挿入されることを意味します。 |
| [isUniformWorksheets](#isUniformWorksheets--) | ドキュメント全体で均一な列分割を使用する場合は true に設定します。デフォルト値は false です; これは列の分割が各ページごとに独立することを意味します。 |
| [setFormat](#setFormat-com.aspose.pdf.ExcelSaveOptions.ExcelFormat-) | 出力形式 |
| [setInsertBlankColumnAtFirst](#setInsertBlankColumnAtFirst-boolean-) | ワークシートの最初の列として空白列の挿入を抑制する必要がある場合は false に設定します。デフォルト値は true です; これは空白列が挿入されることを意味します。 |
| [setMinimizeTheNumberOfWorksheets](#setMinimizeTheNumberOfWorksheets-boolean-) | 結果のブックでワークシートの数を最小化する必要がある場合は true に設定します。デフォルト値は false です; これは各 PDF ページを個別のワークシートとして保存することを意味します。 |
| [setUniformWorksheets](#setUniformWorksheets-boolean-) | 変換に使用される変換エンジンを定義します。 |

### ExcelSaveOptions {#ExcelSaveOptions--}
```
public ExcelSaveOptions()
```

コンストラクタ

### getFormat {#getFormat--}
```
public ExcelSaveOptions.ExcelFormat getFormat()
```

/ * / * 変換時に (仮想) フォントサイズのスケーリングに適用される係数を取得または設定します（Excel テーブルへの変換）/ * レガシーエンジンで。値を小さく設定すると列の検索が容易になり、いくつかの / * ドキュメントで列の結合を防止します。デフォルト値は 0.9; 値を 0 に設定するとアルゴリズムが自動的にスケーリングを選択します。/ * / * / *

**Returns:**
double 値 /

### getMinimizeTheNumberOfWorksheets {#getMinimizeTheNumberOfWorksheets--}
```
public boolean getMinimizeTheNumberOfWorksheets()
```

結果のブックでワークシートの数を最小化する必要がある場合は true に設定します。デフォルト値は false です; これは各 PDF ページを個別のワークシートとして保存することを意味します。

**Returns:**
ブール値

### isInsertBlankColumnAtFirst {#isInsertBlankColumnAtFirst--}
```
public boolean isInsertBlankColumnAtFirst()
```

ワークシートの最初の列として空白列の挿入を抑制する必要がある場合は false に設定します。デフォルト値は true です; これは空白列が挿入されることを意味します。

**Returns:**
ブール値

### isUniformWorksheets {#isUniformWorksheets--}
```
public boolean isUniformWorksheets()
```

ドキュメント全体で均一な列分割を使用する場合は true に設定します。デフォルト値は false です; これは列の分割が各ページごとに独立することを意味します。

**Returns:**
ブール値

### setFormat {#setFormat-com.aspose.pdf.ExcelSaveOptions.ExcelFormat-}
出力形式

### setInsertBlankColumnAtFirst {#setInsertBlankColumnAtFirst-boolean-}
```
public void setInsertBlankColumnAtFirst(boolean value)
```

ワークシートの最初の列として空白列の挿入を抑制する必要がある場合は false に設定します。デフォルト値は true です; これは空白列が挿入されることを意味します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setMinimizeTheNumberOfWorksheets {#setMinimizeTheNumberOfWorksheets-boolean-}
```
public void setMinimizeTheNumberOfWorksheets(boolean value)
```

結果のブックでワークシートの数を最小化する必要がある場合は true に設定します。デフォルト値は false です; これは各 PDF ページを個別のワークシートとして保存することを意味します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setUniformWorksheets {#setUniformWorksheets-boolean-}
```
public void setUniformWorksheets(boolean value)
```

変換に使用される変換エンジンを定義します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  |  |
