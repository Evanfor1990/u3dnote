## RectTransform

* Anchor  
```
|          top  (1,1)
|          |   *anchor.max 
|          +-- right
| left                        
| -- +
|    | bottom
| * anchor.minx
(0,0)---------
```

* Render Mode

1. screen space-overlay :理解为在屏幕上贴一层膜，在一切物体之上
2. screen space-camera：附着在camera上
3. world space：相当于一个GameObject 可被遮挡
