---
title: "split_at"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Mevcut PDF-document'i iki yeni PDF-document'e böler."
type: docs
url: /tr/rust-cpp/core/split_at/
---

_Mevcut PDF-document'i iki yeni PDF-document'e böler._

```rust
pub fn split_at(&self, page: i32) -> Result<(Self, Self), PdfError>
```

**Arguments**
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

    // Mevcut PDF-document'i iki yeni PDF-document'e böl
    let (left, right) = pdf_split.split_at(2)?;

    // Her bölünmüş parçayı ayrı bir PDF-document olarak kaydet
    left.save_as("sample_split_at_left.pdf")?;
    right.save_as("sample_split_at_right.pdf")?;

    Ok(())
}

```