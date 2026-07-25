---
title: "PageWordCount"
second_title: "Aspose.PDF for Go via C++"
description: "PDF-dokümanındaki belirtilen sayfadaki kelime sayısını döndür."
type: docs
url: /tr/go-cpp/core/pagewordcount/
---

_PDF-document'taki belirtilen sayfada kelime sayısını döndür._

```go
func (document *Document) PageWordCount(num int32) (int32, error)
```

**Parameters**: 
  * **num** - page number of the PDF-document

**Return**: 
  * **int32** - word count on the page
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
	// PageWordCount(num int32) belirtilen sayfadaki kelime sayısını PDF-document içinde döndürür.
	page_word_count, err := pdf.PageWordCount(1)
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Word count on the first page:", page_word_count)
}
```
