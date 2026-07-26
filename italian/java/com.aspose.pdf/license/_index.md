---
title: "License"
linktitle: "License"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Fornisce metodi per licenziare il componente. In questo esempio, verrà tentato di trovare un file di licenza chiamato MyLicense.lic nella cartella che contiene il componente, nella."
type: docs
weight: 2670
url: /it/java/com.aspose.pdf/license/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.License

```
public class License extends Object
```

Fornisce metodi per licenziare il componente. In questo esempio, verrà tentato di trovare un file di licenza chiamato MyLicense.lic nella cartella che contiene il componente, nella cartella che contiene l'assembly chiamante, nella cartella dell'assembly di ingresso e poi nelle risorse incorporate dell'assembly chiamante. License license = new License(); license.setLicense(\"MyLicense.lic\");

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [License](#License--) | Inizializza una nuova istanza di questa classe. In questo esempio, verrà tentato di trovare un file di licenza chiamato MyLicense.lic nella cartella che contiene il componente, nella cartella che contiene l'assembly chiamante, nella cartella dell'assembly di ingresso e poi nelle risorse incorporate dell'assembly chiamante. License license = new License(); license.setLicense("MyLicense.lic"); |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [clearLicense](#clearLicense--) | Cancella la licenza corrente. |
| [getLicenseInfo](#getLicenseInfo--) | Ottiene le informazioni sulla licenza corrente. |
| [isInternalFIPSSecurity](#isInternalFIPSSecurity--) | Per impostazione predefinita, utilizziamo la sicurezza jdk predefinita. Valore predefinito == false. In alcuni casi l'ambiente java personalizzato non può supportare gli algoritmi richiesti, quindi possiamo suggerire di utilizzare la sicurezza FIPS integrata interna. |
| [setInternalFIPSSecurity](#setInternalFIPSSecurity-boolean-) | Per impostazione predefinita, utilizziamo la sicurezza jre predefinita. Valore predefinito == false. In alcuni casi l'ambiente java personalizzato non può supportare gli algoritmi richiesti, quindi possiamo suggerire di utilizzare la sicurezza FIPS integrata interna. <p> Nota anche: Secondo l'algoritmo JVM SecureRandom su alcuni sistemi operativi /dev/random attende che venga generato un certo quantitativo di “rumore” sulla macchina host prima di restituire un risultato. La libreria usata per la generazione di numeri casuali nella JVM di Oracle si basa su /dev/random per impostazione predefinita per le piattaforme UNIX. Sebbene /dev/random sia più sicuro, è consigliato usare /dev/urandom se la configurazione JVM predefinita provoca ritardi, o aggiungere dispositivi che generano entropia per /dev/random. <p> L'opzione java seguente può aiutare a evitare ritardi e sovrascrivere l'impostazione securerandom.source. -Djava.security.egd=file:/dev/./urandom |
| [setLicense](#setLicense-java.io.InputStream-) | Licenzia il componente. Un flusso che contiene la licenza. Usa questo metodo per caricare una licenza da un flusso. License license = new License(); license.setLicense(myStream); |
| [setLicense](#setLicense-java.lang.String-) | Licenzia il componente. Tenta di trovare la licenza nelle seguenti posizioni: 1. Percorso esplicito. 2. La cartella del file jar del componente. In questo esempio, verrà tentato di trovare un file di licenza chiamato MyLicense.lic nella cartella che contiene il componente, nella cartella che contiene l'assembly chiamante, nella cartella dell'assembly di ingresso e poi nelle risorse incorporate dell'assembly chiamante. License license = new License(); license.setLicense("MyLicense.lic"); |

### License {#License--}
```
public License()
```

Inizializza una nuova istanza di questa classe. In questo esempio, verrà tentato di trovare un file di licenza chiamato MyLicense.lic nella cartella che contiene il componente, nella cartella che contiene l'assembly chiamante, nella cartella dell'assembly di ingresso e poi nelle risorse incorporate dell'assembly chiamante. License license = new License(); license.setLicense("MyLicense.lic");

### clearLicense {#clearLicense--}
```
public final void clearLicense()
```

Cancella la licenza corrente.

### getLicenseInfo {#getLicenseInfo--}
```
public final LicenseInfo getLicenseInfo()
```

Ottiene le informazioni sulla licenza corrente.

**Returns:**
istanza di LicenseInfo

### isInternalFIPSSecurity {#isInternalFIPSSecurity--}
```
public static boolean isInternalFIPSSecurity()
```

Per impostazione predefinita, utilizziamo la sicurezza jdk predefinita. Valore predefinito == false. In alcuni casi l'ambiente java personalizzato non può supportare gli algoritmi richiesti, quindi possiamo suggerire di utilizzare la sicurezza FIPS integrata interna.

**Returns:**
valore booleano

### setInternalFIPSSecurity {#setInternalFIPSSecurity-boolean-}
```
public static void setInternalFIPSSecurity(boolean internalFIPSSecurity)
```

Per impostazione predefinita, utilizziamo la sicurezza jre predefinita. Valore predefinito == false. In alcuni casi l'ambiente java personalizzato non può supportare gli algoritmi richiesti, quindi possiamo suggerire di utilizzare la sicurezza FIPS integrata interna. <p> Nota anche: Secondo l'algoritmo JVM SecureRandom su alcuni sistemi operativi /dev/random attende che venga generato un certo quantitativo di “rumore” sulla macchina host prima di restituire un risultato. La libreria usata per la generazione di numeri casuali nella JVM di Oracle si basa su /dev/random per impostazione predefinita per le piattaforme UNIX. Sebbene /dev/random sia più sicuro, è consigliato usare /dev/urandom se la configurazione JVM predefinita provoca ritardi, o aggiungere dispositivi che generano entropia per /dev/random. <p> L'opzione java seguente può aiutare a evitare ritardi e sovrascrivere l'impostazione securerandom.source. -Djava.security.egd=file:/dev/./urandom

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| internalFIPSSecurity |  | valore booleano |

### setLicense {#setLicense-java.io.InputStream-}
Licenzia il componente. Un flusso che contiene la licenza. Usa questo metodo per caricare una licenza da un flusso. License license = new License(); license.setLicense(myStream);

### setLicense {#setLicense-java.lang.String-}
Licenzia il componente. Tenta di trovare la licenza nelle seguenti posizioni: 1. Percorso esplicito. 2. La cartella del file jar del componente. In questo esempio, verrà tentato di trovare un file di licenza chiamato MyLicense.lic nella cartella che contiene il componente, nella cartella che contiene l'assembly chiamante, nella cartella dell'assembly di ingresso e poi nelle risorse incorporate dell'assembly chiamante. License license = new License(); license.setLicense("MyLicense.lic");
