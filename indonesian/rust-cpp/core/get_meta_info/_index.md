---
title: "get_meta_info"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengambil nilai informasi meta dari dokumen PDF."
type: docs
url: /id/rust-cpp/core/get_meta_info/
---

_Mengambil nilai informasi meta dari dokumen PDF._

```rust
pub fn get_meta_info(&self, key: &str) -> Result<String, PdfError>
```

**Arguments**
  * **key** - the key whose value to get

**Returns**
  * **Ok(String)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Dapatkan nilai informasi meta dari dokumen PDF
    let author = pdf.get_meta_info("Author")?;

    // Cetak hasil
    println!("Author: {}", author);

    Ok(())
}

```