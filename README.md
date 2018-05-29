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

# Display Resolutions

| Device          | Full Resolution | 1/2      | 1/3           | 1/4       | 1/6           | Comments         |
|-----------------|-----------------|----------|---------------|-----------|---------------|------------------|
| MacBook Pro 15" | 1024x640        | 512x320  | 341.33x213.33 | 256x160   | 170.66x106.66 |                  |
| MacBook Pro 15" | 1280x800        | 640x400  | 426.66x266.66 | 320x200   | 213.33x133.33 |                  |
| MacBook Pro 15" | 1440x900        | 720x450  | 480x300       | 360x225   | 240x150       |                  |
| MacBook Pro 15" | 1680x1050       | 840x525  | 560x350       | 420x262.5 | 280x175       | Laptop Default   |
| MacBook Pro 15" | 1920x1200       | 960x600  | 640x400       | 480x300   | 320x200       | My Default       |
| 27" Display     | 2560x1440       | 1280x720 | 853.33x480    | 640x360   | 426.66x240    | External Monitor |
   
# GitHub

GitHub doesn't work well on `960px`, but then again most sites don't.

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
| `960px` width - Half of MBPr 15"; Usable but requires scrolling                                               | 58                                   | 58                                                     |
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
| `960px` width - Half of MBPr 15"                          | 58                                   | 58                                                     |
| `1280px` width - 3/4s of MBPr 5"; 1/2 of `2560px`; Decent | 82                                   | 82                                                     |
| `1706px` width - 3/4s of `2560px`                         |                                      |                                                        |
| `1920px` width - MBPr 15"                                 | 141                                  | 141                                                    |
| `2560px` width                                            | 179                                  | 179                                                    |
