# Kagi-Nord-Theme

A theme for the Kagi search engine, based on the Nord Theme Pallette (https://www.nordtheme.com/)

# Current Issues

- At the moment, there seem to be various issues regarding mobile support.
  - For example, there is a div in the search bar that has to have a background color or otherwise it's imcompletely filled. Except, on mobile it seems that this background color overfills it. No solution has been found as of now. Some icons also do not have a color.
- There still remains a bunch of broken things when Kagi is configured to use light mode. It may become necessary to just use dark mode instead.
- The code is becoming very messy, as there isn't one concise way to create a theme, but rather CSS just applies on top of whatever Kagi already has, so some things can be themed with variables, but others required custom selectors.

## How To Use

There are two methods for installation. You can either using the native[ Kagi custom CSS feature](https://help.kagi.com/kagi/features/custom-css.html#customizing-kagi-css) or use the [Stylus browser extension](https://chromewebstore.google.com/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne).

### Kagi Custom CSS Feature

1.
