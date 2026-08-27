---
title: "FolderFontSource"
linktitle: "FolderFontSource"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta la cartella che contiene i file di carattere."
type: docs
weight: 1640
url: /it/java/com.aspose.pdf/folderfontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.FolderFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.FolderFontSource

```
public final class FolderFontSource extends FontSource
```

Rappresenta la cartella che contiene i file di carattere.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FolderFontSource](#FolderFontSource-java.lang.String-) | Inizializza una nuova istanza della classe {@code FolderFontSource}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Verifica se gli oggetti della sorgente font della cartella sono uguali. |
| [getFolderPath](#getFolderPath--) | Percorso della cartella che contiene i file dei font. |
| [hashCode](#hashCode--) | Restituisce un valore di hash code per l'oggetto. Questo metodo è supportato per il beneficio delle tabelle hash, come quelle fornite da {@link java.util.HashMap}. <p> Il contratto generale di {@code hashCode} è: <ul> <li>Ogni volta che viene invocato sullo stesso oggetto più di una volta durante l'esecuzione di un'applicazione Java, il metodo {@code hashCode} deve restituire costantemente lo stesso intero, a condizione che nessuna informazione usata nei confronti {@code equals} sull'oggetto sia modificata. Questo intero non deve rimanere coerente da un'esecuzione dell'applicazione a un'altra esecuzione della stessa applicazione. <li>Se due oggetti sono uguali secondo il metodo {@code equals(Object)}, allora chiamare il metodo {@code hashCode} su ciascuno dei due oggetti deve produrre lo stesso risultato intero. <li>Non è <em>necessario</em> che se due oggetti sono diversi secondo il metodo {@link java.lang.Object#equals(java.lang.Object)}, allora chiamare il metodo {@code hashCode} su ciascuno dei due oggetti produca risultati interi distinti. Tuttavia, lo sviluppatore dovrebbe essere consapevole che produrre risultati interi distinti per oggetti diversi può migliorare le prestazioni delle tabelle hash. </ul> <p> Per quanto ragionevolmente praticabile, il metodo hashCode definito dalla classe {@code Object} restituisce interi distinti per oggetti distinti. (Questo è tipicamente implementato convertendo l'indirizzo interno dell'oggetto in un intero, ma questa tecnica di implementazione non è richiesta dal linguaggio di programmazione Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |
| [setFolderPath](#setFolderPath-java.lang.String-) |  |

### FolderFontSource {#FolderFontSource-java.lang.String-}
Inizializza una nuova istanza della classe {@code FolderFontSource}.

### equals {#equals-java.lang.Object-}
Verifica se gli oggetti della sorgente font della cartella sono uguali.

### getFolderPath {#getFolderPath--}
```
public String getFolderPath()
```

Percorso della cartella che contiene i file dei font.

**Returns:**
valore String

### hashCode {#hashCode--}
```
public int hashCode()
```

Restituisce un valore di hash code per l'oggetto. Questo metodo è supportato per il beneficio delle tabelle hash, come quelle fornite da {@link java.util.HashMap}. <p> Il contratto generale di {@code hashCode} è: <ul> <li>Ogni volta che viene invocato sullo stesso oggetto più di una volta durante l'esecuzione di un'applicazione Java, il metodo {@code hashCode} deve restituire costantemente lo stesso intero, a condizione che nessuna informazione usata nei confronti {@code equals} sull'oggetto sia modificata. Questo intero non deve rimanere coerente da un'esecuzione dell'applicazione a un'altra esecuzione della stessa applicazione. <li>Se due oggetti sono uguali secondo il metodo {@code equals(Object)}, allora chiamare il metodo {@code hashCode} su ciascuno dei due oggetti deve produrre lo stesso risultato intero. <li>Non è <em>necessario</em> che se due oggetti sono diversi secondo il metodo {@link java.lang.Object#equals(java.lang.Object)}, allora chiamare il metodo {@code hashCode} su ciascuno dei due oggetti produca risultati interi distinti. Tuttavia, lo sviluppatore dovrebbe essere consapevole che produrre risultati interi distinti per oggetti diversi può migliorare le prestazioni delle tabelle hash. </ul> <p> Per quanto ragionevolmente praticabile, il metodo hashCode definito dalla classe {@code Object} restituisce interi distinti per oggetti distinti. (Questo è tipicamente implementato convertendo l'indirizzo interno dell'oggetto in un intero, ma questa tecnica di implementazione non è richiesta dal linguaggio di programmazione Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
un valore di hash code per questo oggetto. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setFolderPath {#setFolderPath-java.lang.String-}
