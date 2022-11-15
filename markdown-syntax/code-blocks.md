# Code Blocks

## Inline code

Wrap inline snippets of code with `` ` ``.

```markdown
In this example, `<section></section>` should be wrapped as **code**.
```

Renders to:

In this example, `<section></section>` should be wrapped as **code**.

HTML:

```html
<p>In this example, <code>&lt;section&gt;&lt;/section&gt;</code> should be wrapped as <strong>code</strong>.</p>
```

## Indented code

Or indent several lines of code by at least two spaces, as in:

```markdown
    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code
```

Renders to:

```
// Some comments
line 1 of code
line 2 of code
line 3 of code
```

HTML:

```html
<pre>
  <code>
    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code
  </code>
</pre>
```

## Block code "fences"

Use "fences" ` ``` ` to block in multiple lines of code.

```markdown
Sample text here...
```

HTML:

```html
<pre>
  <code>Sample text here...</code>
</pre>
```

## Syntax highlighting

GFM, or "GitHub Flavored Markdown" also supports syntax highlighting. To activate it, simply add the file extension of the language you want to use directly after the first code "fence", ` ```js `, and syntax highlighting will automatically be applied in the rendered HTML.

See \[Code Highlighting]\(\{{< ref "syntaxhighlight.md" >\}}) for additional documentation.

For example, to apply syntax highlighting to JavaScript code:

````
    ```js
    grunt.initConfig({
      assemble: {
        options: {
          assets: 'docs/assets',
          data: 'src/data/*.{json,yml}',
          helpers: 'src/custom-helpers.js',
          partials: ['src/partials/**/*.{hbs,md}']
        },
        pages: {
          options: {
            layout: 'default.hbs'
          },
          files: {
            './': ['src/templates/pages/index.hbs']
          }
        }
      }
    };
    ```
````

Renders to:

```js
grunt.initConfig({
  assemble: {
    options: {
      assets: 'docs/assets',
      data: 'src/data/*.{json,yml}',
      helpers: 'src/custom-helpers.js',
      partials: ['src/partials/**/*.{hbs,md}']
    },
    pages: {
      options: {
        layout: 'default.hbs'
      },
      files: {
        './': ['src/templates/pages/index.hbs']
      }
    }
  }
};
```
