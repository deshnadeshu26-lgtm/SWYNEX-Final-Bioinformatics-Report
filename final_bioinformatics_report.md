# SWYNEX Technologies
# Final Bioinformatics Report

**Intern:** Deshna  
**Internship Domain:** Bioinformatics  
**Task:** Final Bioinformatics Report  
**Tools Used:** Python, Pandas, Google Colab

## 1. Research Question

How can Python-based data cleaning and statistical analysis help improve the quality and understanding of biological datasets?

## 2. Methods

A small sample biological dataset was created for practice using Python and Pandas.

The following steps were performed:

1. Loaded the sample dataset into a Pandas DataFrame.
2. Examined the dataset structure and column information.
3. Identified missing values and duplicate records.
4. Removed duplicate records.
5. Replaced missing numerical values with the median of their respective columns.
6. Generated descriptive statistics using the `describe()` function.
7. Saved the cleaned dataset as a CSV file.

## 3. Results

The original sample dataset contained 6 records and 4 columns.

- Missing values identified: 2
- Duplicate records identified: 1
- Records remaining after cleaning: 5
- Missing values after cleaning: 0
- Duplicate records after cleaning: 0

### Statistical Summary

| Parameter | Gene Expression | GC Content (%) |
|---|---:|---:|
| Mean | 12.98 | 44.39 |
| Minimum | 9.80 | 42.80 |
| Maximum | 15.20 | 46.10 |
| Median | 13.30 | 44.35 |

The cleaning process removed duplicate records and handled missing numerical values successfully.

## 4. Limitations

- The dataset was a small practice dataset and not an experimentally validated biological dataset.
- The limited number of records may not represent real biological variation.
- Median imputation may not preserve the original biological distribution.
- Further validation using authentic biological datasets is required.

## 5. References

1. Pandas Documentation: https://pandas.pydata.org/docs/
2. Python Documentation: https://docs.python.org/3/
3. Google Colab: https://colab.research.google.com/

## Conclusion

This practice exercise provided an introduction to data cleaning and statistical analysis using Python. It demonstrated how missing values and duplicate records can be handled to improve dataset quality. The exercise strengthened my understanding of data preprocessing and basic bioinformatics workflows.

**Intern:** Deshna  
**Organization:** SWYNEX Technologies
