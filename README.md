# stitches.config
*my stitches config*

## features

[Stitches](https://stitches.dev/) config of popular design system like `tailwindcss` and `macos`

### themes

- [tailwindcss](https://github.com/JiangWeixian/stitches.config/tree/master/tailwindcss) - stitches with 🎐 [tailwindcss](https://tailwindcss.com/)
  - [preflight](https://unpkg.com/tailwindcss@3.0.23/src/css/preflight.css)
- [(WIP)macos@monterey](https://github.com/JiangWeixian/stitches.config/tree/master/macos) - stitches with 🍎 [macos](https://developer.apple.com/design/human-interface-guidelines/macos/visual-design/color/) style guide
  - system dark
  - [ ] system light 

#### convention

according to [stitches#naming-convention](https://stitches.dev/docs/tokens#naming-convention). tailwindcss class like `0.5` or `1/2` is not valid. 

```tsx
// recommended
tokenName
token_name
token-name

// avoid
token.name
token$name
token*name
```

There are some different with original `tailwindcss`

- `0.5` will be `0_5`
- `1/2` will be `1-2`

### utils

- Alias for margin e.g. `my/mx/mt/mb`
- Alias for padding e.g. `py/px/pt/pb`
- Size for combine `width/height`
- Text for combine `fontSize/lineHeight`
  
see more details in config file

## usage

Copy or move dir e.g. `tailwindcss` directly to project.

## refs

- [vscode-mac-color-picker](https://github.com/EugeneDae/vscode-mac-color-picker)
- [macos-human-interface-guide](https://developer.apple.com/design/human-interface-guidelines/macos/visual-design/color/)
- [tailwindcss](https://tailwindcss.com)

# 
<div align='right'>

*built with ❤️ by 😼*

</div>