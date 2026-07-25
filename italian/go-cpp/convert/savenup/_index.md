---
title: "SaveNUp"
second_title: "Aspose.PDF per Go via C++"
description: "Converti e salva il PDF-document precedentemente aperto come PDF-document N-Up."
type: docs
url: /it/go-cpp/convert/savenup/
---

_Converti e salva il PDF-document precedentemente aperto come N-Up PDF-document._

```go
func (document *Document) SaveNUp(filename string, columns int32, rows int32) error
```

**Parameters**: 
  * **filename** - new filename
  * **columns** - number of columns
  * **rows** - number of rows

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
	// SaveNUp(filename string, columns int32, rows int32) salva il PDF-document precedentemente aperto come N-Up PDF-document con nome file
	err = pdf.SaveNUp("sample_NUp.pdf", 2, 2)
	if err != nil {
		log.Fatal(err)
	}
}
```
