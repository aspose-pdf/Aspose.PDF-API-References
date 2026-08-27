---
title: "DocumentPrivilege"
linktitle: "DocumentPrivilege"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt die Berechtigungen für den Zugriff auf eine PDF-Datei dar. Siehe {@code PdfFileSecurity}. Es gibt 4 Möglichkeiten, diese Klasse zu verwenden: 1. Direkt vordefinierte Berechtigung verwenden. 2. Basierend auf einer."
type: docs
weight: 110
url: /de/java/com.aspose.pdf.facades/documentprivilege/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.DocumentPrivilege

**All Implemented Interfaces:**
Comparable < Object >

```
public final class DocumentPrivilege extends Object implements Comparable < Object >
```

Stellt die Berechtigungen für den Zugriff auf eine PDF-Datei dar. Siehe {@code PdfFileSecurity}. Es gibt 4 Möglichkeiten, diese Klasse zu verwenden: 1. Eine vordefinierte Berechtigung direkt verwenden. 2. Auf einer vordefinierten Berechtigung basieren und einige spezifische Berechtigungen ändern. 3. Auf einer vordefinierten Berechtigung basieren und eine spezifische Kombination von Adobe‑Professional‑Berechtigungen ändern. 4. Die Wege 2 und 3 kombinieren. //Way1: Using predefined privilege directly. DocumentPrivilege privilege = DocumentPrivilege.getPrint(); //Way2: Based on a predefined privilege and change some specifical permissions. DocumentPrivilege privilege = DocumentPrivilege.getAllowAll(); privilege.setAllowPrint(false); privilege.setAllowModifyContents(false); //Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination. DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setPrintAllowLevel(2); //Way4: Mixes the way2 and way3 DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setAllowPrint(true);

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [compareTo](#compareTo-java.lang.Object-) | Vergleicht zwei {@code DocumentPrivilege}-Objekte. |
| [equals](#equals-java.lang.Object-) | Gibt an, ob ein anderes Objekt diesem "gleich" ist. <p> Die <code>equals</code>-Methode implementiert eine Äquivalenzrelation für nicht‑null Objekt‑Referenzen: <ul> <li>Sie ist <i>reflexiv</i>: Für jeden nicht‑null Referenzwert <code>x</code> sollte <code>x.equals(x)</code> <code>true</code> zurückgeben. <li>Sie ist <i>symmetrisch</i>: Für beliebige nicht‑null Referenzwerte <code>x</code> und <code>y</code> sollte <code>x.equals(y)</code> <code>true</code> zurückgeben, genau dann wenn <code>y.equals(x)</code> <code>true</code> zurückgibt. <li>Sie ist <i>transitiv</i>: Für beliebige nicht‑null Referenzwerte <code>x</code>, <code>y</code> und <code>z</code> sollte, wenn <code>x.equals(y)</code> <code>true</code> und <code>y.equals(z)</code> <code>true</code> zurückgeben, auch <code>x.equals(z)</code> <code>true</code> zurückgeben. <li>Sie ist <i>konsistent</i>: Für beliebige nicht‑null Referenzwerte <code>x</code> und <code>y</code> geben mehrere Aufrufe von <tt>x.equals(y)</tt> stets <code>true</code> oder stets <code>false</code> zurück, vorausgesetzt, dass keine Informationen, die in <code>equals</code>-Vergleichen verwendet werden, verändert wurden. <li>Für jeden nicht‑null Referenzwert <code>x</code> sollte <code>x.equals(null)</code> <code>false</code> zurückgeben. </ul> <p> Die <tt>equals</tt>-Methode für die Klasse <code>Object</code> implementiert die strengste mögliche Äquivalenzrelation für Objekte; das heißt, für beliebige nicht‑null Referenzwerte <code>x</code> und <code>y</code> gibt diese Methode <code>true</code> zurück, genau dann wenn <code>x</code> und <code>y</code> auf dasselbe Objekt verweisen (<code>x == y</code> hat den Wert <code>true</code>). <p> Hinweis: Es ist im Allgemeinen notwendig, die <tt>hashCode</tt>-Methode zu überschreiben, wann immer diese Methode überschrieben wird, um den allgemeinen Vertrag für die <tt>hashCode</tt>-Methode einzuhalten, der besagt, dass gleiche Objekte gleiche Hash‑Codes besitzen. |
| [getAllowAll](#getAllowAll--) | Alle erlaubt. |
| [getAssembly](#getAssembly--) | Erlaubt das Assemblieren der Datei. |
| [getChangeAllowLevel](#getChangeAllowLevel--) | Liest und setzt die Änderungsstufe der Dokumenten‑Berechtigung. Entspricht den "Changes Allowed"-Einstellungen von Adobe Professional. 0: Keine. 1: Einfügen, Löschen und Drehen von Seiten. 2: Ausfüllen von Formularfeldern und Signieren vorhandener Signaturfelder. 3: Kommentieren, Ausfüllen von Formularfeldern und Signieren vorhandener Signaturfelder. 4: Alles außer dem Extrahieren von Seiten. Hat die Eigenschaft den Wert -1, ist die Stufe undefiniert. |
| [getCopy](#getCopy--) | Erlaubt das Kopieren der Datei. |
| [getCopyAllowLevel](#getCopyAllowLevel--) | Liest und setzt die Kopierstufe der Dokumenten‑Berechtigung. Entspricht den Berechtigungseinstellungen von Adobe Professional. 0: Keine. 1: Textzugriff für Screen‑Reader‑Geräte für sehbehinderte Personen aktivieren. 2: Kopieren von Text, Bildern und anderem Inhalt aktivieren. Hat die Eigenschaft den Wert -1, ist die Stufe undefiniert. |
| [getDegradedPrinting](#getDegradedPrinting--) | Erlaubt das Drucken in reduzierter Qualität. |
| [getFillIn](#getFillIn--) | Erlaubt das Ausfüllen von Formularen in der Datei. |
| [getForbidAll](#getForbidAll--) | Alles verboten. |
| [getModifyAnnotations](#getModifyAnnotations--) | Erlaubt das Ändern von Anmerkungen der Datei. |
| [getModifyContents](#getModifyContents--) | Erlaubt das Ändern der Datei. |
| [getPrint](#getPrint--) | Erlaubt das Drucken der Datei. |
| [getPrintAllowLevel](#getPrintAllowLevel--) | Liest und setzt die Druckstufe der Dokumentenprivilegien. Entspricht den Druck‑Erlaubt‑Einstellungen von Adobe Professional. 0: Keine. 1: Niedrige Auflösung (150 dpi). 2: Hohe Auflösung. Hat die Eigenschaft den Wert -1, ist die Stufe undefiniert. |
| [getScreenReaders](#getScreenReaders--) | Erlaubt das Lesen nur auf dem Bildschirm. |
| [getValue](#getValue--) |  |
| [hashCode](#hashCode--) | Gibt einen Hashcode‑Wert für das Objekt zurück. Diese Methode wird zum Nutzen von Hashtabellen bereitgestellt, wie sie z. B. von <code>java.util.Hashtable</code> bereitgestellt werden. <p> Der allgemeine Vertrag von <code>hashCode</code> lautet: <ul> <li>Immer wenn sie während der Ausführung einer Java‑Anwendung mehrmals auf demselben Objekt aufgerufen wird, muss die <tt>hashCode</tt>-Methode konsistent denselben Integer zurückgeben, vorausgesetzt, es werden keine Informationen geändert, die in <tt>equals</tt>-Vergleichen des Objekts verwendet werden. Dieser Integer muss nicht von einer Programmausführung zur nächsten konsistent bleiben. <li>Wenn zwei Objekte gemäß der <tt>equals(Object)</tt>-Methode gleich sind, muss der Aufruf der <code>hashCode</code>-Methode auf beiden Objekten dasselbe Integer‑Ergebnis liefern. <li>Es ist <em>nicht</em> erforderlich, dass bei ungleichen Objekten gemäß der {@link java.lang.Object#equals(java.lang.Object)}‑Methode der Aufruf der <tt>hashCode</tt>-Methode auf beiden Objekten unterschiedliche Integer‑Ergebnisse liefert. Der Programmierer sollte jedoch beachten, dass unterschiedliche Integer‑Ergebnisse für ungleiche Objekte die Leistung von Hashtabellen verbessern können. </ul> <p> Soweit praktisch möglich, liefert die von der Klasse <tt>Object</tt> definierte hashCode‑Methode unterschiedliche Integer für unterschiedliche Objekte. (Dies wird typischerweise dadurch umgesetzt, dass die interne Adresse des Objekts in einen Integer umgewandelt wird, aber diese Implementierungstechnik ist nicht durch die Java<span style="font-size:70%"><sup>TM</sup></span>-Programmiersprache vorgeschrieben.) |
| [isAllowAssembly](#isAllowAssembly--) | Setzt die Berechtigung, die das Zusammenfügen erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten. |
| [isAllowCopy](#isAllowCopy--) | Setzt die Berechtigung, die das Kopieren erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten. |
| [isAllowDegradedPrinting](#isAllowDegradedPrinting--) | Setzt die Berechtigung, die das degradierte Drucken erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten. Wenn gesetzt, wird der Druck auf eine niedrigstufige Darstellung des Erscheinungsbildes beschränkt, möglicherweise von verminderter Qualität. |
| [isAllowFillIn](#isAllowFillIn--) | Setzt die Berechtigung, die das Ausfüllen von Formularen erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten. |
| [isAllowModifyAnnotations](#isAllowModifyAnnotations--) | Setzt die Berechtigung, die das Ändern von Anmerkungen erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten. |
| [isAllowModifyContents](#isAllowModifyContents--) | Setzt die Berechtigung, die das Ändern von Inhalten erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten. |
| [isAllowPrint](#isAllowPrint--) | Setzt die Berechtigung, die das Drucken erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten. |
| [isAllowScreenReaders](#isAllowScreenReaders--) | Setzt die Berechtigung, die Bildschirmleser erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten. |
| [setAllowAssembly](#setAllowAssembly-boolean-) | Setzt die Berechtigung, die das Zusammenfügen erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten. |
| [setAllowCopy](#setAllowCopy-boolean-) | Setzt die Berechtigung, die das Kopieren erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten. |
| [setAllowDegradedPrinting](#setAllowDegradedPrinting-boolean-) | Setzt die Berechtigung, die das degradierte Drucken erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten. Wenn gesetzt, wird der Druck auf eine niedrigstufige Darstellung des Erscheinungsbildes beschränkt, möglicherweise von verminderter Qualität. |
| [setAllowFillIn](#setAllowFillIn-boolean-) | Setzt die Berechtigung, die das Ausfüllen von Formularen erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten. |
| [setAllowModifyAnnotations](#setAllowModifyAnnotations-boolean-) | Setzt die Berechtigung, die das Ändern von Anmerkungen erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten. |
| [setAllowModifyContents](#setAllowModifyContents-boolean-) | Setzt die Berechtigung, die das Ändern von Inhalten erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten. |
| [setAllowPrint](#setAllowPrint-boolean-) | Setzt die Berechtigung, die das Drucken erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten. |
| [setAllowScreenReaders](#setAllowScreenReaders-boolean-) | Setzt die Berechtigung, die Bildschirmleser erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten. |
| [setChangeAllowLevel](#setChangeAllowLevel-int-) | Liest und setzt die Änderungsstufe der Dokumenten‑Berechtigung. Entspricht den "Changes Allowed"-Einstellungen von Adobe Professional. 0: Keine. 1: Einfügen, Löschen und Drehen von Seiten. 2: Ausfüllen von Formularfeldern und Signieren vorhandener Signaturfelder. 3: Kommentieren, Ausfüllen von Formularfeldern und Signieren vorhandener Signaturfelder. 4: Alles außer dem Extrahieren von Seiten. Hat die Eigenschaft den Wert -1, ist die Stufe undefiniert. |
| [setCopyAllowLevel](#setCopyAllowLevel-int-) | Liest und setzt die Kopierstufe der Dokumenten‑Berechtigung. Entspricht den Berechtigungseinstellungen von Adobe Professional. 0: Keine. 1: Textzugriff für Screen‑Reader‑Geräte für sehbehinderte Personen aktivieren. 2: Kopieren von Text, Bildern und anderem Inhalt aktivieren. Hat die Eigenschaft den Wert -1, ist die Stufe undefiniert. |
| [setPrintAllowLevel](#setPrintAllowLevel-int-) | Liest und setzt die Druckstufe der Dokumentenprivilegien. Entspricht den Druck‑Erlaubt‑Einstellungen von Adobe Professional. 0: Keine. 1: Niedrige Auflösung (150 dpi). 2: Hohe Auflösung. Hat die Eigenschaft den Wert -1, ist die Stufe undefiniert. |

### compareTo {#compareTo-java.lang.Object-}
Vergleicht zwei {@code DocumentPrivilege}-Objekte.

### equals {#equals-java.lang.Object-}
Gibt an, ob ein anderes Objekt diesem "gleich" ist. <p> Die <code>equals</code>-Methode implementiert eine Äquivalenzrelation für nicht‑null Objekt‑Referenzen: <ul> <li>Sie ist <i>reflexiv</i>: Für jeden nicht‑null Referenzwert <code>x</code> sollte <code>x.equals(x)</code> <code>true</code> zurückgeben. <li>Sie ist <i>symmetrisch</i>: Für beliebige nicht‑null Referenzwerte <code>x</code> und <code>y</code> sollte <code>x.equals(y)</code> <code>true</code> zurückgeben, genau dann wenn <code>y.equals(x)</code> <code>true</code> zurückgibt. <li>Sie ist <i>transitiv</i>: Für beliebige nicht‑null Referenzwerte <code>x</code>, <code>y</code> und <code>z</code> sollte, wenn <code>x.equals(y)</code> <code>true</code> und <code>y.equals(z)</code> <code>true</code> zurückgeben, auch <code>x.equals(z)</code> <code>true</code> zurückgeben. <li>Sie ist <i>konsistent</i>: Für beliebige nicht‑null Referenzwerte <code>x</code> und <code>y</code> geben mehrere Aufrufe von <tt>x.equals(y)</tt> stets <code>true</code> oder stets <code>false</code> zurück, vorausgesetzt, dass keine Informationen, die in <code>equals</code>-Vergleichen verwendet werden, verändert wurden. <li>Für jeden nicht‑null Referenzwert <code>x</code> sollte <code>x.equals(null)</code> <code>false</code> zurückgeben. </ul> <p> Die <tt>equals</tt>-Methode für die Klasse <code>Object</code> implementiert die strengste mögliche Äquivalenzrelation für Objekte; das heißt, für beliebige nicht‑null Referenzwerte <code>x</code> und <code>y</code> gibt diese Methode <code>true</code> zurück, genau dann wenn <code>x</code> und <code>y</code> auf dasselbe Objekt verweisen (<code>x == y</code> hat den Wert <code>true</code>). <p> Hinweis: Es ist im Allgemeinen notwendig, die <tt>hashCode</tt>-Methode zu überschreiben, wann immer diese Methode überschrieben wird, um den allgemeinen Vertrag für die <tt>hashCode</tt>-Methode einzuhalten, der besagt, dass gleiche Objekte gleiche Hash‑Codes besitzen.

### getAllowAll {#getAllowAll--}
```
public static DocumentPrivilege getAllowAll()
```

Alle erlaubt.

**Returns:**
DocumentPrivilege‑Element

### getAssembly {#getAssembly--}
```
public static DocumentPrivilege getAssembly()
```

Erlaubt das Assemblieren der Datei.

**Returns:**
DocumentPrivilege‑Element

### getChangeAllowLevel {#getChangeAllowLevel--}
```
public final int getChangeAllowLevel()
```

Liest und setzt die Änderungsstufe der Dokumenten‑Berechtigung. Entspricht den "Changes Allowed"-Einstellungen von Adobe Professional. 0: Keine. 1: Einfügen, Löschen und Drehen von Seiten. 2: Ausfüllen von Formularfeldern und Signieren vorhandener Signaturfelder. 3: Kommentieren, Ausfüllen von Formularfeldern und Signieren vorhandener Signaturfelder. 4: Alles außer dem Extrahieren von Seiten. Hat die Eigenschaft den Wert -1, ist die Stufe undefiniert.

**Returns:**
int-Wert

### getCopy {#getCopy--}
```
public static DocumentPrivilege getCopy()
```

Erlaubt das Kopieren der Datei.

**Returns:**
DocumentPrivilege‑Element

### getCopyAllowLevel {#getCopyAllowLevel--}
```
public final int getCopyAllowLevel()
```

Liest und setzt die Kopierstufe der Dokumenten‑Berechtigung. Entspricht den Berechtigungseinstellungen von Adobe Professional. 0: Keine. 1: Textzugriff für Screen‑Reader‑Geräte für sehbehinderte Personen aktivieren. 2: Kopieren von Text, Bildern und anderem Inhalt aktivieren. Hat die Eigenschaft den Wert -1, ist die Stufe undefiniert.

**Returns:**
int-Wert

### getDegradedPrinting {#getDegradedPrinting--}
```
public static DocumentPrivilege getDegradedPrinting()
```

Erlaubt das Drucken in reduzierter Qualität.

**Returns:**
DocumentPrivilege‑Element

### getFillIn {#getFillIn--}
```
public static DocumentPrivilege getFillIn()
```

Erlaubt das Ausfüllen von Formularen in der Datei.

**Returns:**
DocumentPrivilege‑Element

### getForbidAll {#getForbidAll--}
```
public static DocumentPrivilege getForbidAll()
```

Alles verboten.

**Returns:**
DocumentPrivilege‑Element

### getModifyAnnotations {#getModifyAnnotations--}
```
public static DocumentPrivilege getModifyAnnotations()
```

Erlaubt das Ändern von Anmerkungen der Datei.

**Returns:**
DocumentPrivilege‑Element

### getModifyContents {#getModifyContents--}
```
public static DocumentPrivilege getModifyContents()
```

Erlaubt das Ändern der Datei.

**Returns:**
DocumentPrivilege‑Element

### getPrint {#getPrint--}
```
public static DocumentPrivilege getPrint()
```

Erlaubt das Drucken der Datei.

**Returns:**
DocumentPrivilege‑Element

### getPrintAllowLevel {#getPrintAllowLevel--}
```
public final int getPrintAllowLevel()
```

Liest und setzt die Druckstufe der Dokumentenprivilegien. Entspricht den Druck‑Erlaubt‑Einstellungen von Adobe Professional. 0: Keine. 1: Niedrige Auflösung (150 dpi). 2: Hohe Auflösung. Hat die Eigenschaft den Wert -1, ist die Stufe undefiniert.

**Returns:**
int-Wert

### getScreenReaders {#getScreenReaders--}
```
public static DocumentPrivilege getScreenReaders()
```

Erlaubt das Lesen nur auf dem Bildschirm.

**Returns:**
DocumentPrivilege‑Element

### getValue {#getValue--}
```
public final int getValue()
```



### hashCode {#hashCode--}
```
public int hashCode()
```

Gibt einen Hashcode‑Wert für das Objekt zurück. Diese Methode wird zum Nutzen von Hashtabellen bereitgestellt, wie sie z. B. von <code>java.util.Hashtable</code> bereitgestellt werden. <p> Der allgemeine Vertrag von <code>hashCode</code> lautet: <ul> <li>Immer wenn sie während der Ausführung einer Java‑Anwendung mehrmals auf demselben Objekt aufgerufen wird, muss die <tt>hashCode</tt>-Methode konsistent denselben Integer zurückgeben, vorausgesetzt, es werden keine Informationen geändert, die in <tt>equals</tt>-Vergleichen des Objekts verwendet werden. Dieser Integer muss nicht von einer Programmausführung zur nächsten konsistent bleiben. <li>Wenn zwei Objekte gemäß der <tt>equals(Object)</tt>-Methode gleich sind, muss der Aufruf der <code>hashCode</code>-Methode auf beiden Objekten dasselbe Integer‑Ergebnis liefern. <li>Es ist <em>nicht</em> erforderlich, dass bei ungleichen Objekten gemäß der {@link java.lang.Object#equals(java.lang.Object)}‑Methode der Aufruf der <tt>hashCode</tt>-Methode auf beiden Objekten unterschiedliche Integer‑Ergebnisse liefert. Der Programmierer sollte jedoch beachten, dass unterschiedliche Integer‑Ergebnisse für ungleiche Objekte die Leistung von Hashtabellen verbessern können. </ul> <p> Soweit praktisch möglich, liefert die von der Klasse <tt>Object</tt> definierte hashCode‑Methode unterschiedliche Integer für unterschiedliche Objekte. (Dies wird typischerweise dadurch umgesetzt, dass die interne Adresse des Objekts in einen Integer umgewandelt wird, aber diese Implementierungstechnik ist nicht durch die Java<span style="font-size:70%"><sup>TM</sup></span>-Programmiersprache vorgeschrieben.)

**Returns:**
ein Hashcode‑Wert für dieses Objekt. @see java.lang.Object#equals(java.lang.Object) @see java.util.Hashtable

### isAllowAssembly {#isAllowAssembly--}
```
public boolean isAllowAssembly()
```

Setzt die Berechtigung, die das Zusammenfügen erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten.

**Returns:**
boolescher Wert

### isAllowCopy {#isAllowCopy--}
```
public boolean isAllowCopy()
```

Setzt die Berechtigung, die das Kopieren erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten.

**Returns:**
boolescher Wert

### isAllowDegradedPrinting {#isAllowDegradedPrinting--}
```
public boolean isAllowDegradedPrinting()
```

Setzt die Berechtigung, die das degradierte Drucken erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten. Wenn gesetzt, wird der Druck auf eine niedrigstufige Darstellung des Erscheinungsbildes beschränkt, möglicherweise von verminderter Qualität.

**Returns:**
boolescher Wert

### isAllowFillIn {#isAllowFillIn--}
```
public boolean isAllowFillIn()
```

Setzt die Berechtigung, die das Ausfüllen von Formularen erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten.

**Returns:**
boolescher Wert

### isAllowModifyAnnotations {#isAllowModifyAnnotations--}
```
public boolean isAllowModifyAnnotations()
```

Setzt die Berechtigung, die das Ändern von Anmerkungen erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten.

**Returns:**
boolescher Wert

### isAllowModifyContents {#isAllowModifyContents--}
```
public boolean isAllowModifyContents()
```

Setzt die Berechtigung, die das Ändern von Inhalten erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten.

**Returns:**
boolescher Wert

### isAllowPrint {#isAllowPrint--}
```
public boolean isAllowPrint()
```

Setzt die Berechtigung, die das Drucken erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten.

**Returns:**
boolescher Wert

### isAllowScreenReaders {#isAllowScreenReaders--}
```
public boolean isAllowScreenReaders()
```

Setzt die Berechtigung, die Bildschirmleser erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten.

**Returns:**
boolescher Wert

### setAllowAssembly {#setAllowAssembly-boolean-}
```
public void setAllowAssembly(boolean value)
```

Setzt die Berechtigung, die das Zusammenfügen erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setAllowCopy {#setAllowCopy-boolean-}
```
public void setAllowCopy(boolean value)
```

Setzt die Berechtigung, die das Kopieren erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setAllowDegradedPrinting {#setAllowDegradedPrinting-boolean-}
```
public void setAllowDegradedPrinting(boolean value)
```

Setzt die Berechtigung, die das degradierte Drucken erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten. Wenn gesetzt, wird der Druck auf eine niedrigstufige Darstellung des Erscheinungsbildes beschränkt, möglicherweise von verminderter Qualität.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setAllowFillIn {#setAllowFillIn-boolean-}
```
public void setAllowFillIn(boolean value)
```

Setzt die Berechtigung, die das Ausfüllen von Formularen erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setAllowModifyAnnotations {#setAllowModifyAnnotations-boolean-}
```
public void setAllowModifyAnnotations(boolean value)
```

Setzt die Berechtigung, die das Ändern von Anmerkungen erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setAllowModifyContents {#setAllowModifyContents-boolean-}
```
public void setAllowModifyContents(boolean value)
```

Setzt die Berechtigung, die das Ändern von Inhalten erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setAllowPrint {#setAllowPrint-boolean-}
```
public void setAllowPrint(boolean value)
```

Setzt die Berechtigung, die das Drucken erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setAllowScreenReaders {#setAllowScreenReaders-boolean-}
```
public void setAllowScreenReaders(boolean value)
```

Setzt die Berechtigung, die Bildschirmleser erlaubt oder nicht. true bedeutet erlaubt und false bedeutet verboten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setChangeAllowLevel {#setChangeAllowLevel-int-}
```
public void setChangeAllowLevel(int value)
```

Liest und setzt die Änderungsstufe der Dokumenten‑Berechtigung. Entspricht den "Changes Allowed"-Einstellungen von Adobe Professional. 0: Keine. 1: Einfügen, Löschen und Drehen von Seiten. 2: Ausfüllen von Formularfeldern und Signieren vorhandener Signaturfelder. 3: Kommentieren, Ausfüllen von Formularfeldern und Signieren vorhandener Signaturfelder. 4: Alles außer dem Extrahieren von Seiten. Hat die Eigenschaft den Wert -1, ist die Stufe undefiniert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setCopyAllowLevel {#setCopyAllowLevel-int-}
```
public void setCopyAllowLevel(int value)
```

Liest und setzt die Kopierstufe der Dokumenten‑Berechtigung. Entspricht den Berechtigungseinstellungen von Adobe Professional. 0: Keine. 1: Textzugriff für Screen‑Reader‑Geräte für sehbehinderte Personen aktivieren. 2: Kopieren von Text, Bildern und anderem Inhalt aktivieren. Hat die Eigenschaft den Wert -1, ist die Stufe undefiniert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setPrintAllowLevel {#setPrintAllowLevel-int-}
```
public void setPrintAllowLevel(int value)
```

Liest und setzt die Druckstufe der Dokumentenprivilegien. Entspricht den Druck‑Erlaubt‑Einstellungen von Adobe Professional. 0: Keine. 1: Niedrige Auflösung (150 dpi). 2: Hohe Auflösung. Hat die Eigenschaft den Wert -1, ist die Stufe undefiniert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |
