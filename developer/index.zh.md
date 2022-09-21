# Role2 开发者协作标准

## 协作

**代码能推就推。**

不及时推送其他成员就无法得知或参考你的最新开发进展，形成信息黑箱，影响预判，阻塞流程。

什么叫能推？ 正常运行不报错就可以推，可以不完美，可以有 Bug。（至于推到哪个分支请参考 [Git > 分支](#分支) 部分）

### Git

#### 分支

格式：`{master|[feature.FEATURE]dev[.MODULE]}`

##### 功能分支

- **`master`** - **产线版**，充分测试，风险最小，可以直接在产线运行的版本（不可删除）
- **`feature.<NAME>`** - **特性版**，需要独立存在的功能或特性，如：节日专题 `feature.new_year`，教育版 `feature.edu` 等等，通常以 `master` 为基础，合并使用（不可删除）

##### 阶段分支

- **`dev`** - **开发版**，正在开发的总版本，其他子模块最终会合并到此分支（可删除）
- **`dev.<NAME>`** - **子模块开发版**，正在开发的某个子模块，如：`dev.payment`（可删除）

基于 `master` 的开发前缀省略（直接 `dev` 就好，无需 `master.dev`），如果是特性版，只需前缀特性名称即可

- **`feature.edu.dev`** - 教育特性开发版
- **`feature.edu.dev.payment`** - 教育特性开发版，支付模块

## 命名

### 原则

**精准压倒一切。**

### 格式

**在任何情况下**，能使用 `snake_case` 就使用 `snake_case`，**拒绝 `camalCase`**，这些情况包括但不限于：目录名，文件名，变量名，函数名，键名，仓库名，分支名，URL 路径及参数...

**特殊情况**

- 类名：正常使用 `Snake_case`，只不过第一个字母大写，举例：`Apple`, `This_is_a_class`

## 格式

整个团队要使用同一种代码格式，同一种格式意味着字符比对完全一致。人力维护不现实，可以借助格式工具，类似于 [prettier](https://github.com/prettier/prettier)
，参考：[awesome-code-formatters](https://github.com/rishirdua/awesome-code-formatters)
