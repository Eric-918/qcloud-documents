>?三代测序 Falcon 加速服务当前只在腾讯云北京地区提供服务，用户在使用本服务时，请先在双螺旋控制台创建一个北京地区的项目，并将原始数据文件上传至该项目。完成以上两个步骤后，用户可创建 Falcon 加速作业。

## 操作步骤
### 创建一个北京地区的项目
如您之前已创建过北京地区项目，请直接进入下一步。
1. 进入 [双螺旋控制台](https://console.cloud.tencent.com/helix/overview) 后，单击进入项目管理页面。
2. 单击【新建项目】，创建一个位于北京地区的项目。



### 上传原始数据
如您之前已将原始文件上传至北京地区，请直接进入下一步。
1. 单击进入【数据管理】>【私有文件】页面，项目下拉框中，选择刚才对应的项目，进入计划用于存放数据的文件夹。
![](https://main.qcloudimg.com/raw/d599ac726d48520bc152b94ac018ab06.png)
2. 单击【上传文件】，弹出上传文件对话框，单击【选择文件】，在对话框中选择要上传的本地原始数据文件，再单击【确认上传】将文件上传至云端。
![上传文件对话框](https://main.qcloudimg.com/raw/51c21336031d859ff26b62c0bbaeb5fa.png)

###  提交 Falcon 作业  
1.上传好原始数据后，单击进入【作业管理】页面，在项目下拉列表中选择对应的项目后，单击【新建作业】。
![新建作业](https://main.qcloudimg.com/raw/c394446f721fe68258937300f78764f1.png)
2. 在弹出的作业对话框中，选择 Falcon 作业。
3. 进入新建作业详情页后，按如下步骤操作：
 - 创建作业名称；
 - 在【输入配置】中选择原始数据所在目录；
 - 在【输出配置】中编辑结果文件存放目录，默认为 /stdout/,作业运行完成后，结果文件将自动写入结果存放目录；
 - 在【参数配置】中选择本次作业的参数配置文件；
 - 勾选授权许可，只有在获得您的许可后，双螺旋平台才可以在作业执行期间，临时访问您制定的文件存放目录，拉取原始数据文件进行计算，并在计算完成后，临时访问文件写入目录，写入结果文件；
4. 单击【启动作业】，完成 Falcon 作业提交。
![新建作业3](https://main.qcloudimg.com/raw/c64f2926c7e287befd7ff106b4c33306.png)
