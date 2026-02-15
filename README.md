# Modern Dark Glassmorphic theme for Betterbird & Thunderbird  

**Custom `userChrome.css` and `userContent.css` for Betterbird; should also be compatible with Thunderbird **

## What is `betterbird-userchrome`  

Custom `userChrome.css` and `userContent.css` for Betterbird, fully compatible with Thunderbird.

This repository provides a modular, community-maintained CSS setup to customise the Betterbird interface, layout, and content styling using native `userChrome.css` and `userContent.css`. 

***Feel free to contribute!***  

## Features

- Clean, maintainable CSS structure
- Modular snippets for selective styling
- Compatible with latest Betterbird
- Thunderbird-compatible where possible
- Open for community contributions

## Repository Structure

```
/userChrome.css → Main UI customisations
/userContent.css → Content and message styling
/themes/ → Complete theme variations
/snippets/ → Optional modular CSS additions
/docs/ → Documentation and examples
```


## Installation (Betterbird / Thunderbird)

1. Locate your profile folder.
2. Open or create a `chrome` directory inside your profile.
3. Copy:
   - `userChrome.css`
   - `userContent.css`
4. Restart Betterbird.

Ensure `toolkit.legacyUserProfileCustomizations.stylesheets` is set to `true` in `about:config`.

## Compatibility

- Tested on latest Betterbird stable.
- Thunderbird compatibility depends on version parity.
- Breaking UI changes in upstream releases may require updates.

## Roadmap

- Modular theme presets
- Compact layout options
- Accessibility adjustments
- Dark/light variants

## Contributing

Contributions are welcome.

Please follow these rules:

- Keep styles modular and well-commented.
- Do not remove or refactor large sections without discussion.
- Test changes on latest Betterbird stable.
- Avoid vendor-specific hacks unless necessary.
- Submit changes via Pull Request.

All changes must be reviewed before merging.
