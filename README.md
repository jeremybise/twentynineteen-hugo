# Twenty Nineteen Hugo

**NOTE: BIG FAT WORK IN PROGRESS. JUST STARTING.**

This is a port of the WordPress Twenty Nineteen theme to Hugo.

## Installation

From the root of your site:

```
git submodule add https://github.com/jeremybise/twentynineteen-hugo.git themes/twentynineteen-hugo
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

## Differences from original theme

- Comment stuff has been omitted
- Author stuff has been omitted

## Frontmatter Notes

- Featured image path should be set in `image`.

## Available `config.toml` params

- `accent_color = "#FF0000"` Set a custom accent color for links and image filters, if enabled. Defaults to blue.
- `privacy_link = "/privacy/"` Relative URL to privacy page, if there is one. This enables a Privacy Policy link in the footer.
- `description = "This is the site tagline."` Adds tagline next to the site title.
- `enable_image_filters = true|false` Toggles off image color filter feature. Defaults to true.