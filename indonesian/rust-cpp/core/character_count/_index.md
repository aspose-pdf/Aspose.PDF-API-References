---
title: "character_count"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengembalikan jumlah karakter dalam PDF-dokumen."
type: docs
url: /id/rust-cpp/core/character_count/
---

_Mengembalikan jumlah karakter dalam PDF-dokumen._

```rust
pub fn character_count(&self) -> Result<i32, PdfError>
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

    // Kembalikan jumlah karakter dalam PDF-dokumen
    let count = pdf.character_count()?;

    // Cetak jumlah karakter
    println!("Character count: {}", count);

    Ok(())
}

```