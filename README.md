# VSCode Dark+ Theme For Qt Creator

I tried my best to port the default Dark+ theme from VS Code into Qt Creator, as I find it quite nice, but I cannot replicate it 1:1 due to the limitations of Qt's theme engine, for example Qt doesn't differentiate between keywords like `const`, `namespace`, and `enum` which would be blue in VSCode, and keywords like `if`, `operator`, `return`, which would be purple in VSCode; it's either one or the other in Qt, so I've included both options to choose from, purple keywords (what I prefer), but also blue keywords. I hope you enjoy!

## Installation

Just move one or both of the `.xml` files of your choice into your Qt Creator styles folder, and the `.creatortheme` file into your Qt Creator themes folder. These two folders belong to the same parent directory, whose location depends on your operating system, and of which there are always two. The first belongs to your Qt Creator installation directory, and contains Qt Creator's default styles & themes -- any styles located there cannot be modified from within Qt Creator. The second, recommended location, is located in the user data directory for whichever operating system you are using.

_From: https://doc.qt.io/qtcreator/creator-quick-tour.html#location-of-settings-files_

### Windows Location
- Full Paths: `C:\Users\%USERNAME%\AppData\Roaming\QtProject\qtcreator\styles`
              `C:\Users\%USERNAME%\AppData\Roaming\QtProject\qtcreator\themes`

- Shortcut:   `%appdata%\QtProject\qtcreator\styles`
              `%appdata%\QtProject\qtcreator\themes`

If the `theme` or `styles` folder does not exist, create it.

### Linux Location
- `~/.local/share/data/QtProject/qtcreator`

### OSX Location
- `~/Library/Application Support/QtProject/Qt`

## Previews
Font used in the screenshots:  [MonoLisa](https://www.monolisa.dev/)

### Purple Keywords Preview 
![](screenshots/purple1.png)
![](screenshots/purple2.png)
![](screenshots/purple3.png)

### Blue Keywords Preview
![](screenshots/blue1.png)
![](screenshots/blue2.png)
![](screenshots/blue3.png)

### Doxygen Comments
![image-20221120110327601](screenshots/image-20221120110327601.png)

## Additional Credits
* `.creatortheme` and Doxygen comment colours courtesy of [yunke120](https://github.com/yunke120)
