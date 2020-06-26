Don't take it personally if I don't handle your issue or pull request for
a long time, I'm sorry for that. Life happens and burnout is not nice to me.

# Contributing

#### Everything should be well-tested with automation
With rare exceptions, I will not merge a PR if all tests aren't passing.
I also will not merge PRs that have large amounts of new, untested
functionality. I don't require 100% unit test coverage, but all happy paths
should be tested.

#### Maintainabilty > completeness
I will not add something that increases my maintenance burden unless
it's very compelling functionality or an obvious bugfix.

## Contributing code changes

Pull requests are the best way to propose changes to the codebase:

1. Fork the repo and create your branch from `master`.
2. If you've added code that should be tested, add tests.
3. Please, avoid breaking exported APIs.
4. Ensure the test suite passes (`go test ./...`).
5. Make sure your code is formated (personally I format Go code with
   [gofumports](https://github.com/mvdan/gofumpt) but `gofmt` is also great).
6. Make sure your code lints (
   [golangci-lint](https://github.com/golangci/golangci-lint) is my choice).
7. Issue that pull request!

## Write bug reports with detail, background, and sample code

**Great Bug Reports** tend to have:

+ A quick summary and/or background
+ Steps to reproduce
  + Be specific!
  + Give sample code if you can
+ What you expected would happen
+ What actually happens
+ Notes (possibly including why you think this might be happening, or stuff you tried that didn't work)

I *love* thorough bug reports.

#### References
This document was adapted from the open-source contribution guidelines for Facebook's Draft, as well as briandk's [contribution template](https://gist.github.com/briandk/3d2e8b3ec8daf5a27a62).

Also [Why I close PRs (OSS project maintainer notes)](https://www.jeffgeerling.com/blog/2016/why-i-close-prs-oss-project-maintainer-notes) by Jeff Geerling.
