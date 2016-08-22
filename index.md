---
layout: home
---

# What is the import wrapper?

The import wrapper is a command-line tool that helps package a set of pipeline data for easy import into cBioPortal. it creates all the various meta files, and makes sure that everything is packaged correctly. It also takes care of merging a large block of VCF files into a single MAF file with the correct columns for the portal.

## Dependencies

 * Perl with a decently large number of modules
 * tabix
 * The Ensembl variant effect predictor
