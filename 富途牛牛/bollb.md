### BOLLB

布林带百分比

#### 描述：

布林带百分比是。。。。。。

#### 参数：

| 参数名   | 参数值 | 最大值 | 最小值   |
|-------|-----|-----|-------|
| SD    | 20  | 120 | 1     |
| WIDTH | 2   | 50  | 0.001 |

#### 代码：

```
DIS:=STDP(CLOSE,SD);
MID:=MA(CLOSE,SD);
UPPER:=MID+WIDTH*DIS;
LOWER:=MID-WIDTH*DIS;
BBR:(CLOSE-LOWER)/(UPPER-LOWER),COLOR26A69A;

1,COLOR787B86,DOTLINE;
0,COLOR787B86,DOTLINE;
0.5,COLORRED,DOTLINE;
```

编辑页面图片：
![bollb.png](image%2Fbollb.png)

