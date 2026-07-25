---
title: "ExportFdf"
second_title: "Aspose.PDF per Go via C++"
description: "Esporta dal PDF-document precedentemente aperto con AcroForm in FDF-document."
type: docs
url: /it/go-cpp/convert/exportfdf/
---

_Esporta dal PDF-document precedentemente aperto con AcroForm a documento FDF._

```go
func (document *Document) ExportFdf(filename string) error
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
	// ExportFdf(filename string) esporta dal PDF-document precedentemente aperto con AcroForm a documento FDF con il nome file
	err = pdf.ExportFdf("sample.fdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
