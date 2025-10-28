# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Repository Overview

This is an academic literature repository containing research papers and working documents focused on racial inequality, labor markets, discrimination, and organizational stratification. The repository contains approximately 279 files, primarily PDFs of academic papers and Word documents for manuscript drafts.

## Repository Purpose

This repository serves as a centralized reference library for research on:
- Racial discrimination in labor markets and organizations
- Wage inequality and segregation across firms
- Employer-employee matched data analysis
- Organizational reproduction of inequality
- Labor market stratification and segmentation

## Key Documents

The primary working manuscript is located in:
- `01_intro_white firms_092425.docx` - Main manuscript introduction
- `01_intro_white firms_092425 copy.docx` - Backup copy

## File Organization

All files are stored in the root directory with a consistent naming convention:
- Academic papers: `[author] [year] [title].pdf`
- Annotated versions include `(marked)` or `(clean)` suffixes
- Working manuscripts use descriptive names with dates

## Working with This Repository

Since this is a literature repository without code, typical development commands (build, test, lint) are not applicable. Instead:

### File Management
```bash
# Find papers by author
ls -1 | grep -i "[author name]"

# Find papers by topic keywords
ls -1 | grep -i "[keyword]"

# Count total papers
ls -1 *.pdf | wc -l
```

### Version Control
```bash
# View recent document changes
git --no-pager log --oneline

# Check which documents were modified
git --no-pager status
```

## Architecture Notes

This is a flat-file academic literature repository:
- No hierarchical directory structure
- No code or data analysis files
- Version control tracks document updates and additions to the literature collection
- Focus is on research synthesis rather than software development
