---
title: "Split"
second_title: "C++ 経由の Go 用 Aspose.PDF"
description: "現在の PDF ドキュメントからページを抽出して複数の新しい PDF ドキュメントを作成します。"
type: docs
url: /ja/go-cpp/core/split/
---

_現在の PDF ドキュメントからページを抽出して、複数の新しい PDF ドキュメントを作成します。_

```go
func (document *Document) Split(pagerange string) ([]*Document, error)
```

**Parameters**: 
  * **pagerange** - string that defines how to split the PDF-document. Each segment, separated by `;`, specifies the page range for a separate output PDF document. The page range syntax supports individual pages, ranges, and open-ended intervals. For example: "1,3,5;7-10", "-3;4-", or "1;2-3;5-"

**Return**: 
  * **[]\*Document** - slice of new PDF-documents, each containing the pages defined by a corresponding segment of the specified page range
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
	"fmt"
	"github.com/aspose-pdf/aspose-pdf-go-cpp"
	"log"
)

func main() {
	// Open(filename string) は、指定したファイル名の PDF-document を開きます
	pdf_split, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() は、PDF-document に割り当てられたリソースを解放します
	defer pdf_split.Close()

	// Split(pagerange string) は現在の PDF ドキュメントからページを抽出して、複数の新しい PDF ドキュメントを作成します
	pdfs, err := pdf_split.Split("1-2;3;4-")
	if err != nil {
		log.Fatal(err)
	}

	// 分割された各 PDF ドキュメントを別々のファイルとして保存します
	for i, pdf := range pdfs {
		defer pdf.Close()
		filename := fmt.Sprintf("sample_Split_part%d.pdf", i+1)
		// SaveAs(filename string) は以前に開いた PDFドキュメントを新しいファイル名で保存します
		err := pdf.SaveAs(filename)
		if err != nil {
			log.Fatal(err)
		}
	}
}
```
