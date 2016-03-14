

以下範例，開啟 加速度計 & 陀螺儀 & 晶片溫度：

```
start

start?acc=open&gyro=open&ic_temp=open // 待討論

start?acc_x=open&acc_y=open&acc_z=open // 待討論

start?acc=100&gyro=000&ic_temp=1 // 待討論

set?acc=100&gyro=000&ic_temp=1 // 待討論

```

停止，不會有任何資料回傳至電腦

```
stop

```

取得版本號

```
設置：version
回傳：1.0.0

```

矽膠桶回傳範例

```json
{
    "acc" : [0.5, 0.5, 0.5],
    "gyro" : [0.5, 0.5, 0.5],
    "ic_temp" : 25,
    "btn_1" : true,
    "btn_2" : false,
    "lp_btn_1" : true,
    "lp_btn_2" : true    
}

```