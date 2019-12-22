---
title: Config Options for powershell
sidebar_label: powershell
---

| Option | Description | Values | Default |
| ------ | ----------- | ------ | ------- |
|packageName|Client package name (e.g. org.openapitools.client).| |Org.OpenAPITools|
|packageGuid|GUID for PowerShell module (e.g. a27b908d-2a20-467f-bc32-af6f3a654ac5). A random GUID will be generated by default.| |null|
|csharpClientPath|Path to the C# API client generated by OpenAPI Generator, e.g. $ScriptDir\..\csharp\OpenAPIClient where $ScriptDir is the current directory. NOTE: you will need to generate the C# API client separately.| |$ScriptDir\csharp\OpenAPIClient|