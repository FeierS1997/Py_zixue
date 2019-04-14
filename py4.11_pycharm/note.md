
# 配置pycharm运行环境：
    File - Settings:
        Editor - 配置背景, 字体等
        Plugins 安装 Ideavim, Markdown support
        Project - Interpreter 配置Python3项目解释器
            anaconda:虚拟环境管理器：
            -conda list: 显示anaconda安装的包
            -conda env list: 显示anacanda的虚拟环境
            -conda create -n xxx python=3.6: 创建python的版
            本为3.6的虚拟环境, 名称为xxx
        创建环境以后, 选择add local - exist.. - conda e... 
            var - sw - ana3 - envs - py411 - bin - python
            此时可以调试py程序
                -run    运行
                -debug  调试（建议此模式)