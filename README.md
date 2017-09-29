# character-length
Test out character length/limit in different apps/sites.

The purpose of this is to demonstrate readable characater lengths.

Table generated using [Tables Generator](http://www.tablesgenerator.com/markdown_tables#)

Tested on:
- MacBook Pro (15-inch, 2016)

This is also known as:

- row lengths
- row limits
- row width
- [characters per line](https://en.wikipedia.org/wiki/Characters_per_line)
   
# GitHub

GitHub doesn't work well on `920px`, but then again most sites don't.

```css
font-family: SFMono-Regular, Consolas, "Liberation Mono", Menlo, Courier, monospace;
font-size: 12px;
height: auto;
line-height: 20px;
```

|                                                                                                               | macOS Sierra 10.12.6 (16G29)         | macOS Sierra 10.12.6 (16G29)                           |
|---------------------------------------------------------------------------------------------------------------|--------------------------------------|--------------------------------------------------------|
|                                                                                                               | Safari Version 11.0 (12604.1.38.1.7) | Chrome Version 60.0.3112.113 (Official Build) (64-bit) |
| [Viewing a File](https://github.com/aizatto/character-length/blob/master/characters.txt) - Fixed Length       |                                  117 |                                                    117 |
| [Viewing a Diff](https://github.com/aizatto/character-length/commit/bae8f00feda5b832aa6fe162460968d8eaf040a5) |                                      |                                                        |
| `920px` width - Half of MBPr 15"; Usable but requires scrolling                                               | 58                                   | 58                                                     |
| `1280px` width - 3/4s of MBPr 5"; 1/2 of `2560px`; Decent                                                     | 78                                   | 78                                                     |
| `1706px` width - 3/4s of `2560px`                                                                             | 115                                  | 115                                                    |
| `1920px` width - MBPr 15"                                                                                     | 120                                  | 120                                                    |
| `2560px` width                                                                                                | 164                                  | 164                                                    |

# Phabricator

```css
font-family: Menlo, Consolas, Monaco, monospace;
font-size: 11px;
font-stretch: normal;
font-style: normal;
font-variant-caps: normal;
font-weight: normal;
height: 60px;
line-height: 15px;
```

|                                                           | macOS Sierra 10.12.6 (16G29)         | macOS Sierra 10.12.6 (16G29)                           |
|-----------------------------------------------------------|--------------------------------------|--------------------------------------------------------|
|                                                           | Safari Version 11.0 (12604.1.38.1.7) | Chrome Version 60.0.3112.113 (Official Build) (64-bit) |
| Viewing a Diff                                            |                                      |                                                        |
| `920px` width - Half of MBPr 15"                          | 58                                   | 58                                                     |
| `1280px` width - 3/4s of MBPr 5"; 1/2 of `2560px`; Decent | 82                                   | 82                                                     |
| `1706px` width - 3/4s of `2560px`                         |                                      |                                                        |
| `1920px` width - MBPr 15"                                 | 141                                  | 141                                                    |
| `2560px` width                                            | 179                                  | 179                                                    |
