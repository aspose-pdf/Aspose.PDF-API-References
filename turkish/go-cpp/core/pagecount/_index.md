---
title: "PageCount"
second_title: "Aspose.PDF for Go via C++"
description: "PDF-dokümanındaki sayfa sayısını döndür."
type: docs
url: /tr/go-cpp/core/pagecount/
---

_PDF belgesindeki sayfa sayısını döndür._

```go
func (document *Document) PageCount() (int32, error)
```

**Parameters**: 

**Return**: 
  * **int32** - page count of the PDF-document
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
	// PageCount() PDF belgesindeki sayfa sayısını döndürür
	count, err := pdf.PageCount()
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Count:", count)
}
```
