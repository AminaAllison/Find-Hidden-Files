<h1>Find Hidden Files</h1>

#!/bin/bash
<br />

path=$(pwd)
<br />

find ~ -type f -name ".*" -ls
<br />

store_hidden_files=$(find ~ -type f -name ".*" -ls > Desktop/hidden.txt)
<br />

file_path=$(find ./Desktop -name hidden.txt)
<br />
