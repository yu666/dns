# DeleteDomainRecord {#doc_api_Alidns_DeleteDomainRecord .reference}

调用DeleteDomainRecord根据传入参数删除解析记录。

## 调试 {#api_explorer .section}

[您可以在OpenAPI Explorer中直接运行该接口，免去您计算签名的困扰。运行成功后，OpenAPI Explorer可以自动生成SDK代码示例。](https://api.aliyun.com/#product=Alidns&api=DeleteDomainRecord&type=RPC&version=2015-01-09)

## 请求参数 {#parameters .section}

|名称|类型|是否必选|示例值|描述|
|--|--|----|---|--|
|Action|String|是|DeleteDomainRecord|系统规定参数。取值：**DeleteDomainRecord**。

 |
|RecordId|String|是|9999985|解析记录的ID。

 此参数在添加解析时会返回，在获取域名解析列表时会返回。

 |
|AccessKeyId|String|否|your\_accesskey\_id|您的AccessKey ID。

 |
|Lang|String|否|en|语言。

 |
|UserClientIp|String|否|1.1.1.1|用户端IP。

 |

## 返回数据 {#resultMapping .section}

|名称|类型|示例值|描述|
|--|--|---|--|
|RecordId|String|9999985|解析记录的ID。

 |
|RequestId|String|536E9CAD-DB30-4647-AC87-AA5CC38C5382|请求ID。

 |

## 示例 {#demo .section}

请求示例

``` {#request_demo}

http(s)://alidns.aliyuncs.com/?Action=DeleteDomainRecord
&RecordId=9999985
&<公共请求参数>

```

正常返回示例

`XML` 格式

``` {#xml_return_success_demo}
<DeleteDomainRecordResponse>
      <RequestId>536E9CAD-DB30-4647-AC87-AA5CC38C5382</RequestId>
      <RecordId>9999985</RecordId>
</DeleteDomainRecordResponse>
```

`JSON` 格式

``` {#json_return_success_demo}
{
	"RecordId":"9999985",
	"RequestId":"536E9CAD-DB30-4647-AC87-AA5CC38C5382"
}
```

## 错误码 { .section}

访问[错误中心](https://error-center.aliyun.com/status/product/Alidns)查看更多错误码。

