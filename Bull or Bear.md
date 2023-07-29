# Bull or Bear

```python
# cook your dish here
t = int(input())
for _ in range (t):
    X,Y = map(int,input().split())
    if X>Y:
        print("LOSS")
    elif X<Y:
        print("PROFIT")
    else:
        print("NEUTRAL")
```