# 一、 Rules & Names Convention
- 遵循驼峰命名规则
- 遵循Unity命名规则
- 类名、函数以大写开头
- 属性、类变量、局部变量以小写开头
- 严禁写公有类变量
- 统一命名空间
- 除框架需要，请不要使用MonoBehaviour和MonoSingleton
- Lua严格遵循两个规则:一是一切皆local,二是公有化一切皆module

# 二、 Git Convention
- git add
- git commit
    ```shell
    (+ add)
    (- remove)
    (* update)
    (# fixed)
    ```
- git fetch
- git rebase
- manual merge
- git rebase -continue
- git push


# 三、 Environment

## unity

- [Install Unity Hub](https://unity3d.com/get-unity/download)
- [Install Unity 2020.3.33f1](https://unity3d.com/unity/qa/lts-releases?version=2020.3)
  ```
  备注:一定要通过网站选择Unity Hub安装，不然为安装成国内版
  ```

## git
- [Install Git](https://gitforwindows.org/)
- [Install Git-Lfs](https://git-lfs.github.com/)
- [Register GitHub](https://github.com/)
  ```
  备注:将注册好的github邮件地址，发给我用于项目权限
  ```
- [客户端仓库](https://github.com/SuperCLine-ActionEngine)
- [配置、协议、工具等仓库](https://github.com/MetaAvatar)

## python 3.10
- [Install python]
  ```
  备注:通过cmd窗口输入python进行安装
  ```
## repo
- [Install repo](https://gerrit.googlesource.com/git-repo/)
  ```
  备注:通过git bash来运行Install目录下的命令
  ```

## editor
- [Install Visual Studio Community 2019](https://visualstudio.microsoft.com/vs/older-downloads/)
- [Install Visual Studio Code](https://code.visualstudio.com/download)

## mac
```shell
# install git
brew install git
# install git-gui
brew install git-gui
# install git lfs
brew install git-lfs
# install python 3.10.5
brew install python
# install repo
# https://gerrit.googlesource.com/git-repo/
# install unity 2020.3.33f1
# https://unity3d.com/unity/qa/lts-releases?version=2020.3
```

# 四、 [git repo](https://gerrit.googlesource.com/git-repo/)
```shell
repo init --no-clone-bundle -u https://github.com/SuperCLine-ActionEngine/OpenMic-Manifest.git
repo sync
repo forall -c git checkout master
```