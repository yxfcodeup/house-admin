# git commit规范

为了规范代码commit信息的格式，在提交代码前对代码格式做了校验，commit信息不符合规范的将禁止入库  
标准格式为：[type] description  
其中type支持以下几种：    

* feature：新功能（feature）。
* fix：修复bug，可以是QA发现的BUG，也可以是研发自己发现的BUG。
* optimize: 优化相关，比如提升性能、体验。
* docs：文档（documentation）。
* style：格式（不影响代码运行的变动）。
* refactor：重构（即不是新增功能，也不是修改bug的代码变动）。
* test：增加测试。
* chore：构建过程或辅助工具的变动。
* revert：回滚到上一个版本。
* merge：代码合并。

例子：[feature] 增加***功能  