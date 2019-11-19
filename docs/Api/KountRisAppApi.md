# PhpApi\KountRisAppApi

All URIs are relative to *http://localhost:51122*

Method | HTTP request | Description
------------- | ------------- | -------------
[**kountRisAppDelete**](KountRisAppApi.md#kountRisAppDelete) | **DELETE** /api/KountRisApp/{id} | 
[**kountRisAppGet**](KountRisAppApi.md#kountRisAppGet) | **GET** /api/KountRisApp | 
[**kountRisAppGetSayHi**](KountRisAppApi.md#kountRisAppGetSayHi) | **GET** /get-say-hi/{name} | 
[**kountRisAppGet_0**](KountRisAppApi.md#kountRisAppGet_0) | **GET** /api/KountRisApp/{id} | 
[**kountRisAppPost**](KountRisAppApi.md#kountRisAppPost) | **POST** /api/KountRisApp | 
[**kountRisAppPut**](KountRisAppApi.md#kountRisAppPut) | **PUT** /api/KountRisApp/{id} | 


# **kountRisAppDelete**
> kountRisAppDelete($id)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new PhpApi\Api\KountRisAppApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$id = 56; // int | 

try {
    $apiInstance->kountRisAppDelete($id);
} catch (Exception $e) {
    echo 'Exception when calling KountRisAppApi->kountRisAppDelete: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **int**|  |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **kountRisAppGet**
> string kountRisAppGet()



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new PhpApi\Api\KountRisAppApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->kountRisAppGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling KountRisAppApi->kountRisAppGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters
This endpoint does not need any parameter.

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **kountRisAppGetSayHi**
> string kountRisAppGetSayHi($name)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new PhpApi\Api\KountRisAppApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$name = "name_example"; // string | 

try {
    $result = $apiInstance->kountRisAppGetSayHi($name);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling KountRisAppApi->kountRisAppGetSayHi: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **string**|  |

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **kountRisAppGet_0**
> string kountRisAppGet_0($id)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new PhpApi\Api\KountRisAppApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$id = 56; // int | 

try {
    $result = $apiInstance->kountRisAppGet_0($id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling KountRisAppApi->kountRisAppGet_0: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **int**|  |

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **kountRisAppPost**
> string kountRisAppPost($_product_details)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new PhpApi\Api\KountRisAppApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$_product_details = new \PhpApi\Khash\ProductDetails(); // \PhpApi\Khash\ProductDetails | 

try {
    $result = $apiInstance->kountRisAppPost($_product_details);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling KountRisAppApi->kountRisAppPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **_product_details** | [**\PhpApi\Khash\ProductDetails**](../Model/ProductDetails.md)|  |

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/xml, text/xml, application/x-www-form-urlencoded
 - **Accept**: application/json, text/json, application/xml, text/xml

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **kountRisAppPut**
> kountRisAppPut($id, $value)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new PhpApi\Api\KountRisAppApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$id = 56; // int | 
$value = "value_example"; // string | 

try {
    $apiInstance->kountRisAppPut($id, $value);
} catch (Exception $e) {
    echo 'Exception when calling KountRisAppApi->kountRisAppPut: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **int**|  |
 **value** | **string**|  |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/xml, text/xml, application/x-www-form-urlencoded
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

