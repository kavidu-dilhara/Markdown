# Images

Images have a similar syntax to links but include a preceding exclamation point.

```markdown
![Minion](https://octodex.github.com/images/minion.png)
```

![Minion](https://octodex.github.com/images/minion.png)

or

```markdown
![Alt text](https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")
```

![Alt text](https://octodex.github.com/images/stormtroopocat.jpg)

Like links, Images also have a footnote style syntax

## Alternative usage : note images

```markdown
![Alt text][id]
```

![Alt text](https://octodex.github.com/images/dojocat.jpg)

With a reference later in the document defining the URL location:

```
[id]: https://octodex.github.com/images/dojocat.jpg  "The Dojocat"
```

## Resizing image

Add HTTP parameters `width` and/or `height` to the link image to resize the image. Values are CSS values (default is `auto`).

```markdown
![Minion](https://octodex.github.com/images/minion.png?width=20pc)
```

![Minion](https://octodex.github.com/images/minion.png?width=20pc)

```markdown
![Minion](https://octodex.github.com/images/minion.png?height=50px)
```

![Minion](https://octodex.github.com/images/minion.png?height=50px)

```markdown
![Minion](https://octodex.github.com/images/minion.png?height=50px&width=300px)
```

![Minion](https://octodex.github.com/images/minion.png?height=50px\&width=300px)

## Add CSS classes

Add a HTTP `classes` parameter to the link image to add CSS classes. `shadow`and `border` are available but you could define other ones.

```markdown
![stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg?classes=shadow)
```

![stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg?width=40pc\&classes=shadow)

```markdown
![stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg?classes=border)
```

![stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg?width=40pc\&classes=border)

```markdown
![stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg?classes=border,shadow)
```

![stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg?width=40pc\&classes=border,shadow)

## Lightbox

Add a HTTP `featherlight` parameter to the link image to disable lightbox. By default lightbox is enabled using the featherlight.js plugin. You can disable this by defining `featherlight` to `false`.

```markdown
![Minion](https://octodex.github.com/images/minion.png?featherlight=false)
```
