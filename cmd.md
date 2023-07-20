# CMD notes

## Find files with trailing whitespace

```bash
find . -type f -exec egrep -l " +$" {} \;
```
