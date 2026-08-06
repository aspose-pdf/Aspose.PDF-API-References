---
title: "tentang"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengembalikan informasi metadata tentang Aspose.PDF untuk Rust melalui C++."
type: docs
url: /id/rust-cpp/miscellaneous/about/
---

_Mengembalikan informasi metadata tentang Aspose.PDF untuk Rust melalui C++._

```rust
pub fn about(&self) -> Result<ProductInfo, PdfError>
```

**Arguments**


**Returns**
  * **Ok(ProductInfo)** - if the operation succeeds
```rust
#[derive(Debug, Deserialize)]
pub struct ProductInfo {
    #[serde(rename = "product")]
    pub product: String,

    #[serde(rename = "family")]
    pub family: String,

    #[serde(rename = "version")]
    pub version: String,

    #[serde(rename = "releasedate")]
    pub release_date: String,

    #[serde(rename = "producer")]
    pub producer: String,

    #[serde(rename = "islicensed")]
    pub is_licensed: bool,
}
```

  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buat dokumen PDF baru
    let pdf = Document::new()?;

    // Mengembalikan informasi metadata tentang Aspose.PDF untuk Go melalui C++.
    let info = pdf.about()?;

    // Cetak bidang metadata
    println!("Product Info:");
    println!("  Product:      {}", info.product);
    println!("  Family:       {}", info.family);
    println!("  Version:      {}", info.version);
    println!("  ReleaseDate:  {}", info.release_date);
    println!("  Producer:     {}", info.producer);
    println!("  IsLicensed:   {}", info.is_licensed);

    Ok(())
}

```