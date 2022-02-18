# yorn

yorn was created by, and is maintained by **[tal7aouy](https://github.com/tal7aouy)**, and is a tool for benchmarking the given url response status and response time.

⚡️ Usage :

```bash
git clone https://github.com/tal7aouy/yorn
```

✅ Build the project like so:

```bash
cd yorn
make
```

🚀 Next, run yorn:

```bash
cd bin
./yorn <your-domain.com> <number-of-requests>
```

🤓 The output will be something like this:

```
➜  ./yorn google.com 15
[200] google.com ~= 0.629421 seconds
[200] google.com ~= 0.320449 seconds
[200] google.com ~= 0.483449 seconds
[200] google.com ~= 0.474812 seconds
[200] google.com ~= 0.401972 seconds
[200] google.com ~= 0.398322 seconds
[200] google.com ~= 0.321155 seconds
[200] google.com ~= 0.319264 seconds
[200] google.com ~= 0.319220 seconds
[200] google.com ~= 0.398813 seconds
[200] google.com ~= 0.319108 seconds
[200] google.com ~= 0.318398 seconds
[200] google.com ~= 0.319787 seconds
[200] google.com ~= 0.322030 seconds
[200] google.com ~= 0.478483 seconds
```

**yorn** was created by **[tal7aouy](https://github.com/tal7aouy)** under the **[MIT license](https://opensource.org/licenses/MIT)**.
