---
title: "DocumentPrivilege"
linktitle: "DocumentPrivilege"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "Pdf ファイルへのアクセス権限を表します。{@code PdfFileSecurity} を参照してください。このクラスの使用方法は 4 つあります: 1. 事前定義された権限を直接使用する。 2. 基づく。"
type: docs
weight: 110
url: /ja/java/com.aspose.pdf.facades/documentprivilege/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.DocumentPrivilege

**All Implemented Interfaces:**
Comparable < Object >

```
public final class DocumentPrivilege extends Object implements Comparable < Object >
```

Pdf ファイルへのアクセス権限を表します。 {@code PdfFileSecurity} を参照してください。このクラスの使用方法は 4 つあります: 1. 事前定義された権限を直接使用する。 2. 事前定義された権限を基にして特定の権限を変更する。 3. 事前定義された権限を基にして特定の Adobe Professional 権限の組み合わせを変更する。 4. 方法 2 と方法 3 を組み合わせる。 //Way1: Using predefined privilege directly. DocumentPrivilege privilege = DocumentPrivilege.getPrint(); //Way2: Based on a predefined privilege and change some specifical permissions. DocumentPrivilege privilege = DocumentPrivilege.getAllowAll(); privilege.setAllowPrint(false); privilege.setAllowModifyContents(false); //Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination. DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setPrintAllowLevel(2); //Way4: Mixes the way2 and way3 DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setAllowPrint(true);

## メソッド

| メソッド | 説明 |
| --- | --- |
| [compareTo](#compareTo-java.lang.Object-) | 2 つの {@code DocumentPrivilege} オブジェクトを比較します。 |
| [equals](#equals-java.lang.Object-) | このオブジェクトが他のオブジェクトと「等しい」かどうかを示します。 <p> <code>equals</code> メソッドは、null でないオブジェクト参照に対して同値関係を実装します: <ul> <li>それは <i>反射的</i> です: 任意の null でない参照値 <code>x</code> に対し、<code>x.equals(x)</code> は <code>true</code> を返すべきです。 <li>それは <i>対称的</i> です: 任意の null でない参照値 <code>x</code> と <code>y</code> に対し、<code>x.equals(y)</code> が <code>true</code> を返すのは、かつ <code>y.equals(x)</code> が <code>true</code> を返す場合に限ります。 <li>それは <i>推移的</i> です: 任意の null でない参照値 <code>x</code>、<code>y</code>、<code>z</code> に対し、<code>x.equals(y)</code> が <code>true</code> でかつ <code>y.equals(z)</code> が <code>true</code> のとき、<code>x.equals(z)</code> は <code>true</code> を返すべきです。 <li>それは <i>一貫性</i> です: 任意の null でない参照値 <code>x</code> と <code>y</code> に対し、<tt>x.equals(y)</tt> の呼び出しを複数回行っても、オブジェクトの <code>equals</code> 比較に使用される情報が変更されていない限り、常に <code>true</code> か常に <code>false</code> を返します。 <li>任意の null でない参照値 <code>x</code> に対し、<code>x.equals(null)</code> は <code>false</code> を返すべきです。 </ul> <p> クラス <code>Object</code> の <tt>equals</tt> メソッドは、オブジェクトに対して可能な限り最も厳格な同値関係を実装します。つまり、任意の null でない参照値 <code>x</code> と <code>y</code> に対し、このメソッドは <code>true</code> を返すのは、<code>x</code> と <code>y</code> が同一オブジェクトを参照している場合 (<code>x == y</code> が <code>true</code> である) に限ります。 <p> なお、一般にこのメソッドをオーバーライドする場合は、<tt>hashCode</tt> メソッドもオーバーライドして、等価オブジェクトが同じハッシュコードを持つという一般契約を維持する必要があります。 |
| [getAllowAll](#getAllowAll--) | すべて許可されています。 |
| [getAssembly](#getAssembly--) | ファイルのアセンブリを許可します。 |
| [getChangeAllowLevel](#getChangeAllowLevel--) | ドキュメントの権限の変更レベルを取得および設定します。Adobe Professional の「Changes Allowed」設定と同様です。0: なし。1: ページの挿入、削除、回転。2: フォームフィールドへの入力と既存の署名フィールドへの署名。3: コメント、フォームフィールドへの入力、既存の署名フィールドへの署名。4: ページの抽出を除くすべて。プロパティの値が -1 の場合、レベルは未定義です。 |
| [getCopy](#getCopy--) | ファイルのコピーを許可します。 |
| [getCopyAllowLevel](#getCopyAllowLevel--) | ドキュメントの権限のコピー レベルを取得および設定します。Adobe Professional の権限設定と同様です。0: なし。1: 視覚障害者向けのスクリーンリーダーデバイスでテキストにアクセスできるようにする。2: テキスト、画像、その他のコンテンツのコピーを許可する。プロパティの値が -1 の場合、レベルは未定義です。 |
| [getDegradedPrinting](#getDegradedPrinting--) | 低品質印刷を許可します。 |
| [getFillIn](#getFillIn--) | ファイル内のフォームへの入力を許可します。 |
| [getForbidAll](#getForbidAll--) | すべて禁止されています。 |
| [getModifyAnnotations](#getModifyAnnotations--) | ファイルの注釈の変更を許可します。 |
| [getModifyContents](#getModifyContents--) | ファイルの変更を許可します。 |
| [getPrint](#getPrint--) | ファイルの印刷を許可します。 |
| [getPrintAllowLevel](#getPrintAllowLevel--) | ドキュメントの権限の印刷レベルを取得および設定します。Adobe Professional の「Printing Allowed」設定と同様です。0: なし。1: 低解像度 (150 dpi)。2: 高解像度。プロパティの値が -1 の場合、レベルは未定義です。 |
| [getScreenReaders](#getScreenReaders--) | 画面上でのみ閲覧を許可します。 |
| [getValue](#getValue--) |  |
| [hashCode](#hashCode--) | オブジェクトのハッシュコード値を返します。このメソッドは、<code>java.util.Hashtable</code> などが提供するハッシュテーブルのためにサポートされています。<p> <code>hashCode</code> の一般的な契約は次のとおりです: <ul> <li>Java アプリケーションの実行中に同じオブジェクトに対して複数回呼び出された場合、<tt>hashCode</tt> メソッドは、オブジェクトの <tt>equals</tt> 比較に使用される情報が変更されていない限り、常に同じ整数を返さなければなりません。この整数は、ある実行から別の実行へは一貫している必要はありません。<li>2 つのオブジェクトが <tt>equals(Object)</tt> メソッドによって等しいと判断される場合、両方のオブジェクトで <code>hashCode</code> メソッドを呼び出すと同じ整数結果が得られなければなりません。<li>オブジェクトが {@link java.lang.Object#equals(java.lang.Object)} メソッドによって等しくない場合でも、<tt>hashCode</tt> メソッドが各オブジェクトで異なる整数結果を返す必要は<em>ありません</em>。ただし、等しくないオブジェクトに対して異なる整数結果を生成すると、ハッシュテーブルのパフォーマンスが向上する可能性があります。 </ul> <p> 実用的に可能な限り、クラス <tt>Object</tt> によって定義された hashCode メソッドは、異なるオブジェクトに対して異なる整数を返します。（これは通常、オブジェクトの内部アドレスを整数に変換することで実装されますが、この実装手法は Java<span style=\"font-size:70%\"><sup>TM</sup></span> プログラミング言語で必須ではありません。） |
| [isAllowAssembly](#isAllowAssembly--) | アセンブリを許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [isAllowCopy](#isAllowCopy--) | コピーを許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [isAllowDegradedPrinting](#isAllowDegradedPrinting--) | 低品質印刷を許可するかどうかの権限を設定します。true は許可、false は禁止です。設定された場合、印刷は外観の低レベル表現に制限され、品質が低下する可能性があります。 |
| [isAllowFillIn](#isAllowFillIn--) | フォームへの入力を許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [isAllowModifyAnnotations](#isAllowModifyAnnotations--) | 注釈の変更を許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [isAllowModifyContents](#isAllowModifyContents--) | コンテンツの変更を許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [isAllowPrint](#isAllowPrint--) | 印刷を許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [isAllowScreenReaders](#isAllowScreenReaders--) | スクリーンリーダーを許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [setAllowAssembly](#setAllowAssembly-boolean-) | アセンブリを許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [setAllowCopy](#setAllowCopy-boolean-) | コピーを許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [setAllowDegradedPrinting](#setAllowDegradedPrinting-boolean-) | 低品質印刷を許可するかどうかの権限を設定します。true は許可、false は禁止です。設定された場合、印刷は外観の低レベル表現に制限され、品質が低下する可能性があります。 |
| [setAllowFillIn](#setAllowFillIn-boolean-) | フォームへの入力を許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [setAllowModifyAnnotations](#setAllowModifyAnnotations-boolean-) | 注釈の変更を許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [setAllowModifyContents](#setAllowModifyContents-boolean-) | コンテンツの変更を許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [setAllowPrint](#setAllowPrint-boolean-) | 印刷を許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [setAllowScreenReaders](#setAllowScreenReaders-boolean-) | スクリーンリーダーを許可するかどうかの権限を設定します。true は許可、false は禁止です。 |
| [setChangeAllowLevel](#setChangeAllowLevel-int-) | ドキュメントの権限の変更レベルを取得および設定します。Adobe Professional の「Changes Allowed」設定と同様です。0: なし。1: ページの挿入、削除、回転。2: フォームフィールドへの入力と既存の署名フィールドへの署名。3: コメント、フォームフィールドへの入力、既存の署名フィールドへの署名。4: ページの抽出を除くすべて。プロパティの値が -1 の場合、レベルは未定義です。 |
| [setCopyAllowLevel](#setCopyAllowLevel-int-) | ドキュメントの権限のコピー レベルを取得および設定します。Adobe Professional の権限設定と同様です。0: なし。1: 視覚障害者向けのスクリーンリーダーデバイスでテキストにアクセスできるようにする。2: テキスト、画像、その他のコンテンツのコピーを許可する。プロパティの値が -1 の場合、レベルは未定義です。 |
| [setPrintAllowLevel](#setPrintAllowLevel-int-) | ドキュメントの権限の印刷レベルを取得および設定します。Adobe Professional の「Printing Allowed」設定と同様です。0: なし。1: 低解像度 (150 dpi)。2: 高解像度。プロパティの値が -1 の場合、レベルは未定義です。 |

### compareTo {#compareTo-java.lang.Object-}
2 つの {@code DocumentPrivilege} オブジェクトを比較します。

### equals {#equals-java.lang.Object-}
このオブジェクトが他のオブジェクトと「等しい」かどうかを示します。 <p> <code>equals</code> メソッドは、null でないオブジェクト参照に対して同値関係を実装します: <ul> <li>それは <i>反射的</i> です: 任意の null でない参照値 <code>x</code> に対し、<code>x.equals(x)</code> は <code>true</code> を返すべきです。 <li>それは <i>対称的</i> です: 任意の null でない参照値 <code>x</code> と <code>y</code> に対し、<code>x.equals(y)</code> が <code>true</code> を返すのは、かつ <code>y.equals(x)</code> が <code>true</code> を返す場合に限ります。 <li>それは <i>推移的</i> です: 任意の null でない参照値 <code>x</code>、<code>y</code>、<code>z</code> に対し、<code>x.equals(y)</code> が <code>true</code> でかつ <code>y.equals(z)</code> が <code>true</code> のとき、<code>x.equals(z)</code> は <code>true</code> を返すべきです。 <li>それは <i>一貫性</i> です: 任意の null でない参照値 <code>x</code> と <code>y</code> に対し、<tt>x.equals(y)</tt> の呼び出しを複数回行っても、オブジェクトの <code>equals</code> 比較に使用される情報が変更されていない限り、常に <code>true</code> か常に <code>false</code> を返します。 <li>任意の null でない参照値 <code>x</code> に対し、<code>x.equals(null)</code> は <code>false</code> を返すべきです。 </ul> <p> クラス <code>Object</code> の <tt>equals</tt> メソッドは、オブジェクトに対して可能な限り最も厳格な同値関係を実装します。つまり、任意の null でない参照値 <code>x</code> と <code>y</code> に対し、このメソッドは <code>true</code> を返すのは、<code>x</code> と <code>y</code> が同一オブジェクトを参照している場合 (<code>x == y</code> が <code>true</code> である) に限ります。 <p> なお、一般にこのメソッドをオーバーライドする場合は、<tt>hashCode</tt> メソッドもオーバーライドして、等価オブジェクトが同じハッシュコードを持つという一般契約を維持する必要があります。

### getAllowAll {#getAllowAll--}
```
public static DocumentPrivilege getAllowAll()
```

すべて許可されています。

**Returns:**
DocumentPrivilege 要素

### getAssembly {#getAssembly--}
```
public static DocumentPrivilege getAssembly()
```

ファイルのアセンブリを許可します。

**Returns:**
DocumentPrivilege 要素

### getChangeAllowLevel {#getChangeAllowLevel--}
```
public final int getChangeAllowLevel()
```

ドキュメントの権限の変更レベルを取得および設定します。Adobe Professional の「Changes Allowed」設定と同様です。0: なし。1: ページの挿入、削除、回転。2: フォームフィールドへの入力と既存の署名フィールドへの署名。3: コメント、フォームフィールドへの入力、既存の署名フィールドへの署名。4: ページの抽出を除くすべて。プロパティの値が -1 の場合、レベルは未定義です。

**Returns:**
int 値です。

### getCopy {#getCopy--}
```
public static DocumentPrivilege getCopy()
```

ファイルのコピーを許可します。

**Returns:**
DocumentPrivilege 要素

### getCopyAllowLevel {#getCopyAllowLevel--}
```
public final int getCopyAllowLevel()
```

ドキュメントの権限のコピー レベルを取得および設定します。Adobe Professional の権限設定と同様です。0: なし。1: 視覚障害者向けのスクリーンリーダーデバイスでテキストにアクセスできるようにする。2: テキスト、画像、その他のコンテンツのコピーを許可する。プロパティの値が -1 の場合、レベルは未定義です。

**Returns:**
int 値です。

### getDegradedPrinting {#getDegradedPrinting--}
```
public static DocumentPrivilege getDegradedPrinting()
```

低品質印刷を許可します。

**Returns:**
DocumentPrivilege 要素

### getFillIn {#getFillIn--}
```
public static DocumentPrivilege getFillIn()
```

ファイル内のフォームへの入力を許可します。

**Returns:**
DocumentPrivilege 要素

### getForbidAll {#getForbidAll--}
```
public static DocumentPrivilege getForbidAll()
```

すべて禁止されています。

**Returns:**
DocumentPrivilege 要素

### getModifyAnnotations {#getModifyAnnotations--}
```
public static DocumentPrivilege getModifyAnnotations()
```

ファイルの注釈の変更を許可します。

**Returns:**
DocumentPrivilege 要素

### getModifyContents {#getModifyContents--}
```
public static DocumentPrivilege getModifyContents()
```

ファイルの変更を許可します。

**Returns:**
DocumentPrivilege 要素

### getPrint {#getPrint--}
```
public static DocumentPrivilege getPrint()
```

ファイルの印刷を許可します。

**Returns:**
DocumentPrivilege 要素

### getPrintAllowLevel {#getPrintAllowLevel--}
```
public final int getPrintAllowLevel()
```

ドキュメントの権限の印刷レベルを取得および設定します。Adobe Professional の「Printing Allowed」設定と同様です。0: なし。1: 低解像度 (150 dpi)。2: 高解像度。プロパティの値が -1 の場合、レベルは未定義です。

**Returns:**
int 値です。

### getScreenReaders {#getScreenReaders--}
```
public static DocumentPrivilege getScreenReaders()
```

画面上でのみ閲覧を許可します。

**Returns:**
DocumentPrivilege 要素

### getValue {#getValue--}
```
public final int getValue()
```



### hashCode {#hashCode--}
```
public int hashCode()
```

オブジェクトのハッシュコード値を返します。このメソッドは、<code>java.util.Hashtable</code> などが提供するハッシュテーブルのためにサポートされています。<p> <code>hashCode</code> の一般的な契約は次のとおりです: <ul> <li>Java アプリケーションの実行中に同じオブジェクトに対して複数回呼び出された場合、<tt>hashCode</tt> メソッドは、オブジェクトの <tt>equals</tt> 比較に使用される情報が変更されていない限り、常に同じ整数を返さなければなりません。この整数は、ある実行から別の実行へは一貫している必要はありません。<li>2 つのオブジェクトが <tt>equals(Object)</tt> メソッドによって等しいと判断される場合、両方のオブジェクトで <code>hashCode</code> メソッドを呼び出すと同じ整数結果が得られなければなりません。<li>オブジェクトが {@link java.lang.Object#equals(java.lang.Object)} メソッドによって等しくない場合でも、<tt>hashCode</tt> メソッドが各オブジェクトで異なる整数結果を返す必要は<em>ありません</em>。ただし、等しくないオブジェクトに対して異なる整数結果を生成すると、ハッシュテーブルのパフォーマンスが向上する可能性があります。 </ul> <p> 実用的に可能な限り、クラス <tt>Object</tt> によって定義された hashCode メソッドは、異なるオブジェクトに対して異なる整数を返します。（これは通常、オブジェクトの内部アドレスを整数に変換することで実装されますが、この実装手法は Java<span style=\"font-size:70%\"><sup>TM</sup></span> プログラミング言語で必須ではありません。）

**Returns:**
このオブジェクトのハッシュコード値。@see java.lang.Object#equals(java.lang.Object) @see java.util.Hashtable

### isAllowAssembly {#isAllowAssembly--}
```
public boolean isAllowAssembly()
```

アセンブリを許可するかどうかの権限を設定します。true は許可、false は禁止です。

**Returns:**
ブール値

### isAllowCopy {#isAllowCopy--}
```
public boolean isAllowCopy()
```

コピーを許可するかどうかの権限を設定します。true は許可、false は禁止です。

**Returns:**
ブール値

### isAllowDegradedPrinting {#isAllowDegradedPrinting--}
```
public boolean isAllowDegradedPrinting()
```

低品質印刷を許可するかどうかの権限を設定します。true は許可、false は禁止です。設定された場合、印刷は外観の低レベル表現に制限され、品質が低下する可能性があります。

**Returns:**
ブール値

### isAllowFillIn {#isAllowFillIn--}
```
public boolean isAllowFillIn()
```

フォームへの入力を許可するかどうかの権限を設定します。true は許可、false は禁止です。

**Returns:**
ブール値

### isAllowModifyAnnotations {#isAllowModifyAnnotations--}
```
public boolean isAllowModifyAnnotations()
```

注釈の変更を許可するかどうかの権限を設定します。true は許可、false は禁止です。

**Returns:**
ブール値

### isAllowModifyContents {#isAllowModifyContents--}
```
public boolean isAllowModifyContents()
```

コンテンツの変更を許可するかどうかの権限を設定します。true は許可、false は禁止です。

**Returns:**
ブール値

### isAllowPrint {#isAllowPrint--}
```
public boolean isAllowPrint()
```

印刷を許可するかどうかの権限を設定します。true は許可、false は禁止です。

**Returns:**
ブール値

### isAllowScreenReaders {#isAllowScreenReaders--}
```
public boolean isAllowScreenReaders()
```

スクリーンリーダーを許可するかどうかの権限を設定します。true は許可、false は禁止です。

**Returns:**
ブール値

### setAllowAssembly {#setAllowAssembly-boolean-}
```
public void setAllowAssembly(boolean value)
```

アセンブリを許可するかどうかの権限を設定します。true は許可、false は禁止です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setAllowCopy {#setAllowCopy-boolean-}
```
public void setAllowCopy(boolean value)
```

コピーを許可するかどうかの権限を設定します。true は許可、false は禁止です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setAllowDegradedPrinting {#setAllowDegradedPrinting-boolean-}
```
public void setAllowDegradedPrinting(boolean value)
```

低品質印刷を許可するかどうかの権限を設定します。true は許可、false は禁止です。設定された場合、印刷は外観の低レベル表現に制限され、品質が低下する可能性があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setAllowFillIn {#setAllowFillIn-boolean-}
```
public void setAllowFillIn(boolean value)
```

フォームへの入力を許可するかどうかの権限を設定します。true は許可、false は禁止です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setAllowModifyAnnotations {#setAllowModifyAnnotations-boolean-}
```
public void setAllowModifyAnnotations(boolean value)
```

注釈の変更を許可するかどうかの権限を設定します。true は許可、false は禁止です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setAllowModifyContents {#setAllowModifyContents-boolean-}
```
public void setAllowModifyContents(boolean value)
```

コンテンツの変更を許可するかどうかの権限を設定します。true は許可、false は禁止です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setAllowPrint {#setAllowPrint-boolean-}
```
public void setAllowPrint(boolean value)
```

印刷を許可するかどうかの権限を設定します。true は許可、false は禁止です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setAllowScreenReaders {#setAllowScreenReaders-boolean-}
```
public void setAllowScreenReaders(boolean value)
```

スクリーンリーダーを許可するかどうかの権限を設定します。true は許可、false は禁止です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setChangeAllowLevel {#setChangeAllowLevel-int-}
```
public void setChangeAllowLevel(int value)
```

ドキュメントの権限の変更レベルを取得および設定します。Adobe Professional の「Changes Allowed」設定と同様です。0: なし。1: ページの挿入、削除、回転。2: フォームフィールドへの入力と既存の署名フィールドへの署名。3: コメント、フォームフィールドへの入力、既存の署名フィールドへの署名。4: ページの抽出を除くすべて。プロパティの値が -1 の場合、レベルは未定義です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setCopyAllowLevel {#setCopyAllowLevel-int-}
```
public void setCopyAllowLevel(int value)
```

ドキュメントの権限のコピー レベルを取得および設定します。Adobe Professional の権限設定と同様です。0: なし。1: 視覚障害者向けのスクリーンリーダーデバイスでテキストにアクセスできるようにする。2: テキスト、画像、その他のコンテンツのコピーを許可する。プロパティの値が -1 の場合、レベルは未定義です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setPrintAllowLevel {#setPrintAllowLevel-int-}
```
public void setPrintAllowLevel(int value)
```

ドキュメントの権限の印刷レベルを取得および設定します。Adobe Professional の「Printing Allowed」設定と同様です。0: なし。1: 低解像度 (150 dpi)。2: 高解像度。プロパティの値が -1 の場合、レベルは未定義です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |
