1.
Initialize the workspace
In the workspace directory, run:

$ go work init ./hello

2.
go.work -> use ./hello
The use directive tells Go that the module in the hello directory should be main modules when doing a build.

3.
In the workspace directory, run:
$ go run ./hello
olleH

4.

