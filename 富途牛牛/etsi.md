### ETSI

#### 描述：

ETSI是。。。。。。

#### 参数：

| 参数名   | 参数值 | 最大值  | 最小值 |
|-------|-----|------|-----|
| LONG  | 20  | 1000 | 1   |
| SHORT | 5   | 1000 | 1   |

#### 代码：

```
M:=REF(CLOSE,0)-REF(CLOSE,1)
E:100*EMA(EMA(M,LONG),SHORT)/EMA(EMA(ABS(M),LONG),SHORT),COLOR2962FF;
S:EMA(E,SHORT),COLORFF6D00;
```

编辑页面图片：
![etsi.png](image%2Fetsi.png)
