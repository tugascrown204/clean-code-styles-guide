# Python Clean Code Styles

## Naming Conventions
- Use `snake_case` for variables and functions.
- Use `CamelCase` for classes.

## Code Structure
- Keep functions short and focused. One function should do one thing.
- Organize imports clearly at the top of the file.

## Best Practices
- Use list comprehensions where appropriate.
- Prefer `is` for comparisons to singletons like `None`.

## Example
```python
def calculate_area(radius):
    return 3.14 * radius * radius
```

## Counterexample
```python
def area(r):
    return 3.14 * r * r
```
