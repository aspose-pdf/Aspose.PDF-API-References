---
title: "page_to_pdf"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengonversi dan menyimpan halaman yang ditentukan sebagai PDF-document."
type: docs
url: /id/rust-cpp/convert/page_to_pdf/
---

_Mengonversi dan menyimpan halaman yang ditentukan sebagai PDF-document._

```rust
pub fn page_to_pdf(&self, num: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Mengonversi dan menyimpan halaman yang ditentukan sebagai PDF-document
    pdf.page_to_pdf(1, "sample_page1.pdf")?;

    Ok(())
}

```