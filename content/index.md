## Using Backticks


1. Inline code `const y: string = "Hello, world!";`
2. Highlighted inline code `const y: string = "Hello, world!";`{lang=ts} done

Here's an example of inline TypeScript code using backticks:

`const y: string = "Hello, world!";`

## Code Block (for comparison)

```typescript
const y: string = "Hello, world!";
```

As you can see, the code block above should be an inline code block, but instead it is resolved to the ProseCode component.

If you use the MDC shorthand, it works

:prose-inline-code[console.log('ok')]

