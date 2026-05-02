# OrganizationsServersStoreRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** |  |
**provider** | **string** |  |
**credential_id** | **int** |  | [optional]
**team_id** | **int** |  | [optional]
**type** | [**\Dimer47\LaravelForgeSdk\Model\ServerType**](ServerType.md) |  |
**ubuntu_version** | **string** |  |
**php_version** | [**\Dimer47\LaravelForgeSdk\Model\PhpVersion**](PhpVersion.md) |  | [optional]
**database_type** | [**\Dimer47\LaravelForgeSdk\Model\DatabaseType**](DatabaseType.md) |  | [optional]
**recipe_id** | **int** |  | [optional]
**tags** | **string[]** |  | [optional]
**aws** | [**\Dimer47\LaravelForgeSdk\Model\CreateServerRequestAws**](CreateServerRequestAws.md) |  | [optional]
**ocean2** | [**\Dimer47\LaravelForgeSdk\Model\CreateServerRequestOcean2**](CreateServerRequestOcean2.md) |  | [optional]
**hetzner** | [**\Dimer47\LaravelForgeSdk\Model\OrganizationsServersStoreRequestAllOfHetzner**](OrganizationsServersStoreRequestAllOfHetzner.md) |  | [optional]
**vultr** | [**\Dimer47\LaravelForgeSdk\Model\CreateServerRequestVultr**](CreateServerRequestVultr.md) |  | [optional]
**akamai** | [**\Dimer47\LaravelForgeSdk\Model\CreateServerRequestAkamai**](CreateServerRequestAkamai.md) |  | [optional]
**laravel** | [**\Dimer47\LaravelForgeSdk\Model\OrganizationsServersStoreRequestAllOfLaravel**](OrganizationsServersStoreRequestAllOfLaravel.md) |  | [optional]
**custom** | [**\Dimer47\LaravelForgeSdk\Model\CreateServerRequestCustom**](CreateServerRequestCustom.md) |  | [optional]
**add_key_to_source_control** | **bool** |  | [optional] [default to true]
**database** | **string** |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
