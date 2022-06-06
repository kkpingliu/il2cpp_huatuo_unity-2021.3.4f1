# il2cpp_huatuo

适用于unity 2021.3.4f1版本，已更新至支持AOT泛型。感谢huatuo官方大佬的支持！

原始il2cpp是AOT运行时，不支持动态注册dll元数据。huatuo轻微改造了metadata管理模块，插入了一些hook代码，支持动态加载dll元数据。 注意，此项目代码不能单独工作，甚至无法成功编译。必须配合 huatuo 解释器才能正常工作。

链接

https://github.com/focus-creative-games/huatuo

https://github.com/pirunxi/il2cpp_huatuo

https://github.com/focus-creative-games/huatuo_trial
