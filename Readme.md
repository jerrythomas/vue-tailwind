# Issue including typography

I followed the instriuctions in the [README](https://github.com/tailwindlabs/tailwindcss-typography)

```
yarn add @tailwindcss/typography
```
added the plugin to your tailwind.config.js as mentioned in the README.

Shouldn't the following command generate a final css that contains the typography classes?

```bash
npx tailwindcss build src/styles/index.scss -o output.css
```

Adding the following line to the source file after `@tailwindcss base;` is not mentioned in the document.
`@tailwindcss typography;`

But even that makes no difference. This line is not replaced at all and is retained as is.

Can you tell me what I am doing wrong or what step I have missed?
