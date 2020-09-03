### 使用说明

1. 修改简历内容

    请把要生成的模版文件夹中的 HTML 文件中的**文字/代码**内容替换成自己的实际情况。（文件夹里面已经有对应的例子。预览修改效果时，可以把浏览器缩放（"Command" + "+"）成 150% 查看实际转出PDF效果。）

2. 导出为PDF格式
    
    按照你的语言习惯把 HTML 文件转变成 PDF 格式，如果你使用 macOS，可以在first, second或者third文件夹下运行（需安装 wkhtmltopdf，请参考下面步骤）：
    
        ./convert resume.html

    能够直接导出PDF。
    
    如果你使用其他系统，这里附了一个 Python 脚本 convert.py，使用方法如下：
    1. 安装 [wkhtmltopdf](https://wkhtmltopdf.org/) 
        
        > 例如Windows下安装的话首先到[这里](https://wkhtmltopdf.org/downloads.html)下载，安装的时候请记住安装目录，安装完成后把安装目录下bin目录中的可执行wkhtmltopdf.exe文件放在模版目录下（如first/wkhtmltopdf.exe，second/wkhtmltopdf.exe）。
    2. 终端运行：

        pip3 install pdfkit 
        
        python3 convert.py resume.html
    
    即可导出 PDF 文件。字体按照苹方体，冬青黑体，黑体，微软雅黑的顺序进行渲染。你也可以使用自己熟悉的语言来转换，例如 Javascript 可以使用 [pdfkit](https://github.com/devongovett/pdfkit)。如果觉得麻烦的话也可以把 HTML 文件发给我们来导出 PDF。

<hr>

- 请尊重创作者，勿将此模版源码公开，转卖或上传到第三方平台。
- 如果遇到 HTML 页面的 BUG，请发邮件到 contact@osjobs.net。

