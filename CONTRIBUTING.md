Don't take it personally if I don't handle your issue or pull request for
a long time, I'm sorry for that. Life happens and burnout is not nice to me.

# Contributing

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
