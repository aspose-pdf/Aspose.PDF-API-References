---
title: "split_at"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Membagi dokumen PDF saat ini menjadi dua dokumen PDF baru."
type: docs
url: /id/rust-cpp/core/split_at/
---

_Membagi dokumen PDF saat ini menjadi dua dokumen PDF baru._

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
    // Buka PDF-document bernama "sample.pdf"
    let pdf_split = Document::open("sample.pdf")?;

    // Bagi dokumen PDF saat ini menjadi dua dokumen PDF baru
    let (left, right) = pdf_split.split_at(2)?;

    // Simpan setiap bagian yang dibagi sebagai PDF-document terpisah
    left.save_as("sample_split_at_left.pdf")?;
    right.save_as("sample_split_at_right.pdf")?;

    Ok(())
}

```