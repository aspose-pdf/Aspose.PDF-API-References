---
title: "split_at_page"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Membagi PDF-document menjadi dua PDF-document baru."
type: docs
url: /id/rust-cpp/core/split_at_page/
---

_Membagi PDF-document menjadi dua PDF-document baru._

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
    // Buka PDF-document bernama "sample.pdf"
    let pdf_split = Document::open("sample.pdf")?;

    // Bagi PDF-document menjadi dua PDF-document baru
    let (left, right) = Document::split_at_page(&pdf_split, 2)?;

    // Simpan setiap bagian yang dibagi sebagai PDF-document terpisah
    left.save_as("sample_split_at_page_left.pdf")?;
    right.save_as("sample_split_at_page_right.pdf")?;

    Ok(())
}

```