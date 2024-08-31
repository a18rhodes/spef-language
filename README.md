# Basic SPEF syntax highligting

Very basic SPEF (Standard Parasitic Exchange Format IEEE 1481-2009) syntax highligting **only** (i.e., not full language support) for detailed nets (D_NET). May incidentially support reduced nets (R_NET) since the syntax is fairly similar.

Includes coloring for
* Headers (e.g., \*SPEF, \*DESIGN, etc.)
  * Design flow substrings (e.g., "PIN_CAP NONE", "NAME_SCOPE LOCAL", etc.)
* Units (e.g., \*T_UNIT, NS, FF, etc.)
* Comments
* Name mapped items
* Basic keywords (\*D_NET, \*I lines, \*P lines, \*N lines)
* Subnodes and pins
* Instance names as separate entites from numbers
* Numbers including floats

[Example hilights with Dark Modern theme](https://github.com/a18rhodes/spef-language/blob/main/example.png?raw=true "Example")