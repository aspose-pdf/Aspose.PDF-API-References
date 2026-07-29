---
title: "PageCount"
second_title: "Aspose.PDF för Go via C++"
description: "Returnera sidantal i PDF-dokument."
type: docs
url: /sv/go-cpp/core/pagecount/
---

_Returnerar sidantal i PDF-dokumentet._

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
	// Open(filename string) öppnar ett PDF-dokument med filnamn
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() frigör allokerade resurser för PDF-dokument
	defer pdf.Close()
	// PageCount() returnerar sidantal i PDF-dokumentet
	count, err := pdf.PageCount()
	if err != nil {
		log.Fatal(err)
	}
	// Skriv ut
	fmt.Println("Count:", count)
}
```
