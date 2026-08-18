---
title: "extract_text"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengembalikan isi dokumen PDF sebagai teks biasa."
type: docs
url: /id/rust-cpp/core/extract_text/
---

_Mengembalikan isi dokumen PDF sebagai teks biasa._

```rust
pub fn extract_text(&self) -> Result<String, PdfError>
```

**Arguments**


**Returns**
  * **Ok(String)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Kembalikan isi dokumen PDF sebagai teks biasa
    let txt = pdf.extract_text()?;

    // Cetak teks yang diekstrak
    println!("Extracted text:\n{}", txt);

    Ok(())
}

```