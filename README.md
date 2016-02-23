# ZXing .NET

Originally downloaded from http://zxingnet.codeplex.com/

## From the Codeplex site
A library which supports decoding and generating of barcodes (like QR Code, PDF 417, EAN, UPC, Aztec, Data Matrix, Codabar) within images.

The project is a port of the java based barcode reader and generator library ZXing.
https://github.com/zxing/zxing
It has been ported by hand with a lot of optimizations and improvements.

The following barcodes are supported by the decoder:
UPC-A, UPC-E, EAN-8, EAN-13, Code 39, Code 93, Code 128, ITF, Codabar, MSI, RSS-14 (all variants), QR Code, Data Matrix, Aztec and PDF-417.
The encoder supports the following formats:
UPC-A, EAN-8, EAN-13, Code 39, Code 128, ITF, Codabar, Plessey, MSI, QR Code, PDF-417, Aztec, Data Matrix

## Changes in this repo
DPD, a courier in the UK, require their barcodes to switch from subset B to C at specific points, so I've added an encoding hint to manually trigger subset switches
