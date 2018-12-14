### About My Scss Structure

The main ideas behind the organization of these files come from a couple of resources, with a few tweaks.

- [ITCSS: Scalable and maintainable Scss architecture](https://www.xfive.co/blog/itcss-scalable-maintainable-css-architecture/)
- [SASS Guidelines: 7-in-1 pattern](https://sass-guidelin.es/#the-7-1-pattern)

I am basically merging the two approaches, in order to have something that makes a lot of sense yet is easier to understand than the resources above.
Basically, what we are doing is to divide the styles in different categories:

- 01-Abstracts
- 02-Base
- 03-Elements
- 04-Components
- 05-Pages
- 06-Utilities
- 07-Print
- 77-Vendors
- 88-Legacy
- 99-Overrides

In each of these folders you can find a description for what is supposed to go in each folder.
