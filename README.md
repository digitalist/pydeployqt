# pydeployqt
Helps to build cross-plaftorm apps using MXE (aka Linux->Windows). This is a wrapper for  mingw32 objdump /windeployqt substitute (windeployqt is missing from MXE. I don't know why they disabled it, but) 
I use this script to build crossplatform apps with cmake.

## Installation
install mxe. http://mxe.cc

git clone  https://github.com/digitalist/pydeployqt.git
## Usage

1) build your project
2) run
```  
./deploy.py --build=~/project/build/ 
--objdump=/home/user/mxe/usr/bin/i686-w64-mingw32.shared-objdump 
~/project/build/project.exe
```
now you have all the libraries to run your app in Windows inside --build folder!

## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
## History
no history for now
## Credits
TODO: Write credits (me and some python books)
## License
MIT License

Copyright (c) 2016 Alexey Elymanov

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
