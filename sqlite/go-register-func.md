# sqlite RegisterFunc

Sqlite3 does not implement stored procedures, but it has application defined
functions; with the Go sqlite3 wrapper, you can use RegisterFunc to blend Go
and SQL.

* [https://sqlite.org/forum/info/78a60bdeec7c1ee9](https://sqlite.org/forum/info/78a60bdeec7c1ee9)
* [https://pkg.go.dev/github.com/mattn/go-sqlite3#SQLiteConn.RegisterFunc](https://pkg.go.dev/github.com/mattn/go-sqlite3#SQLiteConn.RegisterFunc)

It nicely blends SQL and Go.

Via: [https://golangleipzig.space/posts/meetup-50-wrapup/](https://golangleipzig.space/posts/meetup-50-wrapup/)

Examples:

* [.../controlcenter/.../lmsqlite3/lmsqlite3.go#L70-L84](https://gitlab.com/leandrosansilva/controlcenter/-/blob/4be01c14150eaf629db5d9c7448e5e19850da63c/lmsqlite3/lmsqlite3.go#L70-L84)
* [.../controlcenter/.../intel/connectionstats/reporter.go#L60-63](https://gitlab.com/leandrosansilva/controlcenter/-/blob/4be01c14150eaf629db5d9c7448e5e19850da63c/intel/connectionstats/reporter.go#L60-63)
