## Getting Started

飞马世界是一个二维宇宙，其中飞马星球是一个半径为 1 的星球。飞马星球上生活
着一种飞马人，他们的文明正处于快速发展当中，飞马星球上有很多国家，这些国家都
希望能发射环球卫星，为了保证大家的卫星能够正常运行和飞行，经过磋商飞马人成立
了一个飞马卫星管理局，并制定了一套规则，规则如下：
1. 最低卫星轨道为 1.2
2. 卫星轨道之间的距离不得小于 0.2
3. 每一个卫星必须有一个唯一的 COSPARID，总长度为 6 位，由两位国家编码加上
四位数字组成，由飞马管理局统一分配和管理。
4. 每一个卫星都有一个容易识别的名称，可以由所属国家命名
5. 卫星可以有两种状态，一种状态是处于激活可用状态，另一种是处于封锁非激
活状态，但卫星任然在固定轨道飞行，只是处于不可用状态
6. 卫星报废后，应该及时被删除，腾出轨道空间
为了便于管理，飞马卫星管理局委托你来帮他们开发一套微管理系统，采用面向
对象技术抽象和设计。为了其操作方便，飞马卫星管理局要求要有以下内容：
- 一个主菜单应该向用户提供一个操作选项列表
- 能够查看卫星列表
- 能够注册添加一个新卫星，添加新卫星要符合规则
- 能够编辑修改现有卫星信息
- 能删除卫星
- 能够按名称搜索卫星
- 能够根据 ID 封锁卫星
- 能够激活已经封锁了的卫星，重新启用
主菜单应该询问用户想要选择哪个选项并执行该操作。完成后，应将用户带回主菜
单。主菜单还应允许用户干净地退出应用程序。

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## Dependency Management

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).

