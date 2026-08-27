---
title: "ExportXfdf"
second_title: "Aspose.PDF per Go via C++"
description: "Esporta dal PDF-document precedentemente aperto con AcroForm in XFDF-document."
type: docs
url: /it/go-cpp/convert/exportxfdf/
---

_Esporta dal PDF-document precedentemente aperto con AcroForm in documento XFDF._

```go
func (document *Document) ExportXfdf(filename string) error
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
	// ExportXfdf(filename string) esporta dal PDF-document precedentemente aperto con AcroForm in documento XFDF con nome file
	err = pdf.ExportXfdf("sample.xfdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
