# GoAdmin Official Themes

- [adminlte](https://github.com/MarErm27/GoAdminThemes-/tree/master/adminlte)
- [sword](https://github.com/MarErm27/GoAdminThemes-/tree/master/sword)

[中文介绍](./README_CN.md)

## How to use

- Import the theme
- Set in the global configuration of GoAdmin

```go

package main

import (
	...
	_ "github.com/MarErm27/GoAdminThemes-/adminlte"
	...
)

func main()  {
	
	...
	
	cfg := config.Config{
    		...
    		
    		Theme: "adminlte",
    		
    		...
    	}
	
	...
 
}

```

## How to modify and make it work

Use the Makefile under each theme directory.