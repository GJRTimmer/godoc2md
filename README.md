

# godoc2md
Package godoc2md converts godoc formatted package documentation into Markdown format.

Usage
godoc2cmd can be used from commandline or as a go:generate build tag.

Commandline


	godoc2md $PACKAGE > $GOPATH/src/$PACKAGE/README.md

Build Tag


	//go:generate godoc2md -o README.md .






- - -
Generated by [godoc2md](https://www.github.com/GJRTimmer/godoc2md)
