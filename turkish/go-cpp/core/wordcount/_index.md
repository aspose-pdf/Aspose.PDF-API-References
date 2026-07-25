---
title: "WordCount"
second_title: "Aspose.PDF for Go via C++"
description: "PDF-dökümanındaki kelime sayısını döndür."
type: docs
url: /tr/go-cpp/core/wordcount/
---

_PDF-dokümanındaki kelime sayısını döndür._

```go
func (document *Document) WordCount() (int32, error)
```

**Parameters**: 

**Return**: 
  * **int32** - word count of the PDF-document
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
	// WordCount() PDF-dokümanındaki kelime sayısını döndürür
	word_count, err := pdf.WordCount()
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Word count:", word_count)
}
```
