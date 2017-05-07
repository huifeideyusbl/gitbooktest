github 与gitbook的联调

我们都是小青蛙，哈哈哈哈哈



****实现了菜单容器接口，所以***可用于盛装menu



快捷键的代码创建：   MenuShortcut ms=new MenuShortcut(keyEvent.VK_A);
如果该快捷键还需要shift键的辅助，这可使用如下代码：
MenuShortcut ms=new MenuShortcut(KeyEvent.VK_A,true);

将功能相近的菜单分组：（使用菜单分隔符）两种方法：
调用Menu对象的addSeparator 方法来添加菜单分割线。
添加new Menultem（“-”）菜单项来添加菜单分隔线。
          设置二级菜单


****实现了菜单容器接口，所以***可用于盛装menu



快捷键的代码创建：   MenuShortcut ms=new MenuShortcut(keyEvent.VK_A);
如果该快捷键还需要shift键的辅助，这可使用如下代码：
MenuShortcut ms=new MenuShortcut(KeyEvent.VK_A,true);

将功能相近的菜单分组：（使用菜单分隔符）两种方法：
调用Menu对象的addSeparator 方法来添加菜单分割线。
添加new Menultem（“-”）菜单项来添加菜单分隔线。
          设置二级菜单