#GOPS v0.01a
## 

###Command line tool for string searching files in Go. Find files, fast.

* Uses the [KMP algorithm](http://en.wikipedia.org/wiki/Knuth%E2%80%93Morris%E2%80%93Pratt_algorithm). Linear, O(n), time complexity string search. ([Thanks paddie.](https://github.com/paddie/gokmp))
* Concurrent searching with goroutines.
* Recursively search current directory.
* Unicode capable!

##### Todo
* Better memory handling of opened files
* Better search options
  * regex
  * case sensitivity
  * flag commands
* Better error handling
* Profile and optimize
* Tests


###### HowTo

1. [install Go.](http://golang.org/doc/install)
2. Build the executable. (go build or go install)
3. gops "SearchMe"

