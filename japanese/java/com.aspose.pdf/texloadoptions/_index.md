---
title: "TeXLoadOptions"
linktitle: "TeXLoadOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメントに TeX ファイルをロード/インポートするためのオプションを表します。"
type: docs
weight: 4870
url: /ja/java/com.aspose.pdf/texloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.TeXLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.TeXLoadOptions

```
public class TeXLoadOptions extends LoadOptions
```

PDF ドキュメントに TeX ファイルをロード/インポートするためのオプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TeXLoadOptions](#TeXLoadOptions--) | TeX ファイルを PDF ドキュメントに変換するためのデフォルトのロードオプションを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDateTime](#getDateTime--) | 年、月、日、時間などの日時プリミティブの特定の値を取得/設定します。 |
| [getInputDirectory](#getInputDirectory--) | TeX 入力ディレクトリを取得/設定します。 |
| [getJobName](#getJobName--) | ジョブの名前を取得/設定します。 |
| [getLoadResult](#getLoadResult--) | TeX のロードとコンパイルの結果を取得します - すべてがスムーズに進んだか、コメントやエラーがあったかどうか。 |
| [getNoLigatures](#getNoLigatures--) | すべてのフォントでリガチャを無効にするフラグを取得/設定します。 |
| [getOutputDirectory](#getOutputDirectory--) | TeX 出力ディレクトリを取得/設定します。 |
| [getRasterizeFormulas](#getRasterizeFormulas--) | 数式をラスタライズできるようにするフラグを取得/設定します。 |
| [getRepeat](#getRepeat--) | 入力 TeX ファイルに参照がある場合など、TeX ジョブを 2 回実行する必要があるかどうかを示すフラグを取得/設定します。一般に、この動作はエンジンが組版プロセス中にデータを収集し、最初の実行時に補助ファイルに保存する場合に有用です。2 回目の実行時にエンジンがそのデータを何らかの形で使用します。 |
| [getRequiredInputDirectory](#getRequiredInputDirectory--) | TeX が必要とする入力ディレクトリを取得/設定します。必要な入力とは、メインの .tex ファイルに何らかの形で含まれるファイル（例: 組み込みサポートがないパッケージ）です。 |
| [getShowTerminalOutput](#getShowTerminalOutput--) | コンソールにターミナル出力を表示するかどうかを示すフラグを取得/設定します。 |
| [getSubsetFonts](#getSubsetFonts--) | 出力ファイルでフォントをサブセット化するかどうかを示すフラグを取得/設定します。 |
| [setDateTime](#setDateTime-java.util.Date-) | 年、月、日、時間などの日時プリミティブの特定の値を取得/設定します。 |
| [setInputDirectory](#setInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-) | TeX 入力ディレクトリを取得/設定します。 |
| [setJobName](#setJobName-java.lang.String-) | ジョブの名前を取得/設定します。 |
| [setNoLigatures](#setNoLigatures-boolean-) | すべてのフォントでリガチャを無効にするフラグを取得/設定します。 |
| [setOutputDirectory](#setOutputDirectory-com.aspose.pdf.tex.ITeXOutputDirectory-) | TeX 出力ディレクトリを取得/設定します。 |
| [setRasterizeFormulas](#setRasterizeFormulas-boolean-) | 数式をラスタライズできるようにするフラグを取得/設定します。 |
| [setRepeat](#setRepeat-boolean-) | 入力 TeX ファイルに参照がある場合など、TeX ジョブを 2 回実行する必要があるかどうかを示すフラグを取得/設定します。一般に、この動作はエンジンが組版プロセス中にデータを収集し、最初の実行時に補助ファイルに保存する場合に有用です。2 回目の実行時にエンジンがそのデータを何らかの形で使用します。 |
| [setRequiredInputDirectory](#setRequiredInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-) | TeX が必要とする入力ディレクトリを取得/設定します。必要な入力とは、メインの .tex ファイルに何らかの形で含まれるファイル（例: 組み込みサポートがないパッケージ）です。 |
| [setShowTerminalOutput](#setShowTerminalOutput-boolean-) | コンソールにターミナル出力を表示するかどうかを示すフラグを取得/設定します。 |
| [setSubsetFonts](#setSubsetFonts-boolean-) | 出力ファイルでフォントをサブセット化するかどうかを示すフラグを取得/設定します。 |

### TeXLoadOptions {#TeXLoadOptions--}
```
public TeXLoadOptions()
```

TeX ファイルを PDF ドキュメントに変換するためのデフォルトのロードオプションを作成します。

### getDateTime {#getDateTime--}
```
public final Date getDateTime()
```

年、月、日、時間などの日時プリミティブの特定の値を取得/設定します。

**Returns:**
Date インスタンス

### getInputDirectory {#getInputDirectory--}
```
public final ITeXInputDirectory getInputDirectory()
```

TeX 入力ディレクトリを取得/設定します。

**Returns:**
ITeXInputDirectory インスタンス

### getJobName {#getJobName--}
```
public final String getJobName()
```

ジョブの名前を取得/設定します。

**Returns:**
文字列値

### getLoadResult {#getLoadResult--}
```
public final int getLoadResult()
```

TeX のロードとコンパイルの結果を取得します - すべてがスムーズに進んだか、コメントやエラーがあったかどうか。

**Returns:**
TeXLoadResult 要素

### getNoLigatures {#getNoLigatures--}
```
public final boolean getNoLigatures()
```

すべてのフォントでリガチャを無効にするフラグを取得/設定します。

**Returns:**
ブール値

### getOutputDirectory {#getOutputDirectory--}
```
public final ITeXOutputDirectory getOutputDirectory()
```

TeX 出力ディレクトリを取得/設定します。

**Returns:**
ITeXOutputDirectory インスタンス

### getRasterizeFormulas {#getRasterizeFormulas--}
```
public final boolean getRasterizeFormulas()
```

数式をラスタライズできるようにするフラグを取得/設定します。

**Returns:**
ブール値

### getRepeat {#getRepeat--}
```
public final boolean getRepeat()
```

入力 TeX ファイルに参照がある場合など、TeX ジョブを 2 回実行する必要があるかどうかを示すフラグを取得/設定します。一般に、この動作はエンジンが組版プロセス中にデータを収集し、最初の実行時に補助ファイルに保存する場合に有用です。2 回目の実行時にエンジンがそのデータを何らかの形で使用します。

**Returns:**
ブール値

### getRequiredInputDirectory {#getRequiredInputDirectory--}
```
public final ITeXInputDirectory getRequiredInputDirectory()
```

TeX が必要とする入力ディレクトリを取得/設定します。必要な入力とは、メインの .tex ファイルに何らかの形で含まれるファイル（例: 組み込みサポートがないパッケージ）です。

**Returns:**
ITeXInputDirectory インスタンス

### getShowTerminalOutput {#getShowTerminalOutput--}
```
public final boolean getShowTerminalOutput()
```

コンソールにターミナル出力を表示するかどうかを示すフラグを取得/設定します。

**Returns:**
ブール値

### getSubsetFonts {#getSubsetFonts--}
```
public final boolean getSubsetFonts()
```

出力ファイルでフォントをサブセット化するかどうかを示すフラグを取得/設定します。

**Returns:**
ブール値

### setDateTime {#setDateTime-java.util.Date-}
年、月、日、時間などの日時プリミティブの特定の値を取得/設定します。

### setInputDirectory {#setInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-}
TeX 入力ディレクトリを取得/設定します。

### setJobName {#setJobName-java.lang.String-}
ジョブの名前を取得/設定します。

### setNoLigatures {#setNoLigatures-boolean-}
```
public final void setNoLigatures(boolean value)
```

すべてのフォントでリガチャを無効にするフラグを取得/設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setOutputDirectory {#setOutputDirectory-com.aspose.pdf.tex.ITeXOutputDirectory-}
TeX 出力ディレクトリを取得/設定します。

### setRasterizeFormulas {#setRasterizeFormulas-boolean-}
```
public final void setRasterizeFormulas(boolean value)
```

数式をラスタライズできるようにするフラグを取得/設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setRepeat {#setRepeat-boolean-}
```
public final void setRepeat(boolean value)
```

入力 TeX ファイルに参照がある場合など、TeX ジョブを 2 回実行する必要があるかどうかを示すフラグを取得/設定します。一般に、この動作はエンジンが組版プロセス中にデータを収集し、最初の実行時に補助ファイルに保存する場合に有用です。2 回目の実行時にエンジンがそのデータを何らかの形で使用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setRequiredInputDirectory {#setRequiredInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-}
TeX が必要とする入力ディレクトリを取得/設定します。必要な入力とは、メインの .tex ファイルに何らかの形で含まれるファイル（例: 組み込みサポートがないパッケージ）です。

### setShowTerminalOutput {#setShowTerminalOutput-boolean-}
```
public final void setShowTerminalOutput(boolean value)
```

コンソールにターミナル出力を表示するかどうかを示すフラグを取得/設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setSubsetFonts {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```

出力ファイルでフォントをサブセット化するかどうかを示すフラグを取得/設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
