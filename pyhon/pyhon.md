

# Python

- np.random.normal()函数用于生成正态分布函数，有三个参数。第一个参数是随机数的期望值，对应的是整个分布的中心；第二个是随机数的标准差，数越大越矮胖；第三个数是生成随机数的个数，默认为NONE，则只输出一个数
- shape（）函数的功能是读取矩阵或数组的长度，shape（0）是读取行数，shape（1）是读取列数


### 爬虫

```ptthon
import requests

req = requests.get('https://rate.bot.com.tw/xrt?Lang=zh-TW')
#
print(req.text)
```





```python
import pandas

dfs = pandas.read_html('https://rate.bot.com.tw/xrt?Lang=zh-TW')

print(dfs[0])
```
