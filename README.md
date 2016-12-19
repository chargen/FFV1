# FFV1 Specification

## Introduction

This repository manages the development of specification documents for FFV1, a lossless intra-frame video codec. Information within this repository should be considered in draft form. The current authoritative specificiation for FFV1 may be found at http://www.ffmpeg.org/~michael/ffv1.html.

## Formatting

The FFV1 specification was iniitally written in lyx. In July 2015 the formatting of the specification was transitioned to Markdown. Propering PDF and HTML rendering has been tested with requires pandoc version 1.13.2.1 and higher.

The Markdown version of the FFV1 specification may also be converted into XML, HTML, and text formats as an IETF RFC draft. Producing the RFC formats requires mmark version 1.3.4 or higher and xml2rfc version 2.5.1 or higher.

A Makefile is provided that can produce the PDF and RFC outputs.
