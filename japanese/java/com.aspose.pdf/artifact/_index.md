---
title: "Artifact"
linktitle: "Artifact"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF アーティファクトオブジェクトを表すクラスです。"
type: docs
weight: 190
url: /ja/java/com.aspose.pdf/artifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class Artifact extends Object implements com.aspose.ms.System.IDisposable, Closeable
```

PDF アーティファクトオブジェクトを表すクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Artifact](#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-) | 指定されたタイプとサブタイプを持つアーティファクトのコンストラクタ |
| [Artifact](#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.engine.data.IPdfDictionary-) | このコンストラクタは、ページからアーティファクトが読み取られるときに使用されます。 |
| [Artifact](#Artifact-java.lang.String-java.lang.String-) | 指定されたタイプとサブタイプを持つアーティファクトのコンストラクタ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [beginUpdates](#beginUpdates--) | 削除された更新を開始します。パフォーマンス向上のために同じアーティファクトに対して複数回変更を行う必要がある場合にこの機能を使用します。通常、アーティファクトのプロパティが変更されるたびにアーティファクト演算子が変更され、アーティファクトが変更されるたびにページ内容が変更されます。この影響を回避するには、すべてのアーティファクト更新を StartUpdates/SaveUpdates 呼び出しの間に配置します。これによりページ内容を一度だけ変更できます。Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1); art.beginUpdates(); art.setOpacity ( 0.3f); art.setPosition ( new Point(10,10)); art.setRotation (30); art.saveUpdates(); |
| [close](#close--) | このドキュメントで使用されているすべてのリソースを閉じます。 |
| [dispose](#dispose--) | アーティファクトを破棄します。このメソッドは廃止予定です。代わりに close() を使用してください。 |
| [getArtifactHorizontalAlignment](#getArtifactHorizontalAlignment--) | アーティファクトの水平揃えを取得します。位置が Position プロパティで明示的に指定されている場合、この値は無視されます。 |
| [getArtifactVerticalAlignment](#getArtifactVerticalAlignment--) | アーティファクトの垂直揃えを取得します。位置が Position プロパティで明示的に指定されている場合、この値は無視されます。 |
| [getBottomMargin](#getBottomMargin--) | アーティファクトの下余白を取得します。位置が Position プロパティで明示的に指定されている場合、この値は無視されます。 |
| [getContents](#getContents--) | アーティファクト内部オペレーターのコレクションを取得します。 |
| [getCustomSubtype](#getCustomSubtype--) | アーティファクトのサブタイプ名を取得します。アーティファクトのサブタイプが標準サブタイプでない場合に使用できます。 |
| [getCustomType](#getCustomType--) | アーティファクトのタイプ名を取得します。アーティファクトのタイプが標準でない場合に使用できます。 |
| [getForm](#getForm--) | アーティファクトの XForm を取得します（XForm が使用されている場合）。 |
| [getImage](#getImage--) | アーティファクトの画像を取得します（存在する場合）。 |
| [getLeftMargin](#getLeftMargin--) | アーティファクトの左余白を取得します。位置が Position プロパティで明示的に指定されている場合、この値は無視されます。 |
| [getLines](#getLines--) | 複数行テキストアーティファクトの行。 |
| [getOpacity](#getOpacity--) | アーティファクトの不透明度を取得します。可能な値は 0..1 の範囲です。 |
| [getPosition](#getPosition--) | アーティファクトの位置を取得します。このプロパティが指定されている場合、余白と揃えは無視されます。 |
| [getRectangle](#getRectangle--) | アーティファクトの矩形を取得します。 |
| [getRightMargin](#getRightMargin--) | アーティファクトの右余白を取得します。位置が Position プロパティで明示的に指定されている場合、この値は無視されます。 |
| [getRotation](#getRotation--) | アーティファクトの回転角度を取得します。 |
| [getSubtype](#getSubtype--) | アーティファクトのサブタイプを取得します。アーティファクトが非標準サブタイプを持つ場合、サブタイプ名は CustomSubtype で取得できます。 |
| [getText](#getText--) | アーティファクトのテキストを取得します。 |
| [getTextState](#getTextState--) | アーティファクトテキストのテキスト状態。 |
| [getTopMargin](#getTopMargin--) | アーティファクトの上余白を取得します。位置が Position プロパティで明示的に指定されている場合、この値は無視されます。 |
| [getType](#getType--) | アーティファクトのタイプを取得します。 |
| [getValue](#getValue-java.lang.String-) | アーティファクトのカスタム値を取得します。 |
| [isBackground](#isBackground--) | true の場合、アーティファクトはページ内容の背後に配置されます。 |
| [removeValue](#removeValue-java.lang.String-) | アーティファクトからカスタム値を削除します。 |
| [saveUpdates](#saveUpdates--) | BeginUpdates() 呼び出しの後に行われたアーティファクトのすべての更新を保存します。 |
| [setArtifactHorizontalAlignment](#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | アーティファクトの水平配置を取得します。 |
| [setArtifactVerticalAlignment](#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | アーティファクトの垂直配置を設定します。 |
| [setBackground](#setBackground-boolean-) | true の場合、アーティファクトはページ内容の背後に配置されます。 |
| [setBottomMargin](#setBottomMargin-double-) | アーティファクトの下余白を設定します。 |
| [setCustomSubtype](#setCustomSubtype-java.lang.String-) |  |
| [setCustomType](#setCustomType-java.lang.String-) | アーティファクトタイプの名前を設定します。アーティファクトタイプが標準でない場合に使用できます。 |
| [setImage](#setImage-java.io.InputStream-) | アーティファクトの画像を設定します。 |
| [setImage](#setImage-java.lang.String-) | アーティファクトの画像を設定します。 |
| [setLeftMargin](#setLeftMargin-double-) | アーティファクトの左余白を設定します。位置が明示的に指定されている場合（Position プロパティで）、この値は無視されます。 |
| [setLinesAndState](#setLinesAndState-java.lang.String:A-com.aspose.pdf.TextState-) | アーティファクトのテキストとテキストプロパティを設定します。複数行を指定できます。 |
| [setOpacity](#setOpacity-double-) | アーティファクトの不透明度を設定します。可能な値は 0..1 の範囲です。 |
| [setPageNumberReplacementString](#setPageNumberReplacementString-java.lang.String-) | ページ番号で置き換えられる文字列を設定します。デフォルト値は # です。 |
| [setPdfPage](#setPdfPage-com.aspose.pdf.Page-) | ドキュメントページにアーティファクトとして配置される PDF ページを設定します。 |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | アーティファクトの位置を設定します。 |
| [setRightMargin](#setRightMargin-double-) | アーティファクトの右余白を設定します。 |
| [setRotation](#setRotation-double-) | アーティファクトの回転角度を設定します。 |
| [setSubtype](#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-) | アーティファクトのサブタイプを設定します。 |
| [setText](#setText-com.aspose.pdf.facades.FormattedText-) | アーティファクトのテキストを設定します。 |
| [setText](#setText-java.lang.String-) | アーティファクトのテキストを設定します。 |
| [setTextAndState](#setTextAndState-java.lang.String-com.aspose.pdf.TextState-) | アーティファクトのテキストとテキストプロパティを設定します。 |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | アーティファクトテキストのテキスト状態。 |
| [setTopMargin](#setTopMargin-double-) | アーティファクトの上余白を設定します。 |
| [setType](#setType-com.aspose.pdf.Artifact.ArtifactType-) | アーティファクトのタイプを設定します。 |
| [setValue](#setValue-java.lang.String-java.lang.String-) | アーティファクトのカスタム値を設定します。 |

### Artifact {#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-}
指定されたタイプとサブタイプを持つアーティファクトのコンストラクタ

### Artifact {#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.engine.data.IPdfDictionary-}
このコンストラクタは、ページからアーティファクトが読み取られるときに使用されます。

### Artifact {#Artifact-java.lang.String-java.lang.String-}
指定されたタイプとサブタイプを持つアーティファクトのコンストラクタ

### beginUpdates {#beginUpdates--}
```
public void beginUpdates()
```

削除された更新を開始します。パフォーマンス向上のために同じアーティファクトに対して複数回変更を行う必要がある場合にこの機能を使用します。通常、アーティファクトのプロパティが変更されるたびにアーティファクト演算子が変更され、アーティファクトが変更されるたびにページ内容が変更されます。この影響を回避するには、すべてのアーティファクト更新を StartUpdates/SaveUpdates 呼び出しの間に配置します。これによりページ内容を一度だけ変更できます。Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1); art.beginUpdates(); art.setOpacity ( 0.3f); art.setPosition ( new Point(10,10)); art.setRotation (30); art.saveUpdates();

### close {#close--}
```
public void close()
```

このドキュメントで使用されているすべてのリソースを閉じます。

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

アーティファクトを破棄します。このメソッドは廃止予定です。代わりに close() を使用してください。

### getArtifactHorizontalAlignment {#getArtifactHorizontalAlignment--}
```
public HorizontalAlignment getArtifactHorizontalAlignment()
```

アーティファクトの水平揃えを取得します。位置が Position プロパティで明示的に指定されている場合、この値は無視されます。

**Returns:**
HorizontalAlignment 値 @see HorizontalAlignment

### getArtifactVerticalAlignment {#getArtifactVerticalAlignment--}
```
public VerticalAlignment getArtifactVerticalAlignment()
```

アーティファクトの垂直揃えを取得します。位置が Position プロパティで明示的に指定されている場合、この値は無視されます。

**Returns:**
VerticalAlignment の値です。 @see VerticalAlignment

### getBottomMargin {#getBottomMargin--}
```
public double getBottomMargin()
```

アーティファクトの下余白を取得します。位置が Position プロパティで明示的に指定されている場合、この値は無視されます。

**Returns:**
下余白。

### getContents {#getContents--}
```
public List < Operator > getContents()
```

アーティファクト内部オペレーターのコレクションを取得します。

**Returns:**
アーティファクトの内部演算子を一覧表示します。

### getCustomSubtype {#getCustomSubtype--}
```
public String getCustomSubtype()
```

アーティファクトのサブタイプ名を取得します。アーティファクトのサブタイプが標準サブタイプでない場合に使用できます。

**Returns:**
文字列値

### getCustomType {#getCustomType--}
```
public String getCustomType()
```

アーティファクトのタイプ名を取得します。アーティファクトのタイプが標準でない場合に使用できます。

**Returns:**
文字列アーティファクト名

### getForm {#getForm--}
```
public XForm getForm()
```

アーティファクトの XForm を取得します（XForm が使用されている場合）。

**Returns:**
XForm オブジェクト

### getImage {#getImage--}
```
public XImage getImage()
```

アーティファクトの画像を取得します（存在する場合）。

**Returns:**
XImage オブジェクト

### getLeftMargin {#getLeftMargin--}
```
public double getLeftMargin()
```

アーティファクトの左余白を取得します。位置が Position プロパティで明示的に指定されている場合、この値は無視されます。

**Returns:**
アーティファクトの左余白。

### getLines {#getLines--}
```
public final List < String > getLines()
```

複数行テキストアーティファクトの行。

**Returns:**
文字列のリスト

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

アーティファクトの不透明度を取得します。可能な値は 0..1 の範囲です。

**Returns:**
アーティファクトの不透明度。

### getPosition {#getPosition--}
```
public Point getPosition()
```

アーティファクトの位置を取得します。このプロパティが指定されている場合、余白と揃えは無視されます。

**Returns:**
アーティファクトの位置。

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

アーティファクトの矩形を取得します。

**Returns:**
Rectangle オブジェクト

### getRightMargin {#getRightMargin--}
```
public double getRightMargin()
```

アーティファクトの右余白を取得します。位置が Position プロパティで明示的に指定されている場合、この値は無視されます。

**Returns:**
アーティファクトの右余白。

### getRotation {#getRotation--}
```
public double getRotation()
```

アーティファクトの回転角度を取得します。

**Returns:**
アーティファクトの回転角度。

### getSubtype {#getSubtype--}
```
public Artifact.ArtifactSubtype getSubtype()
```

アーティファクトのサブタイプを取得します。アーティファクトが非標準サブタイプを持つ場合、サブタイプ名は CustomSubtype で取得できます。

**Returns:**
アーティファクトのサブタイプ。 @see ArtifactSubtype

### getText {#getText--}
```
public String getText()
```

アーティファクトのテキストを取得します。

**Returns:**
文字列値

### getTextState {#getTextState--}
```
public final TextState getTextState()
```

アーティファクトテキストのテキスト状態。

**Returns:**
TextState インスタンス

### getTopMargin {#getTopMargin--}
```
public double getTopMargin()
```

アーティファクトの上余白を取得します。位置が Position プロパティで明示的に指定されている場合、この値は無視されます。

**Returns:**
アーティファクトの上余白。

### getType {#getType--}
```
public Artifact.ArtifactType getType()
```

アーティファクトのタイプを取得します。

**Returns:**
アーティファクトタイプの値。 @see ArtifactType

### getValue {#getValue-java.lang.String-}
アーティファクトのカスタム値を取得します。

### isBackground {#isBackground--}
```
public boolean isBackground()
```

true の場合、アーティファクトはページ内容の背後に配置されます。

**Returns:**
ブール値

### removeValue {#removeValue-java.lang.String-}
アーティファクトからカスタム値を削除します。

### saveUpdates {#saveUpdates--}
```
public void saveUpdates()
```

BeginUpdates() 呼び出しの後に行われたアーティファクトのすべての更新を保存します。

### setArtifactHorizontalAlignment {#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
アーティファクトの水平配置を取得します。

### setArtifactVerticalAlignment {#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
アーティファクトの垂直配置を設定します。

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

true の場合、アーティファクトはページ内容の背後に配置されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setBottomMargin {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```

アーティファクトの下余白を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 下余白。 |

### setCustomSubtype {#setCustomSubtype-java.lang.String-}


### setCustomType {#setCustomType-java.lang.String-}
アーティファクトタイプの名前を設定します。アーティファクトタイプが標準でない場合に使用できます。

### setImage {#setImage-java.io.InputStream-}
アーティファクトの画像を設定します。

### setImage {#setImage-java.lang.String-}
アーティファクトの画像を設定します。

### setLeftMargin {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```

アーティファクトの左余白を設定します。位置が明示的に指定されている場合（Position プロパティで）、この値は無視されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | アーティファクトの左余白。 |

### setLinesAndState {#setLinesAndState-java.lang.String:A-com.aspose.pdf.TextState-}
アーティファクトのテキストとテキストプロパティを設定します。複数行を指定できます。

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

アーティファクトの不透明度を設定します。可能な値は 0..1 の範囲です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | アーティファクトの不透明度。 |

### setPageNumberReplacementString {#setPageNumberReplacementString-java.lang.String-}
ページ番号で置き換えられる文字列を設定します。デフォルト値は # です。

### setPdfPage {#setPdfPage-com.aspose.pdf.Page-}
ドキュメントページにアーティファクトとして配置される PDF ページを設定します。

### setPosition {#setPosition-com.aspose.pdf.Point-}
アーティファクトの位置を設定します。

### setRightMargin {#setRightMargin-double-}
```
public void setRightMargin(double value)
```

アーティファクトの右余白を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | アーティファクトの右余白。 |

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

アーティファクトの回転角度を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | アーティファクトの回転角度。 |

### setSubtype {#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-}
アーティファクトのサブタイプを設定します。

### setText {#setText-com.aspose.pdf.facades.FormattedText-}
アーティファクトのテキストを設定します。

### setText {#setText-java.lang.String-}
アーティファクトのテキストを設定します。

### setTextAndState {#setTextAndState-java.lang.String-com.aspose.pdf.TextState-}
アーティファクトのテキストとテキストプロパティを設定します。

### setTextState {#setTextState-com.aspose.pdf.TextState-}
アーティファクトテキストのテキスト状態。

### setTopMargin {#setTopMargin-double-}
```
public void setTopMargin(double value)
```

アーティファクトの上余白を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | アーティファクトの上余白。 |

### setType {#setType-com.aspose.pdf.Artifact.ArtifactType-}
アーティファクトのタイプを設定します。

### setValue {#setValue-java.lang.String-java.lang.String-}
アーティファクトのカスタム値を設定します。
