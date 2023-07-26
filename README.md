# Rofi Buku Integration
Tiny rofi script to run buku bookmarks. Can be assigned a hotkey with sxhkd.

### Dependencies
* Rofi
* Buku
* jq

### Installatin
```
$ git clone https://github.com/moeabdol/rofi-buku
$ cd rofi-buku
$ chmod u+x rofi-buku
$ cp rofi-buku ~/.local/bin
$ rofi-buku
```
* Make sure `~/.local/bin` is in your `$PATH`
* You should generate the bookmarks as a json file using the following command
```
$ buku -j -p0 > bookmarks.json
```
