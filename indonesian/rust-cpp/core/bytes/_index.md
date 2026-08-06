---
title: "byte"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengembalikan isi PDF-dokumen sebagai vektor byte."
type: docs
url: /id/rust-cpp/core/bytes/
---

_Mengembalikan isi PDF-dokumen sebagai vektor byte._

```rust
pub fn bytes(&self) -> Result<Vec<u8>, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Vec\<u8\>)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buat dokumen PDF baru
    let pdf = Document::new()?;

    // Kembalikan isi PDF-dokumen sebagai vektor byte
    let data = pdf.bytes()?;

    // Cetak panjang vektor byte
    println!("Length: {}", data.len());

    Ok(())
}

```