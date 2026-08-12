---
title: "IsSigned"
second_title: "Aspose.PDF for Go via C++"
description: "PDF-dokümanının imzalı durumunu al."
type: docs
url: /tr/go-cpp/security/issigned/
---

_PDF-dökümanının imzalı durumunu al._

```go
func (document *Document) IsSigned() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is signed
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) dosya adıyla bir PDF-belgesi açar
	pdf, err := asposepdf.Open("sample_with_sign.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf.Close()
	// IsSigned() PDF-dökümanının imzalı durumunu alır
	isSig, _ := pdf.IsSigned()
	if isSig {
		fmt.Println("IsSigned() is true")
	}
}
```
