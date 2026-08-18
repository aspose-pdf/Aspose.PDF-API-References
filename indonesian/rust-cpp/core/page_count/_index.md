---
title: "page_count"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengembalikan jumlah halaman dalam PDF-document."
type: docs
url: /id/rust-cpp/core/page_count/
---

_Mengembalikan jumlah halaman dalam PDF-document._

```rust
pub fn page_count(&self) -> Result<i32, PdfError>
```

**Arguments**


**Returns**
  * **Ok(i32)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka PDF-document dari file
    let pdf = Document::open("sample.pdf")?;

    // Kembalikan jumlah halaman dalam PDF-document
    let count = pdf.page_count()?;

    // Cetak jumlah halaman
    println!("Count: {}", count);

    Ok(())
}

```