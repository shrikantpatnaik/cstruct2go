# cstruct2go
A simple tool to convert C structs to equivalent Golang structs

## Installation

The tool can be compiled with a simple `go build`. You can also add it to your `GOBIN` with a `go install`

## Usage

`./cstruct2go -i=test_structs.h -o=test_structs.go -p=test_structs`

CLI Options:  
  -i: Input file  
  -o: Output File  
  -p: Package Name, Defaults to "main"  
  -f: Format flag, Runs go fmt on output file if true, defaults to true   
  -h: Print Help
    
    
## Compatible Types
Compatible types can be found in the test_structs.h file


