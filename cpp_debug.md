|Discription|Solution|Source|
|-----------|--------|--------|
|warning: 'auto' type specifier is a C++11 extension [-Wc++11-extensions]|add ```"code-runner.executorMap" : { "cpp" : "cd $dir && g++ -std=c++11 $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt" }``` to user setting|https://stackoverflow.com/questions/51046803/visual-studio-code-c11-extension-warning/51351913|