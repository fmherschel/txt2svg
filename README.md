# txt2svg
Simply convert command-line output or text files to svg-graphics

## Example

`df -hP | txt2svg --lines=30 --cols=80 > df-hP.svg`

`display df-hP.svg`

## Command line options

`--lines=nn` sets the ouput graphic to a hight to cover nn lines of output. The default is 24.

`--cols=nn` sets the ouput graphic width to cover nn columns of output. The default is 120.
