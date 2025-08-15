# In progress Project

this project is about to use NPL tools to extract people realtionships in novel "Pride and Prejudice".

## How to run

The project already includes pyproject.toml. It is recommended to use uv to manage virtual environments and dependencies.
## Input file:
42671.txt: Original novel text

characters.csv: Manually compiled Knowledge Base (QID, Standard Name and Alias/including title)
## Running sequence:
1) pre-process.py
Product: clean_book.txt
2) main1.py
Product
consolidated_relationships.csv
3) post-processing.py
relationships_with_counts.csv
relationship_pivot_summary.csv
Figure_1.png