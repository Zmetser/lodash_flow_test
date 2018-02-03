In this test flow only reads library definitions.

Reading lodash in master takes a lot more time than in the [`lodash_modified`](https://github.com/Zmetser/lodash_flow_test/compare/lodash_modified) branch

```
➜  git:(master) yarn flow
✨  Done in 59.31s.
```

```
➜  git:(lodash_modified) time yarn flow
✨  Done in 1.19s.
```

The only difference between the two branch is that I removed the individual exports.