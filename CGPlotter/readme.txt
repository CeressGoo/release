主程序：./main/CGPlotter_v0.1.py
建议使用python 3.8.8及以上的版本打开

data、graph、main、report四个文件夹不可以删除

【使用说明】
1. 	将需要作图的数据文件放入data文件夹；
	数据文件仅支持.csv和.txt格式，运行程序前需确保数据文件仅包含数据，如果有说明文字的话必须全部删除（如有的仪器会记录一大堆测试条件和参数，全部删掉，仅保留波长和强度两列数据即可）
	默认会把所有放入data文件夹的数据文件叠到一张图上，所以如果需要作一个文件的图，就一次只放一个。

2. 	运行CGPlotter_v0.1.py；
	装了编程环境的可以用自己喜欢的环境打开，只装了python的可以在main文件夹shift+右键，选择“在此处打开powershell”，在弹出的窗口输入“python CGPlotter_v0.1.py”即可

3. 	程序开始运行后，会提示输入数据文件类型(txt or csv)，是否归一化，以及你的样品名称；依次键入后回车；

4. 	作好的图放在graph文件夹，峰位置和峰强度在report文件夹。
	默认会把所有放入data文件夹的数据文件叠到一张图上，所以如果需要作一个文件的图，就一次只放一个。





5. 	（想把这东西做成一个傻瓜式的应用程序好难。。。。有能力的还是自己调代码吧= =或者你觉得这代码太垃圾的话就教教我更高级的算法吧 菜鸡感谢.jpg）
