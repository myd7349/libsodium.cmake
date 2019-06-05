`CMakeLists.txt` for [```libsodium```](https://github.com/jedisct1/libsodium)
=====

This project is originally as part of [vcpkg#5600](https://github.com/microsoft/vcpkg/pull/5600).

```bash
git clone https://github.com/myd7349/Ongoing-Study.git
pushd Ongoing-Study
git subtree split -P cpp/CMake/libsodium -b libsodium-cmake
popd

mkdir libsodium-cmake
cd libsodium-cmake
git init
git pull ../Ongoing-Study libsodium-cmake
git remote add origin https://github.com/myd7349/libsodium-cmake.git
git push origin -u master
```

Testing
=====

This project has been tested with these `libsodium` versions:

* 1.0.18
* 1.0.17

The test projects is here:

* [findlibsodium_test](https://github.com/myd7349/Ongoing-Study/tree/master/cpp/CMake/vcpkg/findsodium_test)
* [libsodium_test](https://github.com/myd7349/Ongoing-Study/tree/master/cpp/CMake/vcpkg/libsodium_test)

LICENSE
=====

MIT
