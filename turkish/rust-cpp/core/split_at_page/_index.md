---
title: "split_at_page"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-document'i iki yeni PDF-document'e böler."
type: docs
url: /tr/rust-cpp/core/split_at_page/
---

_PDF-document'i iki yeni PDF-document'e böler._

```rust
pub fn split_at_page(document: &Document, page: i32) -> Result<(Self, Self), PdfError>
```

**Arguments**
  * **document** - a reference to the source PDF-document to split
  * **page** - a page number at which to split (1-based, exclusive for the second part)

**Returns**
  * **Ok((Self, Self))** - with the two split documents, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // "sample.pdf" adlı bir PDF-document aç
    let pdf_split = Document::open("sample.pdf")?;

    // PDF-document'i iki yeni PDF-document'e böl
    let (left, right) = Document::split_at_page(&pdf_split, 2)?;

    // Her bölünmüş parçayı ayrı bir PDF-document olarak kaydet
    left.save_as("sample_split_at_page_left.pdf")?;
    right.save_as("sample_split_at_page_right.pdf")?;

    Ok(())
}

```