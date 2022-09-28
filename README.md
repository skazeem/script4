# script4
#!/bin/bash
echo -e "Enter Your Source Path: \c"
read path
echo -e "Enter Your Dest. Path: \c"
read dest
cp -i $path $dest
echo -e "file copied"
