---
title: "ExtractText"
second_title: "Aspose.PDF for Go via C++"
description: "PDF-dökümanının içeriğini düz metin olarak döndür."
type: docs
url: /tr/go-cpp/core/extracttext/
---

_PDF-document içeriğini düz metin olarak döndür._

```go
func (document *Document) ExtractText() (string, error)
```

**Parameters**: 

**Return**: 
  * **string** - PDF-document contents as plain text
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
	// ExtractText() PDF-document içeriğini düz metin olarak döndürür
	txt, err := pdf.ExtractText()
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Extracted text:\n", txt)
}
```
