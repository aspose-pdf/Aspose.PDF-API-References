---
title: "word_count"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengembalikan jumlah kata dalam dokumen PDF."
type: docs
url: /id/rust-cpp/core/word_count/
---

_Mengembalikan jumlah kata dalam dokumen PDF._

```rust
pub fn word_count(&self) -> Result<i32, PdfError>
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

    // Kembalikan jumlah kata dalam dokumen PDF
    let count = pdf.word_count()?;

    // Cetak jumlah kata
    println!("Word count: {}", count);

    Ok(())
}

```