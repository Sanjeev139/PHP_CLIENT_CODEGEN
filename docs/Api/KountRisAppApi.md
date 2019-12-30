# PhpApi\KountRisAppApi

All URIs are relative to *http://localhost:63021*

Method | HTTP request | Description
------------- | ------------- | -------------
[**kountRisAppPostRis**](KountRisAppApi.md#kountRisAppPostRis) | **POST** /api/KountRisApp | 


# **kountRisAppPostRis**
> \PhpApi\Khash\ResponseModel kountRisAppPostRis($inquiry_model)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new PhpApi\Api\KountRisAppApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$inquiry_model = new \PhpApi\Khash\InquiryModel(); // \PhpApi\Khash\InquiryModel | 

try {
    $result = $apiInstance->kountRisAppPostRis($inquiry_model);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling KountRisAppApi->kountRisAppPostRis: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **inquiry_model** | [**\PhpApi\Khash\InquiryModel**](../Model/InquiryModel.md)|  |

### Return type

[**\PhpApi\Khash\ResponseModel**](../Model/ResponseModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/xml, text/xml, application/x-www-form-urlencoded
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

