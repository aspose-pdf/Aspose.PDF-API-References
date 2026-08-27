---
title: "PageMergeLayers"
second_title: "Aspose.PDF per Go via C++"
description: "Unisci tutti i livelli nella pagina in un unico livello con il nome del nuovo livello specificato."
type: docs
url: /it/go-cpp/organize/pagemergelayers/
---

_Unisci tutti i livelli nella pagina in un unico livello con il nome del nuovo livello specificato._

```go
func (document *Document) PageMergeLayers(num int32, newLayerName string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **newLayerName** - name of the new layer after merging

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
	// PageMergeLayers(num int32, newLayerName string) unisce tutti i livelli nella pagina in un unico livello con il nome del nuovo livello specificato
	err = pdf.PageMergeLayers(1, "newLayerName")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) salva il PDF-document precedentemente aperto con un nuovo nome file
	err = pdf.SaveAs("sample_PageMergeLayers.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
