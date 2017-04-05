之前已经介绍了线性表的顺序存储和链式存储的实现和操作。下面就这两种实现进行比较。

顺序表有以下优点：存储密度大，无需为表示元素之间的逻辑关系额外使用存储空间；根据序号查找元素很容易。

顺序表的缺点是插入和删除元素需要移动大量的操作，这一点我在实现的时候强调过。

链表优点是插入和删除操作只需要修改相关指针域，不需要移动元素。

链表的缺点是存储密度小，需要额外的字段表示元素间的关系；根据序号查找元素需要从头找起。
