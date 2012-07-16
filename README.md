
# pandoc data dir

This is where [pandoc](http://johnmacfarlane.net/pandoc/) looks for things such as templates or citation style files.

## using this

pandoc assumes that its data dir is at

- **unix** `$HOME/.pandoc`
- **windows** `C:\Documents And Settings\USERNAME\Application Data\pandoc`

clone this repo there

``` bash
# unix, assuming hub installed
cd ~
git clone era7bioinformatics/.pandoc
# for windows 7:
cd $HOME
git clone https://github.com/era7bioinformatics/.pandoc.git
```
