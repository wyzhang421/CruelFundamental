# 重载和覆盖区别，返回值类型不同，可以重载吗，为什么
- https://www.huaweicloud.com/articles/12625254.html

## 重载 Overload
- 同一个类，相同函数名，不同参数
- 参数相同，返回值不同，不能重载
- 因为函数表/编译器只能区分函数名和参数表

## 覆盖 Overwrite
- 父类子类，相同函数名，相同参数，相同返回值，父类方法没有virtual

## 重写 Override
- 父类子类，相同函数名，胸痛参数，相同返回值，父类方法有virtual
- 父类指针，子类对象，会动态绑定