# Java Clean Code Styles

## Naming Conventions
- Use `camelCase` for method names and `PascalCase` for class names.

## Code Structure
- Group related classes into packages.
- Keep methods small and focused on a single purpose.

## Best Practices
- Use interfaces to define contracts and avoid tight coupling.
- Use the appropriate access modifiers.

## Example
```java
public class Circle {
    private double radius;

    public Circle(double radius) {
        this.radius = radius;
    }

    public double calculateArea() {
        return Math.PI * radius * radius;
    }
}
```

## Counterexample
```java
public class C {
    public double area(int r) {
        return 3.14 * r * r;
    }
}
```
