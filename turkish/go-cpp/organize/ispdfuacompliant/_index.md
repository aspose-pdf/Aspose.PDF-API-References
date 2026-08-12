---
title: "IsPdfUaCompliant"
second_title: "Aspose.PDF for Go via C++"
description: "PDF-document'ın PDF/UA uyumlu olup olmadığını al."
type: docs
url: /tr/go-cpp/organize/ispdfuacompliant/
---

_PDF-belgesi PDF/UA uyumlu._

```go
func (document *Document) IsPdfUaCompliant() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is PDF/UA compliant
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
	// IsPdfUaCompliant() PDF-belgenin PDF/UA uyumluluk durumunu alır
	isPdfua, _ := pdf.IsPdfUaCompliant()
	if isPdfua {
		fmt.Println("IsPdfUaCompliant() is true")
	} else {
		fmt.Println("IsPdfUaCompliant() is false")
	}
}
```
