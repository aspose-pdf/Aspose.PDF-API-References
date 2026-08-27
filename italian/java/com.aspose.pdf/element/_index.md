---
title: "Elemento"
linktitle: "Elemento"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'elemento base della struttura logica."
type: docs
weight: 1180
url: /it/java/com.aspose.pdf/element/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Element

```
public abstract class Element extends Object
```

Classe che rappresenta l'elemento base della struttura logica.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getActualText](#getActualText--) | (Opzionale; PDF 1.4) Testo che è una sostituzione esatta per l'elemento di struttura e i suoi figli. Questo testo di sostituzione (che dovrebbe applicarsi a una porzione di contenuto il più piccola possibile) è utile durante l'estrazione del contenuto del documento a supporto dell'accessibilità per gli utenti con disabilità o per altri scopi. |
| [getAlt](#getAlt--) | (Opzionale) Una descrizione alternativa dell'elemento di struttura e dei suoi figli in forma leggibile dall'uomo, utile durante l'estrazione del contenuto del documento a supporto dell'accessibilità per gli utenti con disabilità o per altri scopi. |
| [getChildren](#getChildren--) | Ottiene la collezione di elementi figli. |
| [getE](#getE--) | (Opzionale; PDF 1.5) La forma estesa di un'abbreviazione. |
| [getLang](#getLang--) | (Opzionale; PDF 1.4) Una lingua che specifica la lingua naturale per tutto il testo nell'elemento di struttura, eccetto dove sovrascritto da specifiche linguistiche per elementi di struttura nidificati o contenuti marcati. |
| [remove](#remove--) | Rimuovi elemento. |
| [setActualText](#setActualText-java.lang.String-) | (Opzionale; PDF 1.4) Testo che è una sostituzione esatta per l'elemento di struttura e i suoi figli. Questo testo di sostituzione (che dovrebbe applicarsi a una porzione di contenuto il più piccola possibile) è utile durante l'estrazione del contenuto del documento a supporto dell'accessibilità per gli utenti con disabilità o per altri scopi. |
| [setAlt](#setAlt-java.lang.String-) | (Opzionale) Una descrizione alternativa dell'elemento di struttura e dei suoi figli in forma leggibile dall'uomo, utile durante l'estrazione del contenuto del documento a supporto dell'accessibilità per gli utenti con disabilità o per altri scopi. |
| [setE](#setE-java.lang.String-) | (Opzionale; PDF 1.5) La forma estesa di un'abbreviazione. |
| [setLang](#setLang-java.lang.String-) | (Opzionale; PDF 1.4) Una lingua che specifica la lingua naturale per tutto il testo nell'elemento di struttura, eccetto dove sovrascritto da specifiche linguistiche per elementi di struttura nidificati o contenuti marcati. |

### getActualText {#getActualText--}
```
public String getActualText()
```

(Opzionale; PDF 1.4) Testo che è una sostituzione esatta per l'elemento di struttura e i suoi figli. Questo testo di sostituzione (che dovrebbe applicarsi a una porzione di contenuto il più piccola possibile) è utile durante l'estrazione del contenuto del documento a supporto dell'accessibilità per gli utenti con disabilità o per altri scopi.

**Returns:**
Oggetto stringa

### getAlt {#getAlt--}
```
public String getAlt()
```

(Opzionale) Una descrizione alternativa dell'elemento di struttura e dei suoi figli in forma leggibile dall'uomo, utile durante l'estrazione del contenuto del documento a supporto dell'accessibilità per gli utenti con disabilità o per altri scopi.

**Returns:**
Oggetto stringa

### getChildren {#getChildren--}
```
public final ElementCollection getChildren()
```

Ottiene la collezione di elementi figli.

**Returns:**
Istanza di ElementCollection

### getE {#getE--}
```
public String getE()
```

(Opzionale; PDF 1.5) La forma estesa di un'abbreviazione.

**Returns:**
Oggetto stringa

### getLang {#getLang--}
```
public String getLang()
```

(Opzionale; PDF 1.4) Una lingua che specifica la lingua naturale per tutto il testo nell'elemento di struttura, eccetto dove sovrascritto da specifiche linguistiche per elementi di struttura nidificati o contenuti marcati.

**Returns:**
Oggetto stringa

### remove {#remove--}
```
public final void remove()
```

Rimuovi elemento.

### setActualText {#setActualText-java.lang.String-}
(Opzionale; PDF 1.4) Testo che è una sostituzione esatta per l'elemento di struttura e i suoi figli. Questo testo di sostituzione (che dovrebbe applicarsi a una porzione di contenuto il più piccola possibile) è utile durante l'estrazione del contenuto del documento a supporto dell'accessibilità per gli utenti con disabilità o per altri scopi.

### setAlt {#setAlt-java.lang.String-}
(Opzionale) Una descrizione alternativa dell'elemento di struttura e dei suoi figli in forma leggibile dall'uomo, utile durante l'estrazione del contenuto del documento a supporto dell'accessibilità per gli utenti con disabilità o per altri scopi.

### setE {#setE-java.lang.String-}
(Opzionale; PDF 1.5) La forma estesa di un'abbreviazione.

### setLang {#setLang-java.lang.String-}
(Opzionale; PDF 1.4) Una lingua che specifica la lingua naturale per tutto il testo nell'elemento di struttura, eccetto dove sovrascritto da specifiche linguistiche per elementi di struttura nidificati o contenuti marcati.
