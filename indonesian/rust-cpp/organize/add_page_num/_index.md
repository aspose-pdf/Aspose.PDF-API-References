---
title: "add_page_num"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menambahkan nomor halaman ke PDF-document."
type: docs
url: /id/rust-cpp/organize/add_page_num/
---

_Menambahkan nomor halaman ke PDF-document._

```rust
pub fn add_page_num(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Tambahkan nomor halaman ke PDF-document
    pdf.add_page_num()?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_add_page_num.pdf")?;

    Ok(())
}

```