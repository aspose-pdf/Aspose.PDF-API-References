---
title: "Enum AnnotationFlags"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Enum Aspose.Pdf.Annotations.AnnotationFlags. Un insieme di flag che specificano varie caratteristiche dell'annotazione"
type: docs
weight: 1530
url: /it/net/aspose.pdf.annotations/annotationflags/
---
## AnnotationFlags enumeration

Un insieme di flag che specificano varie caratteristiche dell'annotazione.

```csharp
[Flags]
public enum AnnotationFlags
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Default | `0` | Valore predefinito. |
| Invisible | `1` | Se impostato, non visualizzare l'annotazione se non appartiene a uno dei tipi di annotazione standard e non è disponibile alcun gestore di annotazioni. Se non impostato, visualizzare tale annotazione sconosciuta utilizzando un flusso di aspetto specificato dal suo dizionario di aspetto, se presente. |
| Hidden | `2` | Se impostato, non visualizzare né stampare l'annotazione né consentirne l'interazione con l'utente, indipendentemente dal tipo di annotazione o dalla disponibilità di un gestore di annotazioni. Nei casi in cui lo spazio sullo schermo è limitato, la possibilità di nascondere e mostrare selettivamente le annotazioni può essere usata in combinazione con i flussi di aspetto per visualizzare informazioni ausiliarie a comparsa simili, per funzione, ai sistemi di aiuto online. |
| Print | `4` | Se impostato, stampare l'annotazione quando la pagina viene stampata. Se non impostato, non stampare mai l'annotazione, indipendentemente dal fatto che sia visualizzata sullo schermo. Questo può essere utile, ad esempio, per annotazioni che rappresentano pulsanti interattivi, i quali non avrebbero alcun scopo significativo sulla pagina stampata. |
| NoZoom | `8` | Se impostato, non scalare l'aspetto dell'annotazione per corrispondere all'ingrandimento della pagina. La posizione dell'annotazione sulla pagina (definita dall'angolo superiore sinistro del suo rettangolo di annotazione) rimane fissa, indipendentemente dall'ingrandimento della pagina. |
| NoRotate | `10` | Se impostato, non ruotare l'aspetto dell'annotazione per corrispondere alla rotazione della pagina. L'angolo superiore sinistro del rettangolo di annotazione rimane in una posizione fissa sulla pagina, indipendentemente dalla rotazione della pagina. |
| NoView | `20` | Se impostato, non visualizzare l'annotazione sullo schermo né consentirne l'interazione con l'utente. L'annotazione può essere stampata (a seconda dell'impostazione del flag Print) ma dovrebbe essere considerata nascosta ai fini della visualizzazione su schermo e dell'interazione dell'utente. |
| ReadOnly | `40` | Se impostato, non consentire all'annotazione di interagire con l'utente. L'annotazione può essere visualizzata o stampata (a seconda delle impostazioni dei flag NoView e Print) ma non dovrebbe rispondere ai clic del mouse né modificare il proprio aspetto in risposta ai movimenti del mouse. Questo flag è ignorato per le annotazioni widget; la sua funzione è inglobata dal flag ReadOnly del campo modulo associato. |
| Locked | `80` | Se impostato, non consentire che l'annotazione venga eliminata o che le sue proprietà (inclusi posizione e dimensione) vengano modificate dall'utente. Tuttavia, questo flag non limita le modifiche al contenuto dell'annotazione, come il valore di un campo modulo. |
| ToggleNoView | `100` | Se impostato, inverte l'interpretazione del flag NoView per determinati eventi. Un uso tipico è avere un'annotazione che appare solo quando il cursore del mouse è posizionato sopra di essa. |
| LockedContents | `200` | Se impostato, non consentire che il contenuto dell'annotazione venga modificato dall'utente. Questo flag non limita l'eliminazione dell'annotazione o le modifiche ad altre proprietà dell'annotazione, come posizione e dimensione. |

### Vedi anche

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


