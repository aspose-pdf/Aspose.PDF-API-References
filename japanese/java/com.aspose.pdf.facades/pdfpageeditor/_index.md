---
title: "PdfPageEditor"
linktitle: "PdfPageEditor"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ページの回転、ズーム、位置移動、ページサイズ変更など、PDF ファイルのページを編集するクラスを表します。"
type: docs
weight: 570
url: /ja/java/com.aspose.pdf.facades/pdfpageeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfPageEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfPageEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfPageEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfPageEditor extends SaveableFacade
```

ページの回転、ズーム、位置移動、ページサイズ変更など、PDF ファイルのページを編集するクラスを表します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [BLINDH](#BLINDH) | 垂直ブラインド |
| [BLINDV](#BLINDV) | 垂直ブラインド |
| [BTWIPE](#BTWIPE) | 下から上へのワイプ |
| [DGLITTER](#DGLITTER) | 対角線のきらめき |
| [DISSOLVE](#DISSOLVE) | 古いページが溶けます |
| [INBOX](#INBOX) | 内向きボックス |
| [LRGLITTER](#LRGLITTER) | 左右のきらめき |
| [LRWIPE](#LRWIPE) | 左右ワイプ |
| [OUTBOX](#OUTBOX) | 外向きボックス |
| [RLWIPE](#RLWIPE) | 右から左へのワイプ |
| [SPLITHIN](#SPLITHIN) | IN 水平分割 |
| [SPLITHOUT](#SPLITHOUT) | アウト水平分割 |
| [SPLITVIN](#SPLITVIN) | IN 垂直分割 |
| [SPLITVOUT](#SPLITVOUT) | アウト垂直分割 |
| [TBGLITTER](#TBGLITTER) | 上下のきらめき |
| [TBWIPE](#TBWIPE) | 上下ワイプ |

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfPageEditor](#PdfPageEditor--) | PdfPageEditor クラスのコンストラクタです。 |
| [PdfPageEditor](#PdfPageEditor-com.aspose.pdf.Document-) | PdfPageEditor クラスのコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [applyChanges](#applyChanges--) | ドキュメントページに加えた変更を適用します。 |
| [getAlignment](#getAlignment--) | 結果ページ上の元の PDF コンテンツの水平配置を取得します。デフォルトは AlignmentType.Left です。代わりに getHorizontalAlignment を使用してください。 |
| [getDisplayDuration](#getDisplayDuration--) | ページの表示時間を取得します。 |
| [getHorizontalAlignment](#getHorizontalAlignment--) | 結果ページ上の元の PDF コンテンツの水平配置を取得します。デフォルトは AlignmentType.Left です。 |
| [getPageBoxSize](#getPageBoxSize-int-java.lang.String-) | <p> ドキュメント内の指定されたボックスのサイズを返します。 </p> <hr> <pre> 以下の例は、1 ページ目のメディアボックスを取得する方法を示しています: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); Rectangle rect = editor.getBoxSize(1, "media"); </pre> |
| [getPageRectangle](#getPageRectangle-com.aspose.pdf.Page-) | ページのサイズを返します。 |
| [getPageRotation](#getPageRotation-int-) | <p> 指定されたページの回転角度を返します。 </p> <hr> <pre> 以下の例は、ページの回転角度を取得する方法を示しています: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); int rotation = editor.getPageSize(1); System.out.println("Rotation of 1st page : " + rotation + " degrees"); </pre> |
| [getPageRotations](#getPageRotations--) | <p> ページの回転角度を取得します。ハッシュテーブルにはページ番号と回転角度が含まれ、キーがページ番号を、キーの値が回転角度（度）を表します。 </p> |
| [getPages](#getPages--) | <p> ページ総数を返します。 </p> <hr> <pre> 以下の例は GetPages() メソッドの使用例を示しています: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); System.out.println("Document has: " + editor.GetPages()); </pre> |
| [getPageSize](#getPageSize--) | 出力ファイルのページサイズを取得します。 |
| [getPageSize](#getPageSize-int-) | <p> 指定されたページのページサイズを返します。 </p> <hr> <pre> 以下の例は GetPageSize メソッドの使用方法を示しています: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); PageSize size = editor.getPageSize(1); System.out.println(\"Size of 1st page : \" + size.getWidth() + \" x \" + size.getHeight()); </pre> |
| [getProcessPages](#getProcessPages--) | 編集対象のページ番号を取得します。デフォルトでは、すべてのページが編集されます。 |
| [getRotation](#getRotation--) | ページの回転角度を取得します。回転は 0、90、180、270 のいずれかである必要があります。デフォルト値は 0 です。 |
| [getTransitionDuration](#getTransitionDuration--) | トランジション効果の期間を取得します。 |
| [getTransitionType](#getTransitionType--) | プレゼンテーション中に別のページからこのページへ移動する際に使用するトランジションスタイルを取得します。 |
| [getVerticalAlignment](#getVerticalAlignment--) | 結果ページ上の元の PDF コンテンツの垂直位置揃えを取得します。デフォルトは VerticalAlignmentType.Bottom です。代わりに getVerticalAlignmentType を使用してください |
| [getVerticalAlignmentType](#getVerticalAlignmentType--) | 結果ページ上の元の PDF コンテンツの垂直位置揃えを取得します。デフォルトは VerticalAlignmentType.Bottom です。 |
| [getZoom](#getZoom--) | ズーム係数を取得します。値 1.0 は 100% に相当します。デフォルト値は 1.0 です。 |
| [isBoxDefined](#isBoxDefined-com.aspose.pdf.Page-java.lang.String-) | ページ上にボックスが定義されているか確認します。 |
| [movePosition](#movePosition-float-float-) | <p> 原点を (0, 0) から指定された点へ移動します。原点は左下で、単位はポイント（1 インチ = 72 ポイント）です。 </p> <hr> <pre> PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"input.pdf\"); editor.movePosition(-100, 60); editor.save(\"moved.pdf\"); </pre> |
| [save](#save-java.io.OutputStream-) | <p> 変更されたドキュメントをストリームに保存します。 </p> <hr> <pre> 以下のサンプルは、変更された PDF ドキュメントをストリームに保存する方法を示しています。 PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); editor.setZoom ( 0.5f); editor.save(\"newdocument.pdf\"); </pre> |
| [save](#save-java.lang.String-) | <p> 変更されたドキュメントをファイルに保存します。 </p> <hr> <pre> 以下のサンプルは、変更された PDF ドキュメントを保存する方法を示しています。 PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); editor.setZoom ( 0.5f); editor.save(\"newdocument.pdf\"); </pre> |
| [setAlignment](#setAlignment-com.aspose.pdf.facades.AlignmentType-) | 結果ページ上の元の PDF コンテンツの水平位置揃えを設定します。デフォルトは AlignmentType.Left です。代わりに setHorizontalAlignment を使用してください |
| [setDisplayDuration](#setDisplayDuration-int-) | ページの表示期間を設定します。 |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | 結果ページ上の元の PDF コンテンツの水平位置揃えを設定します。デフォルトは AlignmentType.Left です。 |
| [setPageRotations](#setPageRotations-java.util.Map-) | ページの回転を設定します。ハッシュテーブルにはページ番号と回転角度が含まれ、キーがページ番号を、キーの値が回転角度（度）を表します。 |
| [setPageSize](#setPageSize-com.aspose.pdf.PageSize-) | 出力ファイルのページサイズを設定します。 |
| [setProcessPages](#setProcessPages-int:A-) | 編集対象のページ番号を設定します。デフォルトでは、すべてのページが編集されます。 |
| [setRotation](#setRotation-int-) | ページの回転を設定します。回転は 0、90、180、270 のいずれかである必要があります。デフォルト値は 0 です。 |
| [setTransitionDuration](#setTransitionDuration-int-) | トランジション効果の期間を設定します。 |
| [setTransitionType](#setTransitionType-int-) | プレゼンテーション中に別のページからこのページへ移動する際に使用するトランジションスタイルを設定します。 |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-) | 結果ページ上の元の PDF コンテンツの垂直位置揃えを設定します。デフォルトは VerticalAlignmentType.Bottom です。代わりに setVerticalAlignmentType を使用してください |
| [setVerticalAlignmentType](#setVerticalAlignmentType-com.aspose.pdf.VerticalAlignment-) | 結果ページ上の元の PDF コンテンツの垂直位置揃えを設定します。デフォルトは VerticalAlignmentType.Bottom です。 |
| [setZoom](#setZoom-float-) | <p> ズーム係数を設定します。値 1.0 は 100% に相当します。デフォルト値は 1.0 です。 </p> |

### BLINDH {#BLINDH}
```
public static final int BLINDH
```

垂直ブラインド

### BLINDV {#BLINDV}
```
public static final int BLINDV
```

垂直ブラインド

### BTWIPE {#BTWIPE}
```
public static final int BTWIPE
```

下から上へのワイプ

### DGLITTER {#DGLITTER}
```
public static final int DGLITTER
```

対角線のきらめき

### DISSOLVE {#DISSOLVE}
```
public static final int DISSOLVE
```

古いページが溶けます

### INBOX {#INBOX}
```
public static final int INBOX
```

内向きボックス

### LRGLITTER {#LRGLITTER}
```
public static final int LRGLITTER
```

左右のきらめき

### LRWIPE {#LRWIPE}
```
public static final int LRWIPE
```

左右ワイプ

### OUTBOX {#OUTBOX}
```
public static final int OUTBOX
```

外向きボックス

### RLWIPE {#RLWIPE}
```
public static final int RLWIPE
```

右から左へのワイプ

### SPLITHIN {#SPLITHIN}
```
public static final int SPLITHIN
```

IN 水平分割

### SPLITHOUT {#SPLITHOUT}
```
public static final int SPLITHOUT
```

アウト水平分割

### SPLITVIN {#SPLITVIN}
```
public static final int SPLITVIN
```

IN 垂直分割

### SPLITVOUT {#SPLITVOUT}
```
public static final int SPLITVOUT
```

アウト垂直分割

### TBGLITTER {#TBGLITTER}
```
public static final int TBGLITTER
```

上下のきらめき

### TBWIPE {#TBWIPE}
```
public static final int TBWIPE
```

上下ワイプ

### PdfPageEditor {#PdfPageEditor--}
```
public PdfPageEditor()
```

PdfPageEditor クラスのコンストラクタです。

### PdfPageEditor {#PdfPageEditor-com.aspose.pdf.Document-}
PdfPageEditor クラスのコンストラクタです。

### applyChanges {#applyChanges--}
```
public void applyChanges()
```

ドキュメントページに加えた変更を適用します。

### getAlignment {#getAlignment--}
```
@Deprecated public AlignmentType getAlignment()
```

結果ページ上の元の PDF コンテンツの水平配置を取得します。デフォルトは AlignmentType.Left です。代わりに getHorizontalAlignment を使用してください。

**Returns:**
AlignmentType オブジェクト @see HorizontalAlignment

### getDisplayDuration {#getDisplayDuration--}
```
public int getDisplayDuration()
```

ページの表示時間を取得します。

**Returns:**
int 値です。

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

結果ページ上の元の PDF コンテンツの水平配置を取得します。デフォルトは AlignmentType.Left です。

**Returns:**
HorizontalAlignment 要素 @see HorizontalAlignment

### getPageBoxSize {#getPageBoxSize-int-java.lang.String-}
<p> ドキュメント内の指定されたボックスのサイズを返します。 </p> <hr> <pre> 以下の例は、1 ページ目のメディアボックスを取得する方法を示しています: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); Rectangle rect = editor.getBoxSize(1, "media"); </pre>

### getPageRectangle {#getPageRectangle-com.aspose.pdf.Page-}
ページのサイズを返します。

### getPageRotation {#getPageRotation-int-}
```
public int getPageRotation(int page)
```

<p> 指定されたページの回転角度を返します。 </p> <hr> <pre> 以下の例は、ページの回転角度を取得する方法を示しています: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); int rotation = editor.getPageSize(1); System.out.println("Rotation of 1st page : " + rotation + " degrees"); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ページ |  | ページインデックス。ドキュメントのページは 1 から番号付けされます。 |

**Returns:**
ページの回転角度（度）。

### getPageRotations {#getPageRotations--}
```
public Map < Integer , Integer > getPageRotations()
```

<p> ページの回転角度を取得します。ハッシュテーブルにはページ番号と回転角度が含まれ、キーがページ番号を、キーの値が回転角度（度）を表します。 </p>

**Returns:**
{@code Map<Integer, Integer>} オブジェクト

### getPages {#getPages--}
```
public int getPages()
```

<p> ページ総数を返します。 </p> <hr> <pre> 以下の例は GetPages() メソッドの使用例を示しています: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); System.out.println("Document has: " + editor.GetPages()); </pre>

**Returns:**
ページ数。

### getPageSize {#getPageSize--}
```
public PageSize getPageSize()
```

出力ファイルのページサイズを取得します。

**Returns:**
PageSize オブジェクト

### getPageSize {#getPageSize-int-}
```
public PageSize getPageSize(int page)
```

<p> 指定されたページのページサイズを返します。 </p> <hr> <pre> 以下の例は GetPageSize メソッドの使用方法を示しています: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); PageSize size = editor.getPageSize(1); System.out.println(\"Size of 1st page : \" + size.getWidth() + \" x \" + size.getHeight()); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ページ |  | ページインデックス。ドキュメントのページは 1 から番号付けされます。 |

**Returns:**
Result は PageSize のインスタンスです。返されたオブジェクトの Width と Height プロパティを使用して、ページの幅と高さを取得します。

### getProcessPages {#getProcessPages--}
```
public int[] getProcessPages()
```

編集対象のページ番号を取得します。デフォルトでは、すべてのページが編集されます。

**Returns:**
int 値の配列

### getRotation {#getRotation--}
```
public int getRotation()
```

ページの回転角度を取得します。回転は 0、90、180、270 のいずれかである必要があります。デフォルト値は 0 です。

**Returns:**
int 値です。

### getTransitionDuration {#getTransitionDuration--}
```
public int getTransitionDuration()
```

トランジション効果の期間を取得します。

**Returns:**
int 値です。

### getTransitionType {#getTransitionType--}
```
public int getTransitionType()
```

プレゼンテーション中に別のページからこのページへ移動する際に使用するトランジションスタイルを取得します。

**Returns:**
int 値です。

### getVerticalAlignment {#getVerticalAlignment--}
```
@Deprecated public VerticalAlignmentType getVerticalAlignment()
```

結果ページ上の元の PDF コンテンツの垂直位置揃えを取得します。デフォルトは VerticalAlignmentType.Bottom です。代わりに getVerticalAlignmentType を使用してください

**Returns:**
VerticalAlignmentType オブジェクト

### getVerticalAlignmentType {#getVerticalAlignmentType--}
```
public VerticalAlignment getVerticalAlignmentType()
```

結果ページ上の元の PDF コンテンツの垂直位置揃えを取得します。デフォルトは VerticalAlignmentType.Bottom です。

**Returns:**
VerticalAlignmentType 要素 @see VerticalAlignmentType

### getZoom {#getZoom--}
```
public float getZoom()
```

ズーム係数を取得します。値 1.0 は 100% に相当します。デフォルト値は 1.0 です。

**Returns:**
float 値

### isBoxDefined {#isBoxDefined-com.aspose.pdf.Page-java.lang.String-}
ページ上にボックスが定義されているか確認します。

### movePosition {#movePosition-float-float-}
```
public void movePosition(float moveX, float moveY)
```

<p> 原点を (0, 0) から指定された点へ移動します。原点は左下で、単位はポイント（1 インチ = 72 ポイント）です。 </p> <hr> <pre> PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"input.pdf\"); editor.movePosition(-100, 60); editor.save(\"moved.pdf\"); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| moveX |  | X 座標。 |
| moveY |  | Y 座標。 |

### save {#save-java.io.OutputStream-}
<p> 変更されたドキュメントをストリームに保存します。 </p> <hr> <pre> 以下のサンプルは、変更された PDF ドキュメントをストリームに保存する方法を示しています。 PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); editor.setZoom ( 0.5f); editor.save(\"newdocument.pdf\"); </pre>

### save {#save-java.lang.String-}
<p> 変更されたドキュメントをファイルに保存します。 </p> <hr> <pre> 以下のサンプルは、変更された PDF ドキュメントを保存する方法を示しています。 PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); editor.setZoom ( 0.5f); editor.save(\"newdocument.pdf\"); </pre>

### setAlignment {#setAlignment-com.aspose.pdf.facades.AlignmentType-}
結果ページ上の元の PDF コンテンツの水平位置揃えを設定します。デフォルトは AlignmentType.Left です。代わりに setHorizontalAlignment を使用してください

### setDisplayDuration {#setDisplayDuration-int-}
```
public void setDisplayDuration(int value)
```

ページの表示期間を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
結果ページ上の元の PDF コンテンツの水平位置揃えを設定します。デフォルトは AlignmentType.Left です。

### setPageRotations {#setPageRotations-java.util.Map-}
ページの回転を設定します。ハッシュテーブルにはページ番号と回転角度が含まれ、キーがページ番号を、キーの値が回転角度（度）を表します。

### setPageSize {#setPageSize-com.aspose.pdf.PageSize-}
出力ファイルのページサイズを設定します。

### setProcessPages {#setProcessPages-int:A-}
```
public void setProcessPages(int[] value)
```

編集対象のページ番号を設定します。デフォルトでは、すべてのページが編集されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値の配列 |

### setRotation {#setRotation-int-}
```
public void setRotation(int value)
```

ページの回転を設定します。回転は 0、90、180、270 のいずれかである必要があります。デフォルト値は 0 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setTransitionDuration {#setTransitionDuration-int-}
```
public void setTransitionDuration(int value)
```

トランジション効果の期間を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setTransitionType {#setTransitionType-int-}
```
public void setTransitionType(int value)
```

プレゼンテーション中に別のページからこのページへ移動する際に使用するトランジションスタイルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-}
結果ページ上の元の PDF コンテンツの垂直位置揃えを設定します。デフォルトは VerticalAlignmentType.Bottom です。代わりに setVerticalAlignmentType を使用してください

### setVerticalAlignmentType {#setVerticalAlignmentType-com.aspose.pdf.VerticalAlignment-}
結果ページ上の元の PDF コンテンツの垂直位置揃えを設定します。デフォルトは VerticalAlignmentType.Bottom です。

### setZoom {#setZoom-float-}
```
public void setZoom(float value)
```

<p> ズーム係数を設定します。値 1.0 は 100% に相当します。デフォルト値は 1.0 です。 </p>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float value <hr> <pre> 以下の例は、ドキュメントページのズームを変更する方法を示しています。 PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); </pre> |
