---
title: "page_is_blank"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Kembalikan apakah halaman kosong dalam dokumen PDF."
type: docs
url: /id/rust-cpp/core/page_is_blank/
---

_Halaman kembali kosong dalam dokumen PDF._

```rust
pub fn page_is_blank(&self, num: i32) -> Result<bool, PdfError>
```

**Arguments**
  * **num** - the page number (1-based)


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka PDF-document dari file
    let pdf = Document::open("sample.pdf")?;

    // Tentukan nomor halaman (indeks berbasis 1)
    let page_number = 1;

    // Halaman kembali kosong dalam dokumen PDF
    let is_blank = pdf.page_is_blank(page_number)?;

    // Cetak jika halaman yang ditentukan kosong
    println!("Is page {} blank? {}", page_number, is_blank);

    Ok(())
}

```