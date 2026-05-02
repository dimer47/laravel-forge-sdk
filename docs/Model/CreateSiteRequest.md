# CreateSiteRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | [**\Dimer47\LaravelForgeSdk\Model\SiteType**](SiteType.md) |  |
**domain_mode** | [**\Dimer47\LaravelForgeSdk\Model\CreateSiteRequestDomainMode**](CreateSiteRequestDomainMode.md) |  | [optional]
**name** | [**\Dimer47\LaravelForgeSdk\Model\CreateSiteRequestName**](CreateSiteRequestName.md) |  | [optional]
**www_redirect_type** | [**\Dimer47\LaravelForgeSdk\Model\WwwRedirectType**](WwwRedirectType.md) | The type of &#x60;www&#x60; redirection to apply to the domain. | [optional]
**allow_wildcard_subdomains** | **bool** | Whether to allow wildcard subdomains for the domain. | [optional]
**root_directory** | **string** |  | [optional]
**web_directory** | **string** |  | [optional]
**is_isolated** | **bool** |  | [optional]
**isolated_user** | **string** |  | [optional]
**php_version** | [**\Dimer47\LaravelForgeSdk\Model\PhpVersion**](PhpVersion.md) |  | [optional]
**zero_downtime_deployments** | **bool** |  | [optional]
**nginx_template_id** | **int** |  | [optional]
**source_control_provider** | [**\Dimer47\LaravelForgeSdk\Model\SourceControlProvider**](SourceControlProvider.md) |  | [optional]
**repository** | **string** |  | [optional]
**branch** | **string** |  | [optional]
**database_id** | **int** | The ID of the database to use with the site. | [optional]
**database_user_id** | **int** | The ID of the database user to use with the site. | [optional]
**statamic_setup** | **string** | The type of setup for Statmic apps. | [optional]
**statamic_starter_kit** | **string** | The starter kit for the Statamic app. | [optional]
**statamic_super_user_email** | **string** |  | [optional]
**statamic_super_user_password** | **string** |  | [optional]
**install_composer_dependencies** | **bool** |  | [optional]
**generate_deploy_key** | **bool** |  | [optional]
**public_deploy_key** | **string** |  | [optional]
**private_deploy_key** | **string** |  | [optional]
**frontend_package_manager** | **string** | The package manager for frontend applications. | [optional]
**frontend_build_command** | **string** | The build command for frontend assets. | [optional]
**nuxt_next_mode** | **string** | The render mode for Next/Nuxt applications. | [optional]
**nuxt_next_port** | **int** | The port used for Next/Nuxt applications. | [optional]
**push_to_deploy** | **bool** | Automatically trigger a new deployment when changes are pushed to the environment&#39;s Git branch. | [optional] [default to false]
**tags** | **string[]** |  | [optional]
**shared_paths** | [**\Dimer47\LaravelForgeSdk\Model\CreateSiteRequestSharedPathsInner[]**](CreateSiteRequestSharedPathsInner.md) | A list of files or directories to be shared between releases for zero-downtime deployments. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
