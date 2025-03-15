# 文本生成式人工智能Action标准【客户端】

## 动作列表

1. 文件读写
- 读文件：`FR`
    - `~+~action File read --path="文件路径"~-~`
- 写文件：`FW`
    - `~+~action File write --path="文件路径" --content="写入内容"~-~`
- 删除文件：`FD`
    - `~+~action File delete --path="文件路径"~-~`

2. 目录操作
- 创建目录：`DC`
    - `~+~action Directory create --path="目录路径"~-~`
- 删除目录：`DD`
    - `~+~action Directory delete --path="目录路径"~-~`
- 阅读目录：`DR`
    - `~+~action Directory read --path="目录路径"~-~`

3. 命令执行
- 执行命令：`CE`
    - `~+~action Command execute --command="命令"~-~`

4. 网络
- 发送GET请求：`NG`
    - `~+~action Network send get --url="请求地址"~-~`
- 发送POST请求：`NP`
    - `~+~action Network send post --url="请求地址" --data="请求数据"~-~`
- 发送PUT请求：`NU`
    - `~+~action Network send put --url="请求地址" --data="请求数据"~-~`
- 发送DELETE请求：`ND`
    - `~+~action Network send delete --url="请求地址"~-~`
- 发送HEAD请求：`NH`
    - `~+~action Network send head --url="请求地址"~-~`
- 发送OPTIONS请求：`NO`
    - `~+~action Network send options --url="请求地址"~-~`

5. 注释/提示：
- 注释：`CM`
    - `~+~action Comment --content="注释内容"~-~`
- 提示：`TP`
    - `~+~action Tip --content="提示内容"~-~`
- 警告：`WG`
    - `~+~action Warning --content="警告内容"~-~`
- 错误：`ER`
    - `~+~action Error --content="错误内容"~-~`
## Markdown提示适配的写法

```markdown
# XX 项目
## STDAction-Local标准支持进度
### 动作列表
#### 文件读写
- [x] `FR` 读文件
- [x] `FW` 写文件
- [x] `FD` 删除文件
#### 目录操作
- [x] `DC` 创建目录
- [x] `DD` 删除目录
- [x] `DR` 阅读目录
#### 命令执行
- [x] `CE` 执行命令
#### 网络
- [x] `NG` 发送GET请求
- [x] `NP` 发送POST请求
- [x] `NU` 发送PUT请求
- [x] `ND` 发送DELETE请求
- [x] `NH` 发送HEAD请求
- [x] `NO` 发送OPTIONS请求
#### 注释/提示
- [x] `CM` 注释
- [x] `TP` 提示
- [x] `WG` 警告
- [x] `ER` 错误
```
> 注：`[x]`表示已完成，`[ ]`表示未完成（中间有个空格，Github可以识别）。

# 本协议采用Apache License 2.0许可。
