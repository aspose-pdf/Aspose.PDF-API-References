---
title: "DocumentPrivilege"
linktitle: "DocumentPrivilege"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta i privilegi per l'accesso al file Pdf. Vedi {@code PdfFileSecurity}. Ci sono 4 modi per utilizzare questa classe: 1.Usare direttamente il privilegio predefinito. 2.In base a un."
type: docs
weight: 110
url: /it/java/com.aspose.pdf.facades/documentprivilege/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.DocumentPrivilege

**All Implemented Interfaces:**
Comparable < Object >

```
public final class DocumentPrivilege extends Object implements Comparable < Object >
```

Rappresenta i privilegi per accedere a un file Pdf. Vedi {@code PdfFileSecurity}. Ci sono 4 modi di utilizzare questa classe: 1. Utilizzare direttamente un privilegio predefinito. 2. Basarsi su un privilegio predefinito e modificare alcune autorizzazioni specifiche. 3. Basarsi su un privilegio predefinito e modificare una combinazione specifica di autorizzazioni Adobe Professional. 4. Mescolare il modo 2 e il modo 3. //Way1: Utilizzare direttamente un privilegio predefinito. DocumentPrivilege privilege = DocumentPrivilege.getPrint(); //Way2: Basarsi su un privilegio predefinito e modificare alcune autorizzazioni specifiche. DocumentPrivilege privilege = DocumentPrivilege.getAllowAll(); privilege.setAllowPrint(false); privilege.setAllowModifyContents(false); //Way3: Basarsi su un privilegio predefinito e modificare una combinazione specifica di autorizzazioni Adobe Professional. DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setPrintAllowLevel(2); //Way4: Mescolare il modo 2 e il modo 3 DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setAllowPrint(true);

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [compareTo](#compareTo-java.lang.Object-) | Confronta due oggetti {@code DocumentPrivilege}. |
| [equals](#equals-java.lang.Object-) | Indica se qualche altro oggetto è "uguale a" questo. <p> Il metodo <code>equals</code> implementa una relazione di equivalenza su riferimenti a oggetti non nulli: <ul> <li>È <i>riflessivo</i>: per qualsiasi valore di riferimento non nullo <code>x</code>, <code>x.equals(x)</code> dovrebbe restituire <code>true</code>. <li>È <i>simmetrico</i>: per qualsiasi valore di riferimento non nullo <code>x</code> e <code>y</code>, <code>x.equals(y)</code> dovrebbe restituire <code>true</code> se e solo se <code>y.equals(x)</code> restituisce <code>true</code>. <li>È <i>transitivo</i>: per qualsiasi valore di riferimento non nullo <code>x</code>, <code>y</code> e <code>z</code>, se <code>x.equals(y)</code> restituisce <code>true</code> e <code>y.equals(z)</code> restituisce <code>true</code>, allora <code>x.equals(z)</code> dovrebbe restituire <code>true</code>. <li>È <i>coerente</i>: per qualsiasi valore di riferimento non nullo <code>x</code> e <code>y</code>, più invocazioni di <tt>x.equals(y)</tt> restituiscono costantemente <code>true</code> o costantemente <code>false</code>, a condizione che nessuna informazione usata nei confronti <code>equals</code> sugli oggetti sia modificata. <li>Per qualsiasi valore di riferimento non nullo <code>x</code>, <code>x.equals(null)</code> dovrebbe restituire <code>false</code>. </ul> <p> Il metodo <tt>equals</tt> per la classe <code>Object</code> implementa la relazione di equivalenza più discriminante possibile sugli oggetti; cioè, per qualsiasi valore di riferimento non nullo <code>x</code> e <code>y</code>, questo metodo restituisce <code>true</code> se e solo se <code>x</code> e <code>y</code> si riferiscono allo stesso oggetto (<code>x == y</code> ha valore <code>true</code>). <p> Nota che è generalmente necessario sovrascrivere il metodo <tt>hashCode</tt> ogni volta che questo metodo è sovrascritto, così da mantenere il contratto generale per il metodo <tt>hashCode</tt>, che afferma che gli oggetti uguali devono avere lo stesso codice hash. |
| [getAllowAll](#getAllowAll--) | Tutto consentito. |
| [getAssembly](#getAssembly--) | Consente l'assemblaggio del file. |
| [getChangeAllowLevel](#getChangeAllowLevel--) | Ottiene e imposta il livello di modifica del privilegio del documento. Come le impostazioni Changes Allowed di Adobe Professional. 0: Nessuno. 1: Inserimento, eliminazione e rotazione delle pagine. 2: Compilazione dei campi modulo e firma dei campi firma esistenti. 3: Commenti, compilazione dei campi modulo e firma dei campi firma esistenti. 4: Qualsiasi operazione tranne l'estrazione delle pagine. Se la proprietà ha valore -1, il livello è indefinito. |
| [getCopy](#getCopy--) | Consente la copia del file. |
| [getCopyAllowLevel](#getCopyAllowLevel--) | Ottiene e imposta il livello di copia del privilegio del documento. Come le impostazioni dei permessi di Adobe Professional. 0: Nessuno. 1: Abilita l'accesso al testo per dispositivi di lettura schermo per ipovedenti. 2: Abilita la copia di testo, immagini e altri contenuti. Se la proprietà ha valore -1, il livello è indefinito. |
| [getDegradedPrinting](#getDegradedPrinting--) | Consente la stampa degradata. |
| [getFillIn](#getFillIn--) | Consente la compilazione dei moduli nel file. |
| [getForbidAll](#getForbidAll--) | Tutto vietato. |
| [getModifyAnnotations](#getModifyAnnotations--) | Consente la modifica delle annotazioni del file. |
| [getModifyContents](#getModifyContents--) | Consente la modifica del file. |
| [getPrint](#getPrint--) | Consente la stampa del file. |
| [getPrintAllowLevel](#getPrintAllowLevel--) | Ottiene e imposta il livello di stampa del privilegio del documento. Come le impostazioni Printing Allowed di Adobe Professional. 0: Nessuno. 1: Bassa risoluzione (150 dpi). 2: Alta risoluzione. Se la proprietà ha valore -1, il livello è indefinito. |
| [getScreenReaders](#getScreenReaders--) | Consente la lettura solo su schermo. |
| [getValue](#getValue--) |  |
| [hashCode](#hashCode--) | Restituisce un valore di codice hash per l'oggetto. Questo metodo è supportato a beneficio delle tabelle hash, come quelle fornite da <code>java.util.Hashtable</code>. <p> Il contratto generale di <code>hashCode</code> è: <ul> <li>Ogni volta che viene invocato sullo stesso oggetto più di una volta durante l'esecuzione di un'applicazione Java, il metodo <tt>hashCode</tt> deve restituire costantemente lo stesso intero, a condizione che nessuna informazione usata nei confronti <tt>equals</tt> sull'oggetto sia modificata. Questo intero non deve rimanere coerente da un'esecuzione dell'applicazione a un'altra esecuzione della stessa applicazione. <li>Se due oggetti sono uguali secondo il metodo <tt>equals(Object)</tt>, allora chiamare il metodo <code>hashCode</code> su ciascuno dei due oggetti deve produrre lo stesso risultato intero. <li>Non è <em>obbligatorio</em> che se due oggetti sono diversi secondo il metodo {@link java.lang.Object#equals(java.lang.Object)}, allora chiamare il metodo <tt>hashCode</tt> su ciascuno dei due oggetti debba produrre risultati interi distinti. Tuttavia, lo sviluppatore dovrebbe essere consapevole che produrre risultati interi distinti per oggetti diversi può migliorare le prestazioni delle tabelle hash. </ul> <p> Per quanto ragionevolmente praticabile, il metodo hashCode definito dalla classe <tt>Object</tt> restituisce interi distinti per oggetti distinti. (Questo è tipicamente implementato convertendo l'indirizzo interno dell'oggetto in un intero, ma questa tecnica di implementazione non è richiesta dal linguaggio di programmazione Java<span style="font-size:70%"><sup>TM</sup></span>.) |
| [isAllowAssembly](#isAllowAssembly--) | Imposta l'autorizzazione che consente l'assemblaggio o meno. true consente e false è vietato. |
| [isAllowCopy](#isAllowCopy--) | Imposta l'autorizzazione che consente la copia o meno. true consente e false è vietato. |
| [isAllowDegradedPrinting](#isAllowDegradedPrinting--) | Imposta l'autorizzazione che consente la stampa degradata o meno. true consente e false è vietato. Quando impostata, la stampa sarà limitata a una rappresentazione di basso livello dell'aspetto, possibilmente di qualità degradata. |
| [isAllowFillIn](#isAllowFillIn--) | Imposta l'autorizzazione che consente la compilazione dei moduli o meno. true consente e false è vietato. |
| [isAllowModifyAnnotations](#isAllowModifyAnnotations--) | Imposta l'autorizzazione che consente la modifica delle annotazioni o meno. true consente e false è vietato. |
| [isAllowModifyContents](#isAllowModifyContents--) | Imposta l'autorizzazione che consente la modifica del contenuto o meno. true consente e false è vietato. |
| [isAllowPrint](#isAllowPrint--) | Imposta l'autorizzazione che consente la stampa o meno. true consente e false è vietato. |
| [isAllowScreenReaders](#isAllowScreenReaders--) | Imposta l'autorizzazione che consente i lettori di schermo o meno. true consente e false è vietato. |
| [setAllowAssembly](#setAllowAssembly-boolean-) | Imposta l'autorizzazione che consente l'assemblaggio o meno. true consente e false è vietato. |
| [setAllowCopy](#setAllowCopy-boolean-) | Imposta l'autorizzazione che consente la copia o meno. true consente e false è vietato. |
| [setAllowDegradedPrinting](#setAllowDegradedPrinting-boolean-) | Imposta l'autorizzazione che consente la stampa degradata o meno. true consente e false è vietato. Quando impostata, la stampa sarà limitata a una rappresentazione di basso livello dell'aspetto, possibilmente di qualità degradata. |
| [setAllowFillIn](#setAllowFillIn-boolean-) | Imposta l'autorizzazione che consente la compilazione dei moduli o meno. true consente e false è vietato. |
| [setAllowModifyAnnotations](#setAllowModifyAnnotations-boolean-) | Imposta l'autorizzazione che consente la modifica delle annotazioni o meno. true consente e false è vietato. |
| [setAllowModifyContents](#setAllowModifyContents-boolean-) | Imposta l'autorizzazione che consente la modifica del contenuto o meno. true consente e false è vietato. |
| [setAllowPrint](#setAllowPrint-boolean-) | Imposta l'autorizzazione che consente la stampa o meno. true consente e false è vietato. |
| [setAllowScreenReaders](#setAllowScreenReaders-boolean-) | Imposta l'autorizzazione che consente i lettori di schermo o meno. true consente e false è vietato. |
| [setChangeAllowLevel](#setChangeAllowLevel-int-) | Ottiene e imposta il livello di modifica del privilegio del documento. Come le impostazioni Changes Allowed di Adobe Professional. 0: Nessuno. 1: Inserimento, eliminazione e rotazione delle pagine. 2: Compilazione dei campi modulo e firma dei campi firma esistenti. 3: Commenti, compilazione dei campi modulo e firma dei campi firma esistenti. 4: Qualsiasi operazione tranne l'estrazione delle pagine. Se la proprietà ha valore -1, il livello è indefinito. |
| [setCopyAllowLevel](#setCopyAllowLevel-int-) | Ottiene e imposta il livello di copia del privilegio del documento. Come le impostazioni dei permessi di Adobe Professional. 0: Nessuno. 1: Abilita l'accesso al testo per dispositivi di lettura schermo per ipovedenti. 2: Abilita la copia di testo, immagini e altri contenuti. Se la proprietà ha valore -1, il livello è indefinito. |
| [setPrintAllowLevel](#setPrintAllowLevel-int-) | Ottiene e imposta il livello di stampa del privilegio del documento. Come le impostazioni Printing Allowed di Adobe Professional. 0: Nessuno. 1: Bassa risoluzione (150 dpi). 2: Alta risoluzione. Se la proprietà ha valore -1, il livello è indefinito. |

### compareTo {#compareTo-java.lang.Object-}
Confronta due oggetti {@code DocumentPrivilege}.

### equals {#equals-java.lang.Object-}
Indica se qualche altro oggetto è "uguale a" questo. <p> Il metodo <code>equals</code> implementa una relazione di equivalenza su riferimenti a oggetti non nulli: <ul> <li>È <i>riflessivo</i>: per qualsiasi valore di riferimento non nullo <code>x</code>, <code>x.equals(x)</code> dovrebbe restituire <code>true</code>. <li>È <i>simmetrico</i>: per qualsiasi valore di riferimento non nullo <code>x</code> e <code>y</code>, <code>x.equals(y)</code> dovrebbe restituire <code>true</code> se e solo se <code>y.equals(x)</code> restituisce <code>true</code>. <li>È <i>transitivo</i>: per qualsiasi valore di riferimento non nullo <code>x</code>, <code>y</code> e <code>z</code>, se <code>x.equals(y)</code> restituisce <code>true</code> e <code>y.equals(z)</code> restituisce <code>true</code>, allora <code>x.equals(z)</code> dovrebbe restituire <code>true</code>. <li>È <i>coerente</i>: per qualsiasi valore di riferimento non nullo <code>x</code> e <code>y</code>, più invocazioni di <tt>x.equals(y)</tt> restituiscono costantemente <code>true</code> o costantemente <code>false</code>, a condizione che nessuna informazione usata nei confronti <code>equals</code> sugli oggetti sia modificata. <li>Per qualsiasi valore di riferimento non nullo <code>x</code>, <code>x.equals(null)</code> dovrebbe restituire <code>false</code>. </ul> <p> Il metodo <tt>equals</tt> per la classe <code>Object</code> implementa la relazione di equivalenza più discriminante possibile sugli oggetti; cioè, per qualsiasi valore di riferimento non nullo <code>x</code> e <code>y</code>, questo metodo restituisce <code>true</code> se e solo se <code>x</code> e <code>y</code> si riferiscono allo stesso oggetto (<code>x == y</code> ha valore <code>true</code>). <p> Nota che è generalmente necessario sovrascrivere il metodo <tt>hashCode</tt> ogni volta che questo metodo è sovrascritto, così da mantenere il contratto generale per il metodo <tt>hashCode</tt>, che afferma che gli oggetti uguali devono avere lo stesso codice hash.

### getAllowAll {#getAllowAll--}
```
public static DocumentPrivilege getAllowAll()
```

Tutto consentito.

**Returns:**
Elemento DocumentPrivilege

### getAssembly {#getAssembly--}
```
public static DocumentPrivilege getAssembly()
```

Consente l'assemblaggio del file.

**Returns:**
Elemento DocumentPrivilege

### getChangeAllowLevel {#getChangeAllowLevel--}
```
public final int getChangeAllowLevel()
```

Ottiene e imposta il livello di modifica del privilegio del documento. Come le impostazioni Changes Allowed di Adobe Professional. 0: Nessuno. 1: Inserimento, eliminazione e rotazione delle pagine. 2: Compilazione dei campi modulo e firma dei campi firma esistenti. 3: Commenti, compilazione dei campi modulo e firma dei campi firma esistenti. 4: Qualsiasi operazione tranne l'estrazione delle pagine. Se la proprietà ha valore -1, il livello è indefinito.

**Returns:**
valore int

### getCopy {#getCopy--}
```
public static DocumentPrivilege getCopy()
```

Consente la copia del file.

**Returns:**
Elemento DocumentPrivilege

### getCopyAllowLevel {#getCopyAllowLevel--}
```
public final int getCopyAllowLevel()
```

Ottiene e imposta il livello di copia del privilegio del documento. Come le impostazioni dei permessi di Adobe Professional. 0: Nessuno. 1: Abilita l'accesso al testo per dispositivi di lettura schermo per ipovedenti. 2: Abilita la copia di testo, immagini e altri contenuti. Se la proprietà ha valore -1, il livello è indefinito.

**Returns:**
valore int

### getDegradedPrinting {#getDegradedPrinting--}
```
public static DocumentPrivilege getDegradedPrinting()
```

Consente la stampa degradata.

**Returns:**
Elemento DocumentPrivilege

### getFillIn {#getFillIn--}
```
public static DocumentPrivilege getFillIn()
```

Consente la compilazione dei moduli nel file.

**Returns:**
Elemento DocumentPrivilege

### getForbidAll {#getForbidAll--}
```
public static DocumentPrivilege getForbidAll()
```

Tutto vietato.

**Returns:**
Elemento DocumentPrivilege

### getModifyAnnotations {#getModifyAnnotations--}
```
public static DocumentPrivilege getModifyAnnotations()
```

Consente la modifica delle annotazioni del file.

**Returns:**
Elemento DocumentPrivilege

### getModifyContents {#getModifyContents--}
```
public static DocumentPrivilege getModifyContents()
```

Consente la modifica del file.

**Returns:**
Elemento DocumentPrivilege

### getPrint {#getPrint--}
```
public static DocumentPrivilege getPrint()
```

Consente la stampa del file.

**Returns:**
Elemento DocumentPrivilege

### getPrintAllowLevel {#getPrintAllowLevel--}
```
public final int getPrintAllowLevel()
```

Ottiene e imposta il livello di stampa del privilegio del documento. Come le impostazioni Printing Allowed di Adobe Professional. 0: Nessuno. 1: Bassa risoluzione (150 dpi). 2: Alta risoluzione. Se la proprietà ha valore -1, il livello è indefinito.

**Returns:**
valore int

### getScreenReaders {#getScreenReaders--}
```
public static DocumentPrivilege getScreenReaders()
```

Consente la lettura solo su schermo.

**Returns:**
Elemento DocumentPrivilege

### getValue {#getValue--}
```
public final int getValue()
```



### hashCode {#hashCode--}
```
public int hashCode()
```

Restituisce un valore di codice hash per l'oggetto. Questo metodo è supportato a beneficio delle tabelle hash, come quelle fornite da <code>java.util.Hashtable</code>. <p> Il contratto generale di <code>hashCode</code> è: <ul> <li>Ogni volta che viene invocato sullo stesso oggetto più di una volta durante l'esecuzione di un'applicazione Java, il metodo <tt>hashCode</tt> deve restituire costantemente lo stesso intero, a condizione che nessuna informazione usata nei confronti <tt>equals</tt> sull'oggetto sia modificata. Questo intero non deve rimanere coerente da un'esecuzione dell'applicazione a un'altra esecuzione della stessa applicazione. <li>Se due oggetti sono uguali secondo il metodo <tt>equals(Object)</tt>, allora chiamare il metodo <code>hashCode</code> su ciascuno dei due oggetti deve produrre lo stesso risultato intero. <li>Non è <em>obbligatorio</em> che se due oggetti sono diversi secondo il metodo {@link java.lang.Object#equals(java.lang.Object)}, allora chiamare il metodo <tt>hashCode</tt> su ciascuno dei due oggetti debba produrre risultati interi distinti. Tuttavia, lo sviluppatore dovrebbe essere consapevole che produrre risultati interi distinti per oggetti diversi può migliorare le prestazioni delle tabelle hash. </ul> <p> Per quanto ragionevolmente praticabile, il metodo hashCode definito dalla classe <tt>Object</tt> restituisce interi distinti per oggetti distinti. (Questo è tipicamente implementato convertendo l'indirizzo interno dell'oggetto in un intero, ma questa tecnica di implementazione non è richiesta dal linguaggio di programmazione Java<span style="font-size:70%"><sup>TM</sup></span>.)

**Returns:**
un valore di codice hash per questo oggetto. @see java.lang.Object#equals(java.lang.Object) @see java.util.Hashtable

### isAllowAssembly {#isAllowAssembly--}
```
public boolean isAllowAssembly()
```

Imposta l'autorizzazione che consente l'assemblaggio o meno. true consente e false è vietato.

**Returns:**
valore booleano

### isAllowCopy {#isAllowCopy--}
```
public boolean isAllowCopy()
```

Imposta l'autorizzazione che consente la copia o meno. true consente e false è vietato.

**Returns:**
valore booleano

### isAllowDegradedPrinting {#isAllowDegradedPrinting--}
```
public boolean isAllowDegradedPrinting()
```

Imposta l'autorizzazione che consente la stampa degradata o meno. true consente e false è vietato. Quando impostata, la stampa sarà limitata a una rappresentazione di basso livello dell'aspetto, possibilmente di qualità degradata.

**Returns:**
valore booleano

### isAllowFillIn {#isAllowFillIn--}
```
public boolean isAllowFillIn()
```

Imposta l'autorizzazione che consente la compilazione dei moduli o meno. true consente e false è vietato.

**Returns:**
valore booleano

### isAllowModifyAnnotations {#isAllowModifyAnnotations--}
```
public boolean isAllowModifyAnnotations()
```

Imposta l'autorizzazione che consente la modifica delle annotazioni o meno. true consente e false è vietato.

**Returns:**
valore booleano

### isAllowModifyContents {#isAllowModifyContents--}
```
public boolean isAllowModifyContents()
```

Imposta l'autorizzazione che consente la modifica del contenuto o meno. true consente e false è vietato.

**Returns:**
valore booleano

### isAllowPrint {#isAllowPrint--}
```
public boolean isAllowPrint()
```

Imposta l'autorizzazione che consente la stampa o meno. true consente e false è vietato.

**Returns:**
valore booleano

### isAllowScreenReaders {#isAllowScreenReaders--}
```
public boolean isAllowScreenReaders()
```

Imposta l'autorizzazione che consente i lettori di schermo o meno. true consente e false è vietato.

**Returns:**
valore booleano

### setAllowAssembly {#setAllowAssembly-boolean-}
```
public void setAllowAssembly(boolean value)
```

Imposta l'autorizzazione che consente l'assemblaggio o meno. true consente e false è vietato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setAllowCopy {#setAllowCopy-boolean-}
```
public void setAllowCopy(boolean value)
```

Imposta l'autorizzazione che consente la copia o meno. true consente e false è vietato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setAllowDegradedPrinting {#setAllowDegradedPrinting-boolean-}
```
public void setAllowDegradedPrinting(boolean value)
```

Imposta l'autorizzazione che consente la stampa degradata o meno. true consente e false è vietato. Quando impostata, la stampa sarà limitata a una rappresentazione di basso livello dell'aspetto, possibilmente di qualità degradata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setAllowFillIn {#setAllowFillIn-boolean-}
```
public void setAllowFillIn(boolean value)
```

Imposta l'autorizzazione che consente la compilazione dei moduli o meno. true consente e false è vietato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setAllowModifyAnnotations {#setAllowModifyAnnotations-boolean-}
```
public void setAllowModifyAnnotations(boolean value)
```

Imposta l'autorizzazione che consente la modifica delle annotazioni o meno. true consente e false è vietato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setAllowModifyContents {#setAllowModifyContents-boolean-}
```
public void setAllowModifyContents(boolean value)
```

Imposta l'autorizzazione che consente la modifica del contenuto o meno. true consente e false è vietato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setAllowPrint {#setAllowPrint-boolean-}
```
public void setAllowPrint(boolean value)
```

Imposta l'autorizzazione che consente la stampa o meno. true consente e false è vietato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setAllowScreenReaders {#setAllowScreenReaders-boolean-}
```
public void setAllowScreenReaders(boolean value)
```

Imposta l'autorizzazione che consente i lettori di schermo o meno. true consente e false è vietato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setChangeAllowLevel {#setChangeAllowLevel-int-}
```
public void setChangeAllowLevel(int value)
```

Ottiene e imposta il livello di modifica del privilegio del documento. Come le impostazioni Changes Allowed di Adobe Professional. 0: Nessuno. 1: Inserimento, eliminazione e rotazione delle pagine. 2: Compilazione dei campi modulo e firma dei campi firma esistenti. 3: Commenti, compilazione dei campi modulo e firma dei campi firma esistenti. 4: Qualsiasi operazione tranne l'estrazione delle pagine. Se la proprietà ha valore -1, il livello è indefinito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setCopyAllowLevel {#setCopyAllowLevel-int-}
```
public void setCopyAllowLevel(int value)
```

Ottiene e imposta il livello di copia del privilegio del documento. Come le impostazioni dei permessi di Adobe Professional. 0: Nessuno. 1: Abilita l'accesso al testo per dispositivi di lettura schermo per ipovedenti. 2: Abilita la copia di testo, immagini e altri contenuti. Se la proprietà ha valore -1, il livello è indefinito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setPrintAllowLevel {#setPrintAllowLevel-int-}
```
public void setPrintAllowLevel(int value)
```

Ottiene e imposta il livello di stampa del privilegio del documento. Come le impostazioni Printing Allowed di Adobe Professional. 0: Nessuno. 1: Bassa risoluzione (150 dpi). 2: Alta risoluzione. Se la proprietà ha valore -1, il livello è indefinito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |
