# perldoc.vim

interface to perldoc. you can get perldoc with integrated operation for vim.

## Usage

### Modules
```
:Perldoc UNIVERSAL
```
Possible to complete names with `<tab>`

### Functions
```
:Perldoc -f grep
```

### Variables
```
:Perldoc -v $$
```

## Configuration

```vim
" Specify modifier of new/split method
let g:perldoc_split_modifier = '10v'

" Specify split positioning
let g:perldoc_split_position = 'rightbelow'
```

## Keymap

Type K to open Perldoc on the keywords.
