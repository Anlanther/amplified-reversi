# Amplified Reversi Skin

CSS to use for an AO3 skin. It can be copied and pasted to use for your own site skin by adding it to your account preferences. Based off the public 'Reversi' skin, but with darker tones and a fully black background.

## Preview photos

![home](https://user-images.githubusercontent.com/25150182/161788442-f5acaa4c-7fdd-41db-b2e6-de158a1853f2.png)
![profile](https://user-images.githubusercontent.com/25150182/161788449-94a76d52-34bb-4107-9a31-3ef30930888a.png)
![story](https://user-images.githubusercontent.com/25150182/161788453-cc9ffe28-3a2d-46f4-8084-a570cc157e1c.png)

## How to use

Simply copy the contents within `main.css` into your custom skin preferences on AO3.

---

## Development

### Setup

This project uses SCSS for better code organisation and variable management.

1. Install the recommended extension (check the VSC workspace config)
2. Enable `Watch Sass` from the status bar
3. All `.scss` changes will automatically compile to `main.css`

### File structure

- `main.scss` — Primary stylesheet (imports variables)
- `_variables.scss` — Colour and style variables
- `main.css` — Compiled output (auto-generated, do not edit)
