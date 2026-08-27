---
title: "Font"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta l'oggetto font."
type: docs
weight: 100
url: /it/python-net/aspose.pdf.text/font/
---

## Font class

Rappresenta l'oggetto font.

Il tipo Font espone i seguenti membri:
## Proprietà
| Nome | Descrizione |
| :- | :- |
| font_name | Ottiene il nome del carattere dell'oggetto [Font](/pdf/python-net/aspose.pdf.text/font/). |
| decoded_font_name | A volte i caratteri PDF (di solito caratteri Cinese/Giapponese/Coreano) possono avere un nome di carattere specifico.<br/>            Questo nome è il valore della proprietà del carattere PDF "BaseFont" e a volte questa proprietà<br/>            può essere rappresentata in forma esadecimale. Se si legge questo nome direttamente potrebbe essere rappresentato<br/>            in forma non leggibile. Per ottenere una forma leggibile è necessario decodificare il nome del carattere secondo<br/>            regole specifiche per questo carattere. <br/>            Questa proprietà restituisce il nome del carattere decodificato, quindi usala nei casi in cui incontri <br/>            un [font_name](/pdf/python-net/aspose.pdf.text/font/) non leggibile.<br/>            Se la proprietà [font_name](/pdf/python-net/aspose.pdf.text/font/) ha una forma leggibile, questa proprietà sarà la stessa di <br/>            [font_name](/pdf/python-net/aspose.pdf.text/font/), così puoi usare questa proprietà in qualsiasi caso in cui tu abbia bisogno di<br/>            ottenere il nome del carattere in una forma leggibile. |
| base_font | Ottiene il valore BaseFont dell'oggetto carattere PDF. Conosciuto anche come nome PostScript del carattere. |
| is_embedded | Ottiene o imposta un valore che indica se il carattere è incorporato.<br/>            I caratteri basati su IFont saranno automaticamente ridotti a sottoinsieme e incorporati |
| is_subset | Ottiene o imposta un valore che indica se il carattere è un sottoinsieme.<br/>             I caratteri basati su IFont saranno automaticamente ridotti a sottoinsieme e incorporati |
| is_accessible | Ottiene indicando se il carattere è presente (installato) nel sistema. |
| font_options | Proprietà utili per regolare il comportamento del font |
## Metodi
| Nome | Descrizione |
| :- | :- |
| get_last_font_embedding_error() | Lo scopo di questo metodo è restituire la descrizione dell'errore se un tentativo<br/>            di incorporare il carattere è fallito. Se non ci sono errori restituisce una stringa vuota. |
| save(stream) | Salva il carattere nel flusso.<br/>            Nota che il carattere viene salvato in formato TTF intermedio destinato a essere usato solo in una copia convertita del documento originale.<br/>            Il file del carattere non è destinato a essere usato al di fuori del contesto del documento originale. |
| measure_string(str, font_size) | Misura la stringa. |

### Vedi anche

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

