# RapeseedRecognition
这是油菜花识别项目代码 
目前把原始的代码放在master分支上。
之后也可以新建自己的分支。
大家可以提交代码到这里方便沟通交流

# Task
一、2m单通道图像和8m rgb三通道 8bit对比 训练模型效果  
二、8m四通道图像 训练模型效果 （初始代码为 Image.open(os.path.join(self.img_dir, path)).convert('RGB') 在datasets下的coco.py中）  
三、将2m和8m图像拼接输入 训练模型  
四、增加1*1的bottleneck layer，提取不同色彩通道之间的相互关系 ，与不添加bottleneck layer 的效果进行对比  
