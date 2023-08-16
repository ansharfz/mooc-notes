- `UNION` allows user to append multiple table.
- Here is the requirement for using `UNION` :
	1. Tables that are wanted to become union must have same number of column
	2. Columns must have the same data type order in the first column
- `UNION` by default doesn't join duplicate row from the subsequent table. Use `UNION ALL` to join all rows even if that row exist in the first table.
- We should consider what column to be displayed and/or joined before we use `UNION`
- 