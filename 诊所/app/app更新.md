# App更新

> 更新记录

<table>
    <tr>
        <th style="width:250px;">日期</th>
        <th>更新内容</th>
    </tr>
    <tr>
        <td>2018-06-04 10:53:38</td>
        <td>生成时间</td>
    </tr>
</table>

> 字段

<table>
    <tr>
        <th style="width:150px;">名称</th>
        <th style="width:60px;">类型</th>
        <th style="width:200px;">说明</th>
        <th>备注</th>
    </tr>
    <tr>
        <td>version</td>
        <td>string</td>
        <td>版本</td>
        <td>-</td>
    </tr>
    <tr>
        <td>versionCode</td>
        <td>int</td>
        <td>版本号</td>
        <td>-</td>
    </tr>
    <tr>
        <td>updateContent</td>
        <td>string</td>
        <td>更新内容</td>
        <td>-</td>
    </tr>
    <tr>
        <td>forceUpdate</td>
        <td>bool</td>
        <td>是否强制更新</td>
        <td>-</td>
    </tr>
    <tr>
        <td>downloadUrl</td>
        <td>string</td>
        <td>文件下载地址</td>
        <td>-</td>
    </tr>
    <tr>
        <td>remark</td>
        <td>string</td>
        <td>备注</td>
        <td>-</td>
    </tr>
</table>

## App更新列表

```
GET /clinic/app/v1/version
```
> 请求参数

<table>
    <tr>
        <th style="width:150px;">属性名称</th>
        <th style="width:60px;">类型</th>
        <th style="width:60px;">必填</th>
        <th style="width:200px;">说明</th>
    </tr>
    <tr>
        <td>version</td>
        <td>string</td>
        <td>是</td>
        <td>当前版本</td>
    </tr>
    <tr>
        <td>versionCode</td>
        <td>int</td>
        <td>是</td>
        <td>当前版本号</td>
    </tr>
</table>
