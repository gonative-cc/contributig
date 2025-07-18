# Best Practices: JS and TS

We outline best practices when developing JavaScript and TypeScript programs.

## Formatting

* We use tabs for indentation with 4-spaces tab size.
* Set a reasonable line length. We use 100 characters line length.

## Type vs Interface:

- Use `interface` for defining object shapes, especially when you need to extend or implement them, or when you need declaration merging.
  Think of an `interface` as a "contract" or a "blueprint" for objects and classes. It's best used for defining the structure of an object.
- Use `type` for defining unions, tuples, mapped types, conditional types, and aliases for primitives. In fact, you must use type when you need to create an alias for a primitive type, or when you need to define a union (A or B) or a tuple.

| Feature              | `interface` | `type` |
| -------------------- | ----------- | ------ |
| Defines Object Shape | ✅          | ✅     |
| Declaration Merging  | ✅          | ❌     |
| Defines Primitives   | ❌          | ✅     |
| Defines Unions       | ❌          | ✅     |
| Defines Tuples       | ❌          | ✅     |
| Used with implements | ✅          | ❌     |

## Links:

- [Style guide](https://google.github.io/styleguide/tsguide.html#naming)
- https://docs.aws.amazon.com/prescriptive-guidance/latest/best-practices-cdk-typescript-iac/typescript-best-practices.html

## Testing

- Use [vitest](https://vitest.dev)
