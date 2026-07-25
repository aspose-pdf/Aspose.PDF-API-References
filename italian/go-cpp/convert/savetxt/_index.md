---
title: "SaveTxt"
second_title: "Aspose.PDF per Go via C++"
description: "Converti e salva il PDF-document precedentemente aperto come Txt-document."
type: docs
url: /it/go-cpp/convert/savetxt/
---

_Converti e salva il PDF-document precedentemente aperto come Txt-document._

```go
func (document *Document) SaveTxt(filename string) error
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
	// SaveTxt(filename string) salva il PDF-document precedentemente aperto come Txt-document con nome file
	err = pdf.SaveTxt("sample.txt")
	if err != nil {
		log.Fatal(err)
	}
}
```
