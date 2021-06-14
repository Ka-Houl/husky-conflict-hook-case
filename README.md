# husky-conflict-hook-case

---

Using npm:

```bash
# Install dependency
$ npm i

# this case uses husky@^4.2.5
# its option in package.json is

#   "husky": {
#     "hooks": {
#       "pre-commit": "node script"
#     }
#   },

# step1
# modify the ./test.js

# step2
$ git add .

# step3
$ git commit -m 'create git conflict'
# now you can see the git commit warning tip in your bash


```

## Links

-   [Newest Feature Requests](https://github.com/Ka-Houl/husky-conflict-hook)
-   [Top Bugs 😱](https://github.com/Ka-Houl/husky-conflict-hook/issues)
-   [Benchmarks](https://github.com/Ka-Houl/husky-conflict-hook#readme)
-   [husky Url](https://www.npmjs.com/package/husky)
-   [lint-staged Url](https://www.npmjs.com/package/lint-staged)
