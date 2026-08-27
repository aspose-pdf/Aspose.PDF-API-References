---
title: "SaveDocXEnhanced"
second_title: "Aspose.PDF per Go via C++"
description: "Converti e salva il PDF-document precedentemente aperto come DocX-document con Modalità di Riconoscimento Avanzata (tabelle e paragrafi completamente modificabili)."
type: docs
url: /it/go-cpp/convert/savedocxenhanced/
---

_Converti e salva il PDF-document precedentemente aperto come DocX-document con Modalità di Riconoscimento Avanzata (tabelle e paragrafi completamente modificabili)._

```go
func (document *Document) SaveDocXEnhanced(filename string) error
```

**Parameters**: 
  * **filename** - new filename

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) apre un PDF-document con filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per il PDF-document
	defer pdf.Close()
	// SaveDocX(filename string) salva il PDF-document precedentemente aperto come DocX-document in Modalità di Riconoscimento Avanzata con filename
	err = pdf.SaveDocXEnhanced("sampleEnhanced.docx")
	if err != nil {
		log.Fatal(err)
	}
}
```
