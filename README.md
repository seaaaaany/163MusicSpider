# 163MusicSpider

This tiny program enables you to download your favorite 163 music playlists. To achieve this goal, following the steps as follow:

1. Get the id of your 163 playlist. To get it, you should open the page of the playlist in a browser then copy the numbers behind "music.163.com/#/playlist?id=" in address bar.
2. Download the python script to your computer and make sure you have Python installed.
3. Run the script by double clicking it. Be careful that you need to run the script whose name is matched with your local Python version. Alternative method is recommended.
4. Open the .txt file right next to the scirpt and select all then copy. Then open [this site](http://spotlistr.herokuapp.com/#/search/textbox) and it will convert the playlist for you. Note: the API 163 provided have the limit of reading 1000 songs in your playlist.





## 网易云音乐Spider


程序旨在帮助你爬取到，网易云上你喜欢的歌单的所有的歌曲信息。 步骤如下：

1. 在浏览器打开你的网易云歌单，复制你的歌单网址中，位于 "music.163.com/#/playlist?id=" 后方的数字。
2. 下载本脚本，并且确保本地机器已安装Python
3. 双击脚本，运行脚本。你只需要运行和你的本地Python版本一样的脚本即可。
4. 歌单保存到本地的.txt文件中。 注意：网易云音乐歌单只允许加载1000首歌曲。



## 如何将网易云音乐歌单导入Spotify？

由于网易云提供的API不定期犯抽，于是利用dongyonghui写的API完成了新的方法，点击[这里](https://github.com/bjason/163MusicToSpotify/blob/master/www.dongyonghui.com/default/20180128-%E7%BD%91%E6%98%93%E4%BA%91%E3%80%81%E9%85%B7%E7%8B%97%E3%80%81QQ%E9%9F%B3%E4%B9%90%E6%AD%8C%E5%8D%95%E6%8E%A5%E5%8F%A3API.html)查看该API的说明。

###### 步骤

1. 得到歌单ID：从浏览器进入到你的歌单，复制地址栏中"music.163.com/#/playlist?id="后面的数字。
2. 进入到[这个页面](https://github.com/bjason/163MusicToSpotify)下载相应的Python文件，请确保电脑上已经正确安装Python。如果电脑上安装了Python2，请下载[AlternativeMethodForPy2.py](https://github.com/bjason/163MusicToSpotify/blob/master/AlternativeMethodForPy2.py)，Python3则下载AlternativeMethodForPy3.py。如果想尝试之前的方法，请下载Python2.py或Python3.py。
3. 运行文件并输入你刚刚获得的歌单ID，看到成功提示后在相同目录下可以看到一个以歌单ID命名的.txt文件。
4. 打开[这个网站](http://spotlistr.herokuapp.com/#/search/textbox)并粘贴.txt中的全部内容，等待其自动识别并创建歌单。