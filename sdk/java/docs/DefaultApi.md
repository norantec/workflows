# DefaultApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**kvDeletePost**](DefaultApi.md#kvDeletePost) | **POST** /kv/delete |  |
| [**kvGetPost**](DefaultApi.md#kvGetPost) | **POST** /kv/get |  |
| [**kvSetPost**](DefaultApi.md#kvSetPost) | **POST** /kv/set |  |
| [**lockGetPost**](DefaultApi.md#lockGetPost) | **POST** /lock/get |  |
| [**lockSetnxPost**](DefaultApi.md#lockSetnxPost) | **POST** /lock/setnx |  |


<a id="kvDeletePost"></a>
# **kvDeletePost**
> KvSetPost200Response kvDeletePost(kvGetPostRequest)



### Example
```java
// Import classes:
import com.norantec.workersdk.ApiClient;
import com.norantec.workersdk.ApiException;
import com.norantec.workersdk.Configuration;
import com.norantec.workersdk.models.*;
import com.norantec.workersdk.api.DefaultApi;

public class Example {
  public static void main(String[] args) {
    ApiClient defaultClient = Configuration.getDefaultApiClient();
    defaultClient.setBasePath("http://localhost");

    DefaultApi apiInstance = new DefaultApi(defaultClient);
    KvGetPostRequest kvGetPostRequest = new KvGetPostRequest(); // KvGetPostRequest | 
    try {
      KvSetPost200Response result = apiInstance.kvDeletePost(kvGetPostRequest);
      System.out.println(result);
    } catch (ApiException e) {
      System.err.println("Exception when calling DefaultApi#kvDeletePost");
      System.err.println("Status code: " + e.getCode());
      System.err.println("Reason: " + e.getResponseBody());
      System.err.println("Response headers: " + e.getResponseHeaders());
      e.printStackTrace();
    }
  }
}
```

### Parameters

| Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **kvGetPostRequest** | [**KvGetPostRequest**](KvGetPostRequest.md)|  | |

### Return type

[**KvSetPost200Response**](KvSetPost200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** |  |  -  |

<a id="kvGetPost"></a>
# **kvGetPost**
> KvGetPost200Response kvGetPost(kvGetPostRequest)



### Example
```java
// Import classes:
import com.norantec.workersdk.ApiClient;
import com.norantec.workersdk.ApiException;
import com.norantec.workersdk.Configuration;
import com.norantec.workersdk.models.*;
import com.norantec.workersdk.api.DefaultApi;

public class Example {
  public static void main(String[] args) {
    ApiClient defaultClient = Configuration.getDefaultApiClient();
    defaultClient.setBasePath("http://localhost");

    DefaultApi apiInstance = new DefaultApi(defaultClient);
    KvGetPostRequest kvGetPostRequest = new KvGetPostRequest(); // KvGetPostRequest | 
    try {
      KvGetPost200Response result = apiInstance.kvGetPost(kvGetPostRequest);
      System.out.println(result);
    } catch (ApiException e) {
      System.err.println("Exception when calling DefaultApi#kvGetPost");
      System.err.println("Status code: " + e.getCode());
      System.err.println("Reason: " + e.getResponseBody());
      System.err.println("Response headers: " + e.getResponseHeaders());
      e.printStackTrace();
    }
  }
}
```

### Parameters

| Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **kvGetPostRequest** | [**KvGetPostRequest**](KvGetPostRequest.md)|  | |

### Return type

[**KvGetPost200Response**](KvGetPost200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** |  |  -  |

<a id="kvSetPost"></a>
# **kvSetPost**
> KvSetPost200Response kvSetPost(kvSetPostRequest)



### Example
```java
// Import classes:
import com.norantec.workersdk.ApiClient;
import com.norantec.workersdk.ApiException;
import com.norantec.workersdk.Configuration;
import com.norantec.workersdk.models.*;
import com.norantec.workersdk.api.DefaultApi;

public class Example {
  public static void main(String[] args) {
    ApiClient defaultClient = Configuration.getDefaultApiClient();
    defaultClient.setBasePath("http://localhost");

    DefaultApi apiInstance = new DefaultApi(defaultClient);
    KvSetPostRequest kvSetPostRequest = new KvSetPostRequest(); // KvSetPostRequest | 
    try {
      KvSetPost200Response result = apiInstance.kvSetPost(kvSetPostRequest);
      System.out.println(result);
    } catch (ApiException e) {
      System.err.println("Exception when calling DefaultApi#kvSetPost");
      System.err.println("Status code: " + e.getCode());
      System.err.println("Reason: " + e.getResponseBody());
      System.err.println("Response headers: " + e.getResponseHeaders());
      e.printStackTrace();
    }
  }
}
```

### Parameters

| Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **kvSetPostRequest** | [**KvSetPostRequest**](KvSetPostRequest.md)|  | |

### Return type

[**KvSetPost200Response**](KvSetPost200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** |  |  -  |

<a id="lockGetPost"></a>
# **lockGetPost**
> KvGetPost200Response lockGetPost(lockGetPostRequest)



### Example
```java
// Import classes:
import com.norantec.workersdk.ApiClient;
import com.norantec.workersdk.ApiException;
import com.norantec.workersdk.Configuration;
import com.norantec.workersdk.models.*;
import com.norantec.workersdk.api.DefaultApi;

public class Example {
  public static void main(String[] args) {
    ApiClient defaultClient = Configuration.getDefaultApiClient();
    defaultClient.setBasePath("http://localhost");

    DefaultApi apiInstance = new DefaultApi(defaultClient);
    LockGetPostRequest lockGetPostRequest = new LockGetPostRequest(); // LockGetPostRequest | 
    try {
      KvGetPost200Response result = apiInstance.lockGetPost(lockGetPostRequest);
      System.out.println(result);
    } catch (ApiException e) {
      System.err.println("Exception when calling DefaultApi#lockGetPost");
      System.err.println("Status code: " + e.getCode());
      System.err.println("Reason: " + e.getResponseBody());
      System.err.println("Response headers: " + e.getResponseHeaders());
      e.printStackTrace();
    }
  }
}
```

### Parameters

| Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **lockGetPostRequest** | [**LockGetPostRequest**](LockGetPostRequest.md)|  | |

### Return type

[**KvGetPost200Response**](KvGetPost200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** |  |  -  |

<a id="lockSetnxPost"></a>
# **lockSetnxPost**
> LockSetnxPost200Response lockSetnxPost(lockSetnxPostRequest)



### Example
```java
// Import classes:
import com.norantec.workersdk.ApiClient;
import com.norantec.workersdk.ApiException;
import com.norantec.workersdk.Configuration;
import com.norantec.workersdk.models.*;
import com.norantec.workersdk.api.DefaultApi;

public class Example {
  public static void main(String[] args) {
    ApiClient defaultClient = Configuration.getDefaultApiClient();
    defaultClient.setBasePath("http://localhost");

    DefaultApi apiInstance = new DefaultApi(defaultClient);
    LockSetnxPostRequest lockSetnxPostRequest = new LockSetnxPostRequest(); // LockSetnxPostRequest | 
    try {
      LockSetnxPost200Response result = apiInstance.lockSetnxPost(lockSetnxPostRequest);
      System.out.println(result);
    } catch (ApiException e) {
      System.err.println("Exception when calling DefaultApi#lockSetnxPost");
      System.err.println("Status code: " + e.getCode());
      System.err.println("Reason: " + e.getResponseBody());
      System.err.println("Response headers: " + e.getResponseHeaders());
      e.printStackTrace();
    }
  }
}
```

### Parameters

| Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **lockSetnxPostRequest** | [**LockSetnxPostRequest**](LockSetnxPostRequest.md)|  | |

### Return type

[**LockSetnxPost200Response**](LockSetnxPost200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** |  |  -  |

