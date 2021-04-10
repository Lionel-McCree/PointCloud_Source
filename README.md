# PointNet_Source
Some papers and some codes I collected...  
· Latent T angent Space Representation forNormal Estimation  
用于法线估计。编码器类似PCPNet，对称函数使用了加权平均，解码器回归的是一系列（接近）切平面的点，用类似RANSAC的方法随机采样生成法线，取最优。  
· PU-Net: Point Cloud Upsampling Network  
用于点云上采样。补丁提取，逐层提取特征（再进行聚合），用多个卷积对聚合特征进行计算以扩展特征，用扩展后的特征回归坐标。
