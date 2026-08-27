---
title: "ClearMetaInfo"
second_title: "Aspose.PDF per Go via C++"
description: "Cancella tutti i valori delle informazioni meta del documento PDF."
type: docs
url: /it/go-cpp/core/clearmetainfo/
---

_Cancella tutti i valori delle informazioni meta del documento PDF._

```go
func (document *Document) ClearMetaInfo() error
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
	// ClearMetaInfo() cancella tutti i valori delle informazioni meta del documento PDF
	err = pdf.ClearMetaInfo()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) salva il PDF-document precedentemente aperto con un nuovo nome file
	err = pdf.SaveAs("sample_ClearMetaInfo.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
