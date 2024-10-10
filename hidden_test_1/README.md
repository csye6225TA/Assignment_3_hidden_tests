# Test Case 1

## APIs tested

- `define_stuff`
- `add`
- `remove`
- `get_count`
- `undefine`

## File passed

```csv
define_stuff,books,stationery
define_stuff,chairs,furniture
add,5,books
get_count,chairs
add,3,chairs
remove,1,books
get_count,books
add,2,books
remove,2,chairs
get_count,chairs
undefine,books
get_count,books
undefine,chairs
```

# Note
The application should handle trailing `,` gracefully and not return any errors.
