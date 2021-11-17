#### 包使用教程

在文件内导入包

```typescript
import Upload from 'vue-wyl-upload';

components:{
    Upload
}

<Upload :filename="xxx" :filesize="xxx" :uploadSpeed="xxx" :percentage="xxx" :uploaded="xxx"></Upload>
```

需要传入的参数props

`filename`： 文件名称

`filesize`： 文件大小

`uploadSpeed`： 上传速度

`percentage`： 上传进度

`uploaded`： 图片上传完毕

