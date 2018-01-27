# get-css-fonts - Get local fonts from a CSS URL

Simple script to download a fonts CSS (typically from a Google fonts URL) and
all font resources declared in it.

The resulting CSS will have font `url()`s updated to match the local path.

For example,

```bash
./get-css-fonts 'http://fonts.googleapis.com/css?family=Source+Code+Pro|Source+Sans+Pro:300,400'
```

will create a `fonts.css` files with font URLs pointing to a local `fonts/`
directory, where all font files are downloaded.
