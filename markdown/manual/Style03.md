# インフォボックスも含めてエクスポートしたマーカーの色・サイズ・画像適用

（※）「Marker to GeoJSON」でエクスポートした【インフォボックス付きマーカー】に対応。それ以外のエクスポート方法で出力したデータには非対応のため、「（サンプル）ポイントの色・サイズの変更」を使用する

```jsx
{
  "marker": {
    "height": {
      "expression": "${reearthClassicMarker.height}"
    },
    "heightReference": {
      "expression": "${reearthClassicMarker.heightReference}"
    },
    "image": {
      "expression": "${reearthClassicMarker.image}"
    },
    "imageSize": {
      "expression": "${reearthClassicMarker.imageSize}"
    },
    "imageSizeInMeters": {
      "expression": "${reearthClassicMarker.imageSizeInMeters}"
    },
    "pointColor": {
      "expression": "${reearthClassicMarker.pointColor}"
    },
    "pointOutlineColor": {
      "expression": "${reearthClassicMarker.pointOutlineColor}"
    },
    "pointOutlineWidth": {
      "expression": "${reearthClassicMarker.pointOutlineWidth}"
    },
    "pointSize": {
      "expression": "${reearthClassicMarker.pointSize}"
    },
    "style": {
      "expression": "${reearthClassicMarker.style}"
    }
  }
}
```

