- `LEFT` used to write characters of a string from the left.
- `RIGHT` used to write characters of a string from the right.
- `LENGTH` calculates how long the characters in the string.
- `TRIM` is used whenever we want to remove character from the beginning and/or end of a string. `TRIM` takes three argument 
	1. Specify which position to trim 'Leading', 'Trailing', 'Both'
	2. Characters to remove
	3. Columns that we want to trim
- `POSITION` specify the position of the first matching string
- `STRPOS` will achieve same thing as `POSITION` but with different syntax.
- `POSITION` and `STRPOS` is case-sensitive.
- `SUBSTR` will create string based on the beginning and ending position that specified in the syntax
- `CONCAT` combine columns into one column of string.
- We can use `||` as a substitute for `CONCAT`.
- `UPPER` makes character in data appear in uppercase. `LOWER` makes it lowercase 
- `EXTRACT` function retrieve a value (ex. year, month, etc) from a DATETIME
- `DATE_TRUNC` will convert date into a precision that specified
- `CURRENT_DATE`, `CURRENT_TIME`, `CURRENT_TIMESTAMP`, `LOCALTIME`, `LOCALTIMESTAMP`,  and `NOW` can be used to calculate current date.
- `COALESCE` can be used to fill data