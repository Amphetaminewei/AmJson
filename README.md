# AmJson
A JSON parser based on C++17

## 平台

经测试在Windows10下的VS2019及Ubuntu18.04LTS下GCC7.5.0下测试均可正常使用，
注意在GCC下编译时需要手动指定使用C++17

## 测试

/include中提供了text.cpp作为单元测试，同时使用了[nativejson-benchmark](https://github.com/Amphetaminewei/nativejson-benchmark)测试其性能

## 构建

仅需编译除text.cpp外的文件，编译为静态类库即可使用