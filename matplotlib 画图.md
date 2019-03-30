# matplotlib 画图



```python
import matplotlib.pyplot as plt
plt.plot(result[:, 0], result[:, 1], 'ro-')
plt.xticks(np.arange(1, 15, 2)) # 设置横坐标
plt.show()
# 画点
plt.scatter(datas[:,0], datas[:,2],20.0*labels, 20.0*labels) # 后面是点的颜色
plt.show()








```

