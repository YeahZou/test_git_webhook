测试 github的webhook的触发时机。
1、在repo上配置webhook，该repo下所有分支的push都会触发hook
2、发起一个request请求也会触发
3、被merge后会触发一次
4、测试是否OK了