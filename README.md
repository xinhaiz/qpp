# QPP - GIT项目管理的小工具

# 产生: 因为懒

# 环境
  - shell

# 使用
  - 适用：非独立并且无依赖关系的多个项目适用QPP
  - 自动：在需要处理的GIT项目总目录执行 $PATH/build
  - 手动：执行 $PATH/qpp, 参数如下：
    * `-c | --name` 项目名称  
    * `-p | --prefix` 项目下可能出现的文件夹
    * `-a | --action` 执行动作, [pull, clone]
    * `-o | --project` 操作的项目(多个)  
    * `-r | --remote` 克隆远程项目地址(多个, action为clone时有效，且与`-o | --project`成对出现)
