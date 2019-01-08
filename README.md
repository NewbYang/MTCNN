# MTCNN

Caffe之python接口配置  
1、安装python2.7,下载caffe;  
2、修改caffe-master文件夹下配置文件CommonSettings.props  
         python support：true    
         pythondir：C:\Python27  
3、编译caffe python接口  
4、将caffe-master/Build/x64/Release/pycaffe中的caffe文件夹拷贝到C:\Python27\Lib\site-packages路径下  
   在命令行中  
   进入python  
   import caffe确认caffe是否引入成功  
 5、运行
