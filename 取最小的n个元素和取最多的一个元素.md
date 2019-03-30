# 取最小的n个元素和取最多的一个元素

```python
import heapq
import collections

D = [{'label':label[i] ,'distance': distance(trainData[i], testData)} for i in range(trainData.shape[0])]
need = heapq.nsmallest(k, D, key= lambda s : s['distance'])
realResult = [x["label"] for x in need]
result = collections.Counter(realResult)
result = result.most_common()[0][0]


```

