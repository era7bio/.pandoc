
# pandoc data dir

This is where [pandoc](http://johnmacfarlane.net/pandoc/) looks for things such as templates or citation style files.

## using this

pandoc assumes that its data dir is at

- **unix** `$HOME/.pandoc`
- **windows** `$HOME\AppData\Roaming\pandoc`

clone this repo there

``` bash
# unix, assuming hub installed
cd ~
git clone era7bio/.pandoc
# for windows 7:
cd $HOME\AppData\Roaming
git clone https://github.com/era7bio/.pandoc.git pandoc
```


