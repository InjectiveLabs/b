`github.com/cznic/b` has moved to [`modernc.org/b`](https://godoc.org/modernc.org/b) ([vcs](https://gitlab.com/cznic/b)).

Please update your import paths to `modernc.org/b`.

### Usage in InjectiveLab projects

Put this into go.mod:

```
replace modernc.org/b => github.com/InjectiveLabs/b v1.1.0
```

Then use as normal:

```
import (
	btree "modernc.org/b"
)
```
