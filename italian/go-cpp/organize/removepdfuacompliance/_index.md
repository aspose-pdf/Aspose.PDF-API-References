---
title: "RemovePdfUaCompliance"
second_title: "Aspose.PDF per Go via C++"
description: "Rimuovi la conformità PDF/UA da un PDF-document."
type: docs
url: /it/go-cpp/organize/removepdfuacompliance/
---

_Rimuovi la conformità PDF/UA da un documento PDF._

```go
func (document *Document) RemovePdfUaCompliance() error
```

**Parameters**: 

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
	// RemovePdfUaCompliance() rimuove la conformità PDF/UA da un documento PDF
	err = pdf.RemovePdfUaCompliance()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) salva il PDF-document precedentemente aperto con un nuovo nome file
	err = pdf.SaveAs("sample_RemovePdfUaCompliance.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
