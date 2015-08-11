# cpm-FakeIt
[CPM](http://cpm.rocks) external for
[FakeIt](https://github.com/eranpeer/FakeIt) mocking framework.

## Usage

Add this line to your `CMakeLists.txt` file:
```
CPM_AddModule("cpm-catch"
  GIT_REPOSITORY "https://github.com/bcachet/cpm-catch")
CPM_AddModule("cpm-FakeIt"
  GIT_REPOSITORY "https://github.com/bcachet/cpm-FakeIt")

```

Add this to your C++ code to use FakeIt with Catch:
```c++
#include <catch.hpp>
#include <catch/fakeit.hpp>
```

