# **kplot**: A Command-Line Data Plotting Script


## Summary
This Python script simplifies data visualization directly from the command line. It takes input via file redirection or piping, parses X and Y columns, and creates customizable plots with options for titles, legends, and vertical markers. Designed for efficient and flexible plotting in CLI workflows.

## Usage
```bash
% cat datafile | kplot [-h] -y <col1,col2, ..> -x col [-v xaxis_value[,xaxis_value,...]] [-l <legend1,legend2,..>] [-t title] [-f]
```
```python
optional arguments:
  -h, --help            show this help message and exit
  -y <col1,col2, ..>    Columns to plot (comma-separated, 1-indexed)
  -x col                Column to use as x-axis (1-indexed)
  -v xaxis_value[,xaxis_value,...]
                        Position(s) of vertical line(s) on plot (comma-separated)
  -l <legend1,legend2,..>
                        Legend labels (comma-separated)
  -t title              Plot title
  -f                    Treat x-axis as categorical
```
