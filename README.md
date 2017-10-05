# news-vj-third-party-services
Code snippets that support our consumption of third-party services.

This repo currently contains the supporting code for:
1. Hearken
2. Shorthand

## Usage
### Shorthand
#### CSS Fixes
In order to apply the RTL fix for a Shorthand story, you will first need to ensure that you can edit the story in the Shorthand editor. In this editor you will find an 'Add CSS' button. 
#### RTL Languages
Applies styling to correct for RTL languages.
To use, copy the contents of `shorthand/rtl.css` into the Shorthand editor CSS panel for your story. 
If the story is in Arabic, also apply the Arabic font to the story by copying the contents of `shorthand/arabic-font.css` here.
#### Mobile/Desktop Only Sections Hack
Enables the hiding and showing of sections at `900px` based on their title (`show-desktop` or `show-mobile`)
To use, copy the contents of `mobile-desktop-toggle.css` into the Shorthand editor CSS panel for your story. 
