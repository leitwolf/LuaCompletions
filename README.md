LuaCompletions
==============

lua completions for sublime text 2/3

## Description

A lua develop plugin for sublime text 2/3.

##Features

 * system api completions support(lua5.1/5.2)
 * some snippets,like if-else,if-elseif-else,while,comment,repeat-until....
 * create new lua file with template

## Installation

Download .zip source file, then unzip it, clone "LuaCompletions" folder into the SublimeText ```Packages``` directory.  A restart of SublimeText might be nessecary to complete the install.


## Usage

###System api

```
{
	// 5.1 or 5.2
	"system":"5.1"
}
```

### template
```
{
    // lua template attributes
    // you can add new attibutes in the template_attr tag,like email
    // and then modify the template file "lua.tmpl"
    "date_format": "%Y-%m-%d %H:%M:%S",
    "template_attr": {
        "author": "My Name"
    }
}
```
It appear on the side bar context menu.
