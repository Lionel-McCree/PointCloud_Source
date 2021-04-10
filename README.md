# PointNet_Source
Some papers and some codes I collected...  
· Latent T angent Space Representation forNormal Estimation  
编码器类似PCPNet，对称函数使用了加权平均，解码器回归的是一系列（接近）切平面的点，用类似RANSAC的方法随机采样生成法线，取最优。
