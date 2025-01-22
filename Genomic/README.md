# Mock Genomic Submission Files

The files in this directory will mimic a genomic data submission to CRDC.

## Directory Contents
*datafiles* - The files in this directory are mock .bam and .bai files.  These files will be uploaded to CRDC using the CLI Upload Tool.

*loadsheets* - These are the CRDC submission metadata load sheets that are examples of what submitters create as part of their data submission.  These files can be submitted via the graphical interface, the CLI Upload Tool, or the Submission APIs

**Note:** Some of these load sheets have errors so that you can see how the system behaves with incorrect information.  It is recommended that you upload files with **error** in the file name to see how the Submission Portal manages errors.  Then replace the **error** files with the **correct** files for the same node.

- **file_error.csv** - This file contaains multiple errors in the file node.
- **file_correct.csv** - This file contains the correct information for the file node and can act as a file manifest.
- **genomic_info_error.csv** - This file will introduce errors specific to the genomic_info node
- **genomic_info_correct.csv** - This file is correct and will pass validation.
- **participant.csv**
- **program.csv**
- **sample.csv**
- **study_error.csv** - This file has errors specific to the study node
- **study_correct** - This file will correctly pass validaiton
- **treatment.csv**
