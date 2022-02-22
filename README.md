# casperlang-stdlib

Standard library for casper

Include following `package.json` in root of your casper project:
```
{
  "dependencies": {
    "std": {
      "version": "0.1.1",
      "url": "github.com/openengineer/casperlang-stdlib"
    }
  }
}
```

Then import the library in a file by placing the following statement at the top:
```
import "std"
```

The first time you run your program the repository will be downloaded and cached.
