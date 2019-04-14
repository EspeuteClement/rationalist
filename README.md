# rationalist

## What is this?

Useless database/website to sort movies/songs/shows by absurd criteria based on title only (colors, numbers, etc.).

Live at [rationalist.lucien.cat](http://rationalist.lucien.cat)

## Contributing

Rationalist is open to contributions, especially content additions, but also style modifications or new functionality. There are some rules below but they're subject to change and up for discussion.

Generally, all values should be deterministic, which doesn't necessarily mean that they wouldn't change over time (some dates change) or are exact, but that the result would always be consistent (for instance someone else wouldn't interpret it differently).

- Dependencies
  - Do not include any dependency on other software
  - Remote API requests are more likely to be accepted
- Criteria
  - Color
    - Use wikipedia to get the hex color from a color name
  - Date
    - Relative dates are allowed (e.g. `The Day After Tomorrow`)
  - Distance
  - Duration
  - Element
  - Letter
    - The letter in the title should be pronounced as the sole letter would, `a boy` does not count for the letter `A`, but `Boy A` does
  - Mass
    - Must be deterministic (the average elephant's mass for `Elephant Man` does not work)
  - Number
    - Saga numbering (e.g. `Iron Man 2`) is forbidden
    - No restriction on the format of the number (e.g. Roman numerals are ok)
- Titles
  - Currently all in english, but may change to original only
