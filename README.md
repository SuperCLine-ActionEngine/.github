# Rules & Names Convention
- 遵循驼峰命名规则
- 遵循Unity命名规则
- 类名、函数以大写开头
- 属性、类变量、局部变量以小写开头
- 严禁写公有类变量
- 统一命名空间
- 除框架需要，请不要使用MonoBehaviour和MonoSingleton
- Lua严格遵循两个规则:一是一切皆local,二是公有化一切皆module

# [git repo](https://gerrit.googlesource.com/git-repo/)
```shell
repo init --no-clone-bundle -u https://github.com/SuperCLine-ActionEngine/OpenMic-Manifest.git
repo sync
repo forall -c git checkout master
```