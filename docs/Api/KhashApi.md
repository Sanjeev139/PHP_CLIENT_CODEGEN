# PhpApi\KhashApi

All URIs are relative to *http://localhost:51122*

Method | HTTP request | Description
------------- | ------------- | -------------
[**khashGetKey**](KhashApi.md#khashGetKey) | **GET** /get-key/{key} | 
[**khashHashGiftCard**](KhashApi.md#khashHashGiftCard) | **GET** /hash-gift-card/{merchantid}/{card} | 
[**khashHashPaymentToken**](KhashApi.md#khashHashPaymentToken) | **GET** /hash-payment-token/{card} | 


# **khashGetKey**
> string khashGetKey($key)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new PhpApi\Api\KhashApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$key = "key_example"; // string | 

try {
    $result = $apiInstance->khashGetKey($key);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling KhashApi->khashGetKey: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **key** | **string**|  |

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **khashHashGiftCard**
> string khashHashGiftCard($merchantid, $card)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new PhpApi\Api\KhashApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$merchantid = 56; // int | 
$card = "card_example"; // string | 

try {
    $result = $apiInstance->khashHashGiftCard($merchantid, $card);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling KhashApi->khashHashGiftCard: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **merchantid** | **int**|  |
 **card** | **string**|  |

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **khashHashPaymentToken**
> string khashHashPaymentToken($card)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new PhpApi\Api\KhashApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$card = "card_example"; // string | 

try {
    $result = $apiInstance->khashHashPaymentToken($card);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling KhashApi->khashHashPaymentToken: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **card** | **string**|  |

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

