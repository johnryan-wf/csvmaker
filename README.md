# csvmaker

generates large csvs to print to stdout

## example

bash:

	csvmaker -rows 5 -cols 3
	
output:

	0, 0, 0
	1, 1, 1
	2, 2, 2
	3, 3, 3
	4, 4, 4

## installation

	go get github.com/johnryan-wf/csvmaker
	go install github.com/johnryan-wf/csvmaker

## running tests

	go test ./...

