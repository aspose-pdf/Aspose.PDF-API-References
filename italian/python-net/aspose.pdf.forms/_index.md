---
title: "aspose.pdf.forms"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Lo spazio dei nomi aspose.pdf.forms contiene classi che descrivono i moduli (standard, statici, dinamici) e vari tipi di campi come casella di testo, casella di riepilogo, pulsante radio ecc."
type: docs
weight: 60
url: /it/python-net/aspose.pdf.forms/
---


Lo spazio dei nomi aspose.pdf.forms contiene classi che descrivono i moduli (standard, statici, dinamici) e vari tipi di campi come casella di testo, casella di riepilogo, pulsante radio ecc.

## Classi
| Classe | Descrizione |
| :- | :- |
| [BarcodeField](/pdf/python-net/aspose.pdf.forms/barcodefield/) | La classe rappresenta un campo barcode. |
| [ButtonField](/pdf/python-net/aspose.pdf.forms/buttonfield/) | La classe rappresenta un campo pulsante. |
| [CheckboxField](/pdf/python-net/aspose.pdf.forms/checkboxfield/) | Classe che rappresenta un campo di tipo checkbox |
| [ChoiceField](/pdf/python-net/aspose.pdf.forms/choicefield/) | Rappresenta la classe base per i campi di scelta. |
| [ComboBoxField](/pdf/python-net/aspose.pdf.forms/comboboxfield/) | Classe che rappresenta un campo Combobox del modulo. |
| [DateField](/pdf/python-net/aspose.pdf.forms/datefield/) | Campo data con visualizzazione calendario. |
| [DocMDPSignature](/pdf/python-net/aspose.pdf.forms/docmdpsignature/) | Rappresenta la classe del tipo di firma MDP (rilevamento e prevenzione delle modifiche) del documento. |
| [ExternalSignature](/pdf/python-net/aspose.pdf.forms/externalsignature/) | Crea una firma PKCS#7Detached separata utilizzando un X509Certificate2. Supporta smartcard usb, token senza chiavi private esportabili. |
| [Field](/pdf/python-net/aspose.pdf.forms/field/) | Classe base per i campi del modulo acro. |
| [FileSelectBoxField](/pdf/python-net/aspose.pdf.forms/fileselectboxfield/) | Campo per l'elemento di selezione file. |
| [Form](/pdf/python-net/aspose.pdf.forms/form/) | Classe che rappresenta l'oggetto modulo. |
| [IconFit](/pdf/python-net/aspose.pdf.forms/iconfit/) | Descrive come l'icona dell'annotazione widget deve essere visualizzata all'interno del suo rettangolo di annotazione. |
| [ListBoxField](/pdf/python-net/aspose.pdf.forms/listboxfield/) | Classe che rappresenta il campo ListBox. |
| [NumberField](/pdf/python-net/aspose.pdf.forms/numberfield/) | Campo di testo con caratteri validi specificati |
| [Option](/pdf/python-net/aspose.pdf.forms/option/) | Classe che rappresenta l'opzione del campo di scelta. |
| [OptionCollection](/pdf/python-net/aspose.pdf.forms/optioncollection/) | Classe che rappresenta la raccolta di opzioni del campo di scelta. |
| [PKCS1](/pdf/python-net/aspose.pdf.forms/pkcs1/) | Rappresenta l'oggetto firma relativo allo standard PKCS#1.<br/>            L'algoritmo di crittografia RSA e il metodo di digest SHA-1 sono utilizzati per la firma. |
| [PKCS7](/pdf/python-net/aspose.pdf.forms/pkcs7/) | Rappresenta l'oggetto PKCS#7 conforme alla specifica PKCS#7 nell'Internet RFC 2315, <br/>            PKCS #7: Cryptographic Message Syntax, Versione 1.5.<br/>            Il digest SHA1 dell'intervallo di byte del documento è incapsulato nel campo PKCS#7 SignedData. |
| [PKCS7Detached](/pdf/python-net/aspose.pdf.forms/pkcs7detached/) | Rappresenta l'oggetto PKCS#7 conforme alla specifica PKCS#7 nell'Internet RFC 2315, <br/>            PKCS #7: Cryptographic Message Syntax, Versione 1.5.<br/>            Il digest originale del messaggio firmato sull'intervallo di byte del documento è incorporato come campo PKCS#7 SignedData normale. <br/>            Nessun dato è incapsulato nel campo PKCS#7 SignedData. |
| [PasswordBoxField](/pdf/python-net/aspose.pdf.forms/passwordboxfield/) | Classe che descrive il campo di testo per l'inserimento della password. |
| [RadioButtonField](/pdf/python-net/aspose.pdf.forms/radiobuttonfield/) | Classe che rappresenta il campo pulsante radio. |
| [RadioButtonOptionField](/pdf/python-net/aspose.pdf.forms/radiobuttonoptionfield/) | Classe che rappresenta l'elemento del campo RadioButton. |
| [RichTextBoxField](/pdf/python-net/aspose.pdf.forms/richtextboxfield/) | Classe che descrive il componente editor di testo avanzato. |
| [Signature](/pdf/python-net/aspose.pdf.forms/signature/) | Una classe astratta che rappresenta l'oggetto firma nel documento pdf. <br/>            Le firme sono campi con valori di oggetti firma, quest'ultimo contiene dati utilizzati per<br/>            verificare la validità del documento. |
| [SignatureCustomAppearance](/pdf/python-net/aspose.pdf.forms/signaturecustomappearance/) | Una classe astratta che rappresenta l'oggetto aspetto personalizzato della firma. |
| [SignatureField](/pdf/python-net/aspose.pdf.forms/signaturefield/) | Rappresenta il campo modulo firma. |
| [TextBoxField](/pdf/python-net/aspose.pdf.forms/textboxfield/) | Classe che rappresenta il campo casella di testo. |
| [XFA](/pdf/python-net/aspose.pdf.forms/xfa/) | Rappresenta il modulo XML relativo all'XML Forms Architecture (XFA). |
## Enumerazioni
| Enumerazione | Descrizione |
| :- | :- |
| [BoxStyle](/pdf/python-net/aspose.pdf.forms/boxstyle/) | Rappresenta gli stili della casella di controllo. |
| [DocMDPAccessPermissions](/pdf/python-net/aspose.pdf.forms/docmdpaccesspermissions/) | Le autorizzazioni di accesso concesse per questo documento.<br/>            I valori validi sono:<br/>            1 - Non sono consentite modifiche al documento; qualsiasi modifica al documento invalida la firma.<br/>            2 - Le modifiche consentite sono la compilazione dei moduli, l'istanziazione di modelli di pagina e la firma; altre modifiche invalidano la firma.<br/>            3 - Le modifiche consentite sono le stesse della voce 2, oltre alla creazione, eliminazione e modifica di annotazioni; altre modifiche invalidano la firma. |
| [FormType](/pdf/python-net/aspose.pdf.forms/formtype/) | Enumerazione dei possibili tipi di Acro Form. |
| [IconCaptionPosition](/pdf/python-net/aspose.pdf.forms/iconcaptionposition/) | Descrive la posizione dell'icona. |
| [ScalingMode](/pdf/python-net/aspose.pdf.forms/scalingmode/) | Il tipo di ridimensionamento da utilizzare. |
| [ScalingReason](/pdf/python-net/aspose.pdf.forms/scalingreason/) | Le circostanze in cui l'icona deve essere ridimensionata all'interno del rettangolo di annotazione. |
| [SubjectNameElements](/pdf/python-net/aspose.pdf.forms/subjectnameelements/) | L'enumerazione descrive gli elementi nella stringa dell'oggetto della firma. |
| [Symbology](/pdf/python-net/aspose.pdf.forms/symbology/) | Una simbologia (Barcode) definisce i dettagli tecnici di un particolare tipo di codice a barre:<br/>            la larghezza delle barre, il set di caratteri, il metodo di codifica, le specifiche del checksum, ecc. |
