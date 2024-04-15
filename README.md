factorial: 
https://llvm.org/docs/CommandGuide/lli.html

#to execute program from LLVM bitcode use lli
$ lli factorial.ll

#need to link lli 
brew install llvm
echo 'export PATH="/usr/local/opt/llvm/bin:$PATH"' >> ~/.zshrc
source ~/.zshrc

sum_of_array:
clang -emit-llvm -S /Users/araimbay/Programming/C_code/sum_of_array/sum_of_array.c -o ./sum_of_array.ll