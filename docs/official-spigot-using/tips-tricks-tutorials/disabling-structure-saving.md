## 背景

如果您在保存世界时遇到了延迟，您可能需要禁用结构保存。对于那些使用 1.7 版新地图的用户，也建议禁用结构保存。

然而，禁用结构保存有其优点和缺点，如下所述。

## 优点

- 保存不会导致滞后，导致更快的保存，不会暂时暂停服务器
- 更少的资源被闲置使用

## 缺点

- 女巫不会在他们的小屋里生成
- 凋零骷髅不会在地堡中生成
- 末影之眼睛不会指向据点
- 铁傀儡将不再在村庄中生成
- 可能还有其他尚未发现的问题

## 说明

要禁用结构保存，请按照下面提供的信息进行操作。

1. 确保你的服务器处于关闭状态
2. 打开你的 `spigot.YAML` 文件进行编辑。这可以在服务器的根目录中找到。
3. 将 boolean 型变量 `save-structure-info` 改为 `false`。
4. 在禁用保存结构信息后，你需要从每个世界的/data 文件夹中移动或删除 `Fortress.dat`, `Mineshaft.dat`, `Stronghold.dat`, `Temple.dat` 和 `Village.dat`。
5. 重新启动你的服务器

[跳转至官网原文 :material-link:](https://www.spigotmc.org/wiki/disabling-structure-saving/){ .md-button }