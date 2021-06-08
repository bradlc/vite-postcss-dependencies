The `tailwindcss` plugin registers the following dependencies in this example:

```
{ type: 'dependency', file: '{projectRoot}/main.js' }
{ type: 'dependency', file: '{projectRoot}/tailwind.config.js' }
```

# Reproduction

1. `npm install`
2. `npm run dev`
3. Notice that the text is styled as expected
4. Edit `main.js`, replacing `text-red-500` with `text-blue-500`
5. Notice that the text is now black instead of the expected blue
