# calculation_api

All URIs are relative to *http://127.0.0.1:8080*

Method | HTTP request | Description
------------- | ------------- | -------------
**getCalc**](calculation_api.md#getCalc) | **PUT** /calc | Get result of calculation


# **getCalc**
> models::CalculationResult getCalc(calculation)
Get result of calculation

Server calculates value and returns result

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
  **calculation** | [**Calculation**](Calculation.md)| Get calculated result of expression entered | 

### Return type

[**models::CalculationResult**](CalculationResult.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, application/xml, application/x-www-form-urlencoded
 - **Accept**: application/json, application/xml

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

