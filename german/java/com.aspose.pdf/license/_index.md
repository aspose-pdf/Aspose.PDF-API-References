---
title: "Lizenz"
linktitle: "Lizenz"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt Methoden zum Lizenzieren der Komponente bereit. In diesem Beispiel wird versucht, eine Lizenzdatei mit dem Namen MyLicense.lic im Ordner zu finden, der die Komponente enthält, im."
type: docs
weight: 2670
url: /de/java/com.aspose.pdf/license/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.License

```
public class License extends Object
```

Stellt Methoden zur Lizenzierung der Komponente bereit. In diesem Beispiel wird versucht, eine Lizenzdatei mit dem Namen MyLicense.lic im Ordner zu finden, der die Komponente enthält, im Ordner, der die aufrufende Assembly enthält, im Ordner der Einstieg-Assembly und anschließend in den eingebetteten Ressourcen der aufrufenden Assembly. License license = new License(); license.setLicense("MyLicense.lic");

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [License](#License--) | Initialisiert eine neue Instanz dieser Klasse. In diesem Beispiel wird versucht, eine Lizenzdatei mit dem Namen MyLicense.lic im Ordner zu finden, der die Komponente enthält, im Ordner, der die aufrufende Assembly enthält, im Ordner der Einstieg-Assembly und dann in den eingebetteten Ressourcen der aufrufenden Assembly. License license = new License(); license.setLicense("MyLicense.lic"); |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [clearLicense](#clearLicense--) | Löscht die aktuelle Lizenz. |
| [getLicenseInfo](#getLicenseInfo--) | Ruft die aktuellen Lizenzinformationen ab. |
| [isInternalFIPSSecurity](#isInternalFIPSSecurity--) | Standardmäßig verwenden wir die standardmäßige JDK-Sicherheit. Standardwert == false. In einigen Fällen kann die angepasste Java-Umgebung die erforderlichen Algorithmen nicht unterstützen, daher können wir vorschlagen, die interne eingebaute FIPS-Sicherheit zu verwenden. |
| [setInternalFIPSSecurity](#setInternalFIPSSecurity-boolean-) | Standardmäßig verwenden wir die standardmäßige JRE-Sicherheit. Standardwert == false. In einigen Fällen kann die angepasste Java-Umgebung die erforderlichen Algorithmen nicht unterstützen, daher können wir vorschlagen, die interne eingebaute FIPS-Sicherheit zu verwenden. <p> Hinweis auch: Laut dem JVM SecureRandom-Algorithmus wartet /dev/random auf einigen Betriebssystemen, bis eine bestimmte Menge an „Rauschen“ auf dem Host‑Computer erzeugt wurde, bevor ein Ergebnis zurückgegeben wird. Die Bibliothek, die für die Zufallszahlengenerierung in Oracles JVM verwendet wird, nutzt standardmäßig /dev/random für UNIX‑Plattformen. Obwohl /dev/random sicherer ist, wird empfohlen, /dev/urandom zu verwenden, wenn die Standard‑JVM‑Konfiguration Verzögerungen verursacht, oder Geräte hinzuzufügen, die Entropie für /dev/random erzeugen. <p> Die folgende Java‑Option kann helfen, Verzögerungen zu vermeiden und die Einstellung securerandom.source zu überschreiben. -Djava.security.egd=file:/dev/./urandom |
| [setLicense](#setLicense-java.io.InputStream-) | Lizenziert die Komponente. Ein Stream, der die Lizenz enthält. Verwenden Sie diese Methode, um eine Lizenz aus einem Stream zu laden. License license = new License(); license.setLicense(myStream); |
| [setLicense](#setLicense-java.lang.String-) | Lizenziert die Komponente. Versucht, die Lizenz an den folgenden Orten zu finden: 1. Expliziter Pfad. 2. Der Ordner der Komponenten‑Jar‑Datei. In diesem Beispiel wird versucht, eine Lizenzdatei mit dem Namen MyLicense.lic im Ordner zu finden, der die Komponente enthält, im Ordner, der die aufrufende Assembly enthält, im Ordner der Einstieg‑Assembly und dann in den eingebetteten Ressourcen der aufrufenden Assembly. License license = new License(); license.setLicense("MyLicense.lic"); |

### License {#License--}
```
public License()
```

Initialisiert eine neue Instanz dieser Klasse. In diesem Beispiel wird versucht, eine Lizenzdatei mit dem Namen MyLicense.lic im Ordner zu finden, der die Komponente enthält, im Ordner, der die aufrufende Assembly enthält, im Ordner der Einstieg-Assembly und dann in den eingebetteten Ressourcen der aufrufenden Assembly. License license = new License(); license.setLicense("MyLicense.lic");

### clearLicense {#clearLicense--}
```
public final void clearLicense()
```

Löscht die aktuelle Lizenz.

### getLicenseInfo {#getLicenseInfo--}
```
public final LicenseInfo getLicenseInfo()
```

Ruft die aktuellen Lizenzinformationen ab.

**Returns:**
LicenseInfo-Instanz

### isInternalFIPSSecurity {#isInternalFIPSSecurity--}
```
public static boolean isInternalFIPSSecurity()
```

Standardmäßig verwenden wir die standardmäßige JDK-Sicherheit. Standardwert == false. In einigen Fällen kann die angepasste Java-Umgebung die erforderlichen Algorithmen nicht unterstützen, daher können wir vorschlagen, die interne eingebaute FIPS-Sicherheit zu verwenden.

**Returns:**
boolescher Wert

### setInternalFIPSSecurity {#setInternalFIPSSecurity-boolean-}
```
public static void setInternalFIPSSecurity(boolean internalFIPSSecurity)
```

Standardmäßig verwenden wir die standardmäßige JRE-Sicherheit. Standardwert == false. In einigen Fällen kann die angepasste Java-Umgebung die erforderlichen Algorithmen nicht unterstützen, daher können wir vorschlagen, die interne eingebaute FIPS-Sicherheit zu verwenden. <p> Hinweis auch: Laut dem JVM SecureRandom-Algorithmus wartet /dev/random auf einigen Betriebssystemen, bis eine bestimmte Menge an „Rauschen“ auf dem Host‑Computer erzeugt wurde, bevor ein Ergebnis zurückgegeben wird. Die Bibliothek, die für die Zufallszahlengenerierung in Oracles JVM verwendet wird, nutzt standardmäßig /dev/random für UNIX‑Plattformen. Obwohl /dev/random sicherer ist, wird empfohlen, /dev/urandom zu verwenden, wenn die Standard‑JVM‑Konfiguration Verzögerungen verursacht, oder Geräte hinzuzufügen, die Entropie für /dev/random erzeugen. <p> Die folgende Java‑Option kann helfen, Verzögerungen zu vermeiden und die Einstellung securerandom.source zu überschreiben. -Djava.security.egd=file:/dev/./urandom

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| internalFIPSSecurity |  | boolescher Wert |

### setLicense {#setLicense-java.io.InputStream-}
Lizenziert die Komponente. Ein Stream, der die Lizenz enthält. Verwenden Sie diese Methode, um eine Lizenz aus einem Stream zu laden. License license = new License(); license.setLicense(myStream);

### setLicense {#setLicense-java.lang.String-}
Lizenziert die Komponente. Versucht, die Lizenz an den folgenden Orten zu finden: 1. Expliziter Pfad. 2. Der Ordner der Komponenten‑Jar‑Datei. In diesem Beispiel wird versucht, eine Lizenzdatei mit dem Namen MyLicense.lic im Ordner zu finden, der die Komponente enthält, im Ordner, der die aufrufende Assembly enthält, im Ordner der Einstieg‑Assembly und dann in den eingebetteten Ressourcen der aufrufenden Assembly. License license = new License(); license.setLicense("MyLicense.lic");
