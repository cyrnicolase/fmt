# phpfmt - releases

phpfmt adopts a CoreOS-like versioning system. There are two channels:

- lts channel: long term support channel whose backward compatibility is guaranteed for 12 months.
- alpha channel: where latest changes live and frequently will not honor backward compatibility 

Check the releases on [this JSON file](https://github.com/phpfmt/releases/blob/master/releases.json) ([raw](https://raw.githubusercontent.com/phpfmt/releases/master/releases.json)).

Current LTS (803) EOL: May/2017


## Download 

- [LTS](https://github.com/phpfmt/releases/blob/master/releases/lts)
- [Alpha](https://github.com/phpfmt/releases/blob/master/releases/alpha)

## vim - config
```
let g:phpfmt_on_save = get(g:, 'phpfmt_on_save', 1) " format on save (autocmd)
let g:phpfmt_indent_with_space = 4         " use spaces instead of tabs for indentation
let g:phpfmt_config = "/home/work/.vim/custom/phpfmt.ini"
```
