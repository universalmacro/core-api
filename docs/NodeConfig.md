# NodeConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Database** | Pointer to [**DBConfig**](DBConfig.md) |  | [optional] 
**Redis** | Pointer to [**RedisConfig**](RedisConfig.md) |  | [optional] 

## Methods

### NewNodeConfig

`func NewNodeConfig() *NodeConfig`

NewNodeConfig instantiates a new NodeConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNodeConfigWithDefaults

`func NewNodeConfigWithDefaults() *NodeConfig`

NewNodeConfigWithDefaults instantiates a new NodeConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDatabase

`func (o *NodeConfig) GetDatabase() DBConfig`

GetDatabase returns the Database field if non-nil, zero value otherwise.

### GetDatabaseOk

`func (o *NodeConfig) GetDatabaseOk() (*DBConfig, bool)`

GetDatabaseOk returns a tuple with the Database field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatabase

`func (o *NodeConfig) SetDatabase(v DBConfig)`

SetDatabase sets Database field to given value.

### HasDatabase

`func (o *NodeConfig) HasDatabase() bool`

HasDatabase returns a boolean if a field has been set.

### GetRedis

`func (o *NodeConfig) GetRedis() RedisConfig`

GetRedis returns the Redis field if non-nil, zero value otherwise.

### GetRedisOk

`func (o *NodeConfig) GetRedisOk() (*RedisConfig, bool)`

GetRedisOk returns a tuple with the Redis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedis

`func (o *NodeConfig) SetRedis(v RedisConfig)`

SetRedis sets Redis field to given value.

### HasRedis

`func (o *NodeConfig) HasRedis() bool`

HasRedis returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


