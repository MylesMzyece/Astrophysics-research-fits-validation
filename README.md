# Astrophysics-research-fits-validation

## Overview

This repository contains Python code developed as part of my undergraduate research project in astronomy and astrophysics. The goal is to validate WISE (Wide-field Infrared Survey Explorer) FITS image files against their corresponding TXT database records.  

The tasks completed include:

1. **Matching FITS filenames to TXT records**  
   - Extracts date and filter information from human-created FITS filenames.  
   - Compares this information to the TXT records.  

2. **Reading FITS headers**  
   - Reads `DATE` and `NUMFRMS` (number of subframes) from FITS headers.  

3. **Comparing FITS headers to TXT records**  
   - Checks if `DATE` matches `date_obs` in TXT.  
   - Checks if `NUMFRMS` matches the corresponding TXT field.  
   - Reports mismatches.  

4. **Automation**  
   - Loops over all FITS and TXT files in a folder and prints a summary of results.
