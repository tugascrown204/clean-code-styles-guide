# JavaScript Clean Code Styles

## Naming Conventions
- Use `camelCase` for variables and functions.
- Use `PascalCase` for classes.

## Code Structure
- Keep code modular and organized.
- Use ES6 modules whenever possible.

## Best Practices
- Avoid global variables. Use closures or modules.
- Always declare variables with `const` or `let`.

## Example
```javascript
function calculateArea(radius) {
    return Math.PI * radius * radius;
}
```

## Counterexample
```javascript
function area(r) {
    return 3.14 * r * r;
}
```
