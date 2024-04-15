factorial: 
https://llvm.org/docs/CommandGuide/lli.html

#to execute program from LLVM bitcode use lli
$ lli factorial.ll

#need to link lli 
brew install llvm
echo 'export PATH="/usr/local/opt/llvm/bin:$PATH"' >> ~/.zshrc
source ~/.zshrc
