---
title: "page_character_count"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengembalikan jumlah karakter pada halaman yang ditentukan dalam PDF-dokumen."
type: docs
url: /id/rust-cpp/core/page_character_count/
---

_Mengembalikan jumlah karakter pada halaman yang ditentukan dalam PDF-dokumen._

```rust
pub fn page_character_count(&self) -> Result<i32, PdfError>
```

**Arguments**
  * **num** - the page number (1-based)


**Returns**
  * **Ok(i32)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka PDF-document dari file
    let pdf = Document::open("sample.pdf")?;

    // Tentukan nomor halaman (indeks berbasis 1)
    let page_number = 1;

    // Kembalikan jumlah karakter pada halaman yang ditentukan
    let count = pdf.page_character_count(page_number)?;

    // Cetak jumlah karakter
    println!("Character count on page {}: {}", page_number, count);

    Ok(())
}

```