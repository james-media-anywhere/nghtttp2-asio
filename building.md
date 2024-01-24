Either:
"C:\Program Files\CMake\bin\cmake" -DCMAKE_BUILD_TYPE=Debug -B out/build -S .
"C:\Program Files\CMake\bin\cmake" -DCMAKE_BUILD_TYPE=Release -B out/build -S .
Then open out/build/nghttp2-asio.sln in Visual Studio & build.