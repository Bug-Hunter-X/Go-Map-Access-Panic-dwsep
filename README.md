# Go Map Access Panic

This repository demonstrates a common error in Go: accessing a map element without first checking if the map is nil.  Attempting to access an element of an uninitialized map results in a runtime panic.

The `bug.go` file contains the erroneous code.  `bugSolution.go` shows the corrected version with a nil check.

This is crucial to prevent unexpected crashes in Go programs that use maps extensively.