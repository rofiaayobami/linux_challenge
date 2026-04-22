
# Day 18 - Text Processing in Linux (grep, awk, sed)

## Objective

The goal for today was to learn how to search, filter, and manipulate text data using Linux tools.

---

## What I Learned

- `grep` is used to search for patterns in files
- `awk` is used to process structured data by columns
- `sed` is used to edit and replace text
- Pipes (`|`) allow combining multiple commands

---

## What I Built / Practiced

- Searched for specific text using `grep`
- Extracted columns using `awk`
- Filtered data using conditions in `awk`
- Replaced text using `sed`
- Combined commands using pipes

---

## Challenges Faced

- Understanding awk syntax
- Differentiating between grep, awk, and sed

---

## Key Takeaways

- Linux provides powerful tools for text processing
- `grep`, `awk`, and `sed` are essential for data handling
- Pipes allow chaining commands together
- These tools are widely used in data engineering workflows

---

## Resources

- Linux manual pages (`man grep`, `man awk`, `man sed`)
- Practice on remote Linux server

---

## Output

```bash
grep Mary data.txt
awk -F',' '{print $1}' data.txt
awk -F',' '$2 > 24 {print $1}' data.txt
sed 's/John/Jane/' data.txt
