---
title: "AnnotationFlags"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Un insieme di flag che specificano varie caratteristiche dell'annotazione."
type: docs
weight: 930
url: /it/python-net/aspose.pdf.annotations/annotationflags/
---

## AnnotationFlags enumeration

Un insieme di flag che specificano varie caratteristiche dell'annotazione.

## Members
| Nome membro | Descrizione |
| :- | :- |
| DEFAULT | Valore predefinito. |
| INVISIBLE | Se impostato, non visualizzare l'annotazione se non appartiene a uno dei tipi di annotazione standard<br/>            e non è disponibile alcun gestore di annotazioni. Se non impostato, visualizzare tale annotazione sconosciuta<br/>            utilizzando un flusso di aspetto specificato dal suo dizionario di aspetto, se presente. |
| HIDDEN | Se impostato, non visualizzare né stampare l'annotazione né consentirne l'interazione con l'utente,<br/>            indipendentemente dal tipo di annotazione o dalla disponibilità di un gestore di annotazioni.<br/>            Nei casi in cui lo spazio sullo schermo è limitato, la possibilità di nascondere e mostrare le annotazioni in modo selettivo<br/>            può essere usata in combinazione con i flussi di aspetto per visualizzare informazioni ausiliarie a comparsa<br/>            simili per funzione ai sistemi di aiuto online. |
| STAMPA | Se impostato, stampare l'annotazione quando la pagina viene stampata. Se non impostato, non stampare mai l'annotazione,<br/>            indipendentemente dal fatto che sia visualizzata sullo schermo. Questo può essere utile, ad esempio, per annotazioni<br/>            che rappresentano pulsanti interattivi, i quali non avrebbero alcuno scopo significativo sulla pagina stampata. |
| NO_ZOOM | Se impostato, non ridimensionare l'aspetto dell'annotazione per corrispondere all'ingrandimento della pagina.<br/>            La posizione dell'annotazione sulla pagina (definita dall'angolo superiore sinistro del suo rettangolo di annotazione)<br/>            rimane fissa, indipendentemente dall'ingrandimento della pagina. |
| NO_ROTATE | Se impostato, non ruotare l'aspetto dell'annotazione per corrispondere alla rotazione della pagina.<br/>            L'angolo superiore sinistro del rettangolo dell'annotazione rimane in una posizione fissa sulla pagina,<br/>            indipendentemente dalla rotazione della pagina. |
| NO_VIEW | Se impostato, non visualizzare l'annotazione sullo schermo né consentirne l'interazione con l'utente.<br/>            L'annotazione può essere stampata (a seconda dell'impostazione del flag Print)<br/>            ma dovrebbe essere considerata nascosta ai fini della visualizzazione su schermo e dell'interazione dell'utente. |
| READ_ONLY | Se impostato, non consentire all'annotazione di interagire con l'utente. L'annotazione può essere visualizzata<br/>            o stampata (a seconda delle impostazioni dei flag NoView e Print) ma non dovrebbe rispondere ai click del mouse<br/>            o modificare il proprio aspetto in risposta ai movimenti del mouse. Questo flag è ignorato per le annotazioni widget;<br/>            la sua funzione è assorbita dal flag ReadOnly del campo modulo associato. |
| LOCKED | Se impostato, non consentire che l'annotazione venga eliminata o che le sue proprietà (inclusi posizione e dimensione)<br/>            vengano modificate dall'utente. Tuttavia, questo flag non limita le modifiche al contenuto dell'annotazione,<br/>            come il valore di un campo modulo. |
| TOGGLE_NO_VIEW | Se impostato, inverte l'interpretazione del flag NoView per alcuni eventi.<br/>            Un uso tipico è avere un'annotazione che appare solo quando il cursore del mouse è tenuto sopra di essa. |
| LOCKED_CONTENTS | Se impostato, non consente che il contenuto dell'annotazione venga modificato dall'utente.<br/>            Questo flag non limita l'eliminazione dell'annotazione o le modifiche ad altre proprietà dell'annotazione,<br/>            come posizione e dimensione. |

### Vedi anche

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

