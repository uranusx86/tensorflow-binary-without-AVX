# tensorflow-binary-without-AVX
After download, plz rename to **tensorflow-1.12.0rc0-cp35-cp35m-linux_x86_64.whl**, 

cause pip will check file name is match to the os platform or not.

check what wheel tags are compatible on your system with the following command
```
python3 -c "import wheel.pep425tags as w; print(w.get_supported())" | sed -zE 's/\),/),\n/g'
```
