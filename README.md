# GenServerAPIMap

* 将工程目录下的hamster.proto，按照message name，生成ServiceApiMap.lua，大写key对应message name

## 未实现

- [ ] 生成目录下的所有proto文件，到lua代码里，合并为一个

- [x] 生成request对应response的对应文件

- [ ] 区分notify的message，生成handler对应文件