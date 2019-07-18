# 自动生成md文档插件说明文档

### 1.1.0

版本升级  
    支持配置参数 **jsPath** 来生成用于获取生成md内容的路径  
bug修复  
    生成标题前有空格导致md渲染失败

使用方法：  


    ```
        // .babelrc
        "plugins": [
            ["autodoc", {"jsPath": "public/README.js"}]
        ]

    ```
