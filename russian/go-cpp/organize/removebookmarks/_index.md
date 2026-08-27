---
title: "RemoveBookmarks"
second_title: "Aspose.PDF для Go через C++"
description: "Удалить закладки из PDF-документа."
type: docs
url: /ru/go-cpp/organize/removebookmarks/
---

_Удалить закладки из PDF-документа._

```go
func (document *Document) RemoveBookmarks() error
```

**Parameters**: 

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) открывает PDF-документ с именем файла
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() освобождает выделенные ресурсы для PDF-документа
	defer pdf.Close()
	// RemoveBookmarks() удаляет закладки из PDF-документа
	err = pdf.RemoveBookmarks()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
	err = pdf.SaveAs("sample_RemoveBookmarks.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
