---
title: "PageCount"
second_title: "Aspose.PDF pour Go via C++"
description: "Retourner le nombre de pages du PDF-document."
type: docs
url: /fr/go-cpp/core/pagecount/
---

_Renvoie le nombre de pages dans le PDF-document._

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
	// Open(filename string) ouvre un PDF-document avec filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libère les ressources allouées pour le PDF-document
	defer pdf.Close()
	// PageCount() renvoie le nombre de pages dans le PDF-document
	count, err := pdf.PageCount()
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Count:", count)
}
```
