---
title: "ExportXml"
second_title: "Aspose.PDF per Go via C++"
description: "Esporta dal PDF-document precedentemente aperto con AcroForm in XML-document."
type: docs
url: /it/go-cpp/convert/exportxml/
---

_Esporta dal PDF-document precedentemente aperto con AcroForm a XML-document._

```go
func (document *Document) ExportXml(filename string) error
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
	// ExportXml(filename string) esporta dal PDF-document precedentemente aperto con AcroForm a XML-document con filename
	err = pdf.ExportXml("sample.xml")
	if err != nil {
		log.Fatal(err)
	}
}
```
