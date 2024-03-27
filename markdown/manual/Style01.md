# 高さによる色分け For Plateau building 3D Tiles

```jsx
{
  "3dtiles": {
    "color": {
      "expression": {
        "conditions": [
          [
            "${計測高さ}>=180",
            "color('#F9FD4C')"
          ],
          [
            "${計測高さ}>=120",
            "color('#F6CD3D')"
          ],
          [
            "${計測高さ}>=60",
            "color('#EBD384')"
          ],
          [
            "${計測高さ}>=31",
            "color('#9E79BA')"
          ],
          [
            "${計測高さ}>=12",
            "color('#5230C2')"
          ],
          [
            "true",
            "color('#362C52')"
          ]
        ]
      }
    },
    "colorBlendMode": "highlight",
    "pbr": false,
    "shadows": "disabled"
  }
}
```

