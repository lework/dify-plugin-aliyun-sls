# Alibaba Cloud Log Service (SLS) plugin

**Author:** lework
**Version:** 0.0.2
**Type:** tool
**REPO:** [dify-plugin-aliyun-sls](https://github.com/lework/dify-plugin-aliyun-sls)

This is a Dify plugin for querying log data in Alibaba Cloud Log Service (SLS).

## Function

- Query log data in Alibaba Cloud SLS Log Service
- Supports specifying query statements, log libraries, time ranges and other parameters
- Supports custom query result quantity limits

## Configuration

To use this plugin, you need to provide the following Alibaba Cloud credentials:

- Endpoint: Endpoint of Alibaba Cloud SLS service, for example: cn-hangzhou.log.aliyuncs.com
- Access Key ID: Access Key ID of Alibaba Cloud account
- Access Key Secret: Access Key Secret of Alibaba Cloud account
- Project: Project name of Alibaba Cloud SLS
- Logstore (optional): Log library name of Alibaba Cloud SLS, which can also be specified when querying

## Usage examples

```
Query logs containing "error" in the last 15 minutes
```

```
Query all logs in the last 1 hour in logstore "nginx-access", and limit the return to 50
```

## Query syntax

Supports query syntax of Alibaba Cloud SLS, for details, please refer to [Alibaba Cloud SLS Query syntax documentation](https://help.aliyun.com/document_detail/29060.html).
