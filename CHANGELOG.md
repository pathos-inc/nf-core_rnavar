# nf-core/rnavar: Changelog

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0dev] nfcore/rnavar

### Added

### Changed

- [#95](https://github.com/nf-core/rnavar/pull/95) - Template update from nf-core/tools 2.5 -> 2.9
- [#97](https://github.com/nf-core/rnavar/pull/97) - Template update from nf-core/tools 2.10

### Fixed

- [#97](https://github.com/nf-core/rnavar/pull/97) - Update all gatk4 modules to disable JVM hotspot

## [1.0.0] nfcore/rnavar - 2022/06/20

First production release of the pipeline with latest software versions.

This version is based on GATK4 best-practices for RNAseq [Ref](https://github.com/gatk-workflows/gatk4-rnaseq-germline-snps-indels) and it includes:

### `Added`

- Added `FastQC v0.11.9` from nf-core modules for read-level QC and summary.
- Added `STAR v2.7.9a` from nf-core modules for read alignment to reference genome.
- Added `Samtools v1.15.1` from nf-core modules for alignment statistics and QC.
- Added `GATK v4.2.6.1` from nf-core modules for alignment post-processing, variant calling and filtration.
- Added `Tabix v1.11` from nf-core modules for indexing BAM ann VCF files.
- Added `SnpEff v5.0` from nf-core modules for variant annotation.
- Added `Ensembl VEP v104.3` from nf-core modules for variant annotation.
- Added `MultiQC v1.12` from nf-core modules for QC summary report.
- Added Scatter i.e., one interval-list into many interval-files to run multiple processes in parallel.

Thanks to everyone that contributed to this release.
Special thanks to @maxulysse and @FriederikeHanssen for your review and valuable suggestions.
