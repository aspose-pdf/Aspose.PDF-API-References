---
title: "IsPdfaCompliant"
second_title: "Aspose.PDF for Go via C++"
description: "PDF-document'ın PDF/A uyumlu olup olmadığını al."
type: docs
url: /tr/go-cpp/organize/ispdfacompliant/
---

_Get PDF-dokümanının PDF/A uyumlu olduğunu al._

```go
func (document *Document) IsPdfaCompliant() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is PDF/A compliant
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) dosya adıyla bir PDF-belgesi açar
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf.Close()
	// IsPdfaCompliant() PDF-dokümanının PDF/A uyumluluk durumunu alır
	isPdfa, _ := pdf.IsPdfaCompliant()
	if isPdfa {
		fmt.Println("IsPdfaCompliant() is true")
	} else {
		fmt.Println("IsPdfaCompliant() is false")
	}
}
```
