---
title: "WordCount"
second_title: "Aspose.PDF für Go über C++"
description: "Wortanzahl im PDF-Dokument zurückgeben."
type: docs
url: /de/go-cpp/core/wordcount/
---

_Gibt die Wortanzahl im PDF-Dokument zurück._

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
	// Open(filename string) öffnet ein PDF-document mit Dateiname
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() gibt zugewiesene Ressourcen für PDF-document frei
	defer pdf.Close()
	// WordCount() gibt die Wortanzahl im PDF-Dokument zurück
	word_count, err := pdf.WordCount()
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Word count:", word_count)
}
```
