# 根据贵州冠状肺炎疫情制作的大屏展示
大屏展示数据由个人录入

## epidemic-prevention

## 项目部署
参照 [Configuration Reference](https://cli.vuejs.org/zh/guide/deployment.html#docker-nginx)


### JSON配置细项
> 打开dist文件夹js目录 -- data.json


---


####字段说明如下


*grandTotal -- 累计人数（大屏中上）
  heat_person -- 累计发热人数
  sickKey_person -- 重点患者
  suspect_person -- 疑似人数


*openData -- 贵阳公开数据（大屏左上）
  openPatients -- 公开确诊、治愈、死亡
  openCompare -- 相比昨日增加人数


*sampleData -- 疫情预警管理（大屏右上）
  accept -- 接受样本数量
  detection -- 检测样本数量
  positive -- 阳性人数
  negtive -- 阴性人数
  stay_out -- 待出结果
  others -- 其他流感



*keyPatient -- 最新重点患者(大屏右侧)
  _请按照数组顺序来填写字段_


## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
