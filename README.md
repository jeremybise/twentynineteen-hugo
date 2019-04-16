# Twenty Nineteen Hugo

**NOTE: BIG FAT WORK IN PROGRESS. JUST STARTING.**

This is a port of the WordPress Twenty Nineteen theme to Hugo.

## Installation

From the root of your site:

```
git submodule add https://github.com/jeremybise/twentynineteen-hugo.git themes/twentynineteen-hugo
```

In your `config.toml`, add the following:

```
theme = "twentynineteen-hugo"
```

## Updating

From the root of your site:

```
git submodule update --remote --merge
```

## Highlights

- Accent color configurable via config.toml
- Featured images and image filter effect works
- Social menu icons all ported using Hugo's built-in menus
- Syntax highlighting included with the Monokai Light syntax theme

## Differences from original theme

- Comment stuff has been omitted
- Author stuff has been omitted

## Content Notes

- To set a featured image for a post or page, add `image: /path/to/image.jpg` to your frontmatter.
- 

## Available `config.toml` params

These go in `config.toml` in a `[params]` section like this:

```toml
[params]
  accent_color = "#FF0000"
  description = "This is the site tagline."
```

- `accent_color = "#FF0000"` Set a custom accent color for links and image filters, if enabled. Defaults to blue.
- `privacy_link = "/privacy/"` Relative URL to privacy page, if there is one. This enables a Privacy Policy link in the footer.
- `description = "This is the site tagline."` Adds tagline next to the site title.
- `disable_image_filters = false` Setting to true disables the color filter feature on images. Defaults to false.

## Syntax Highlighting

Add these to `config.toml`:

```toml
pygmentsUseClasses=true
pygmentsCodefences=true
```