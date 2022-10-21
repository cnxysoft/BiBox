# BiBox
## B站API实用化工具

## 前言：
    这是一个旨在将B站API实用化的工具，以方便剪辑MAN的工作喵。

## 准备：
    将压缩包中的“工具”文件夹解压（或直接拖拽）至任意目录下。

## 使用：
  ### 一、批量更新B站昵称（简单操作）
    1.打开“ID列表.txt”，将Excel表格中的UID选中后覆盖粘贴在记事本中并保存（每行一个）。
    2.打开“BiBox.exe”，输入1并回车，将保存好的“ID列表.txt”拖入程序后回车，等待程序执行完成。
    3.打开“查询结果.txt”，全选复制其中数据并粘贴回Excel中（包含2列，分别是：UID、昵称）。
  ### 二、回放自动路灯（实验）
    1.打开“关键词.txt”，将需要标注时间的关键词写入记事本中并保存（每行一个）。
    2.打开“BiBox.exe”，输入2并回车，输入“BV号,分P号”后回车，等待程序执行（中间要有半角逗号）。
    3.打开“照明结果.txt”，查看结果，程序会将时间以“时：分：秒：毫秒”进行标注，后附原字幕备查。
### 进阶：
    1.本程序支持命令行调用，具体使用方法可以“-h”参数执行程序并查看输出。
    2.本程序的自动路灯功能目前（可能）尚不完善，后续有空会进行相关完善。

## 安全：
    为了安全起见，使用前建议检查文件数字签名，右键“BiBox.exe”菜单，点击属性，
    确认最上方存在“数字签名”标签页即可。
### 进阶：
    确认文件MD5为：CB32DADE14E4AB8D871FA5B08F90D425

## 联系：
    有问题或需要可联系：alen@znin.net
