---
title: "PageCharacterCount"
second_title: "Aspose.PDF for Go via C++"
description: "PDF-dokümanındaki belirtilen sayfadaki karakter sayısını döndür."
type: docs
url: /tr/go-cpp/core/pagecharactercount/
---

_PDF-document'taki belirtilen sayfada karakter sayısını döndür._

```go
func (document *Document) PageCharacterCount(num int32) (int32, error)
```

**Parameters**: 
  * **num** - page number of the PDF-document

**Return**: 
  * **int32** - character count on the page
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
	// PageCharacterCount(num int32) belirtilen sayfadaki karakter sayısını PDF-document içinde döndürür.
	page_character_count, err := pdf.PageCharacterCount(1)
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Character count on the first page:", page_character_count)
}
```
