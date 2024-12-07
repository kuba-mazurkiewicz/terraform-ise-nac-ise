## 0.1.2

- Add `parent_group` attribute to `user_identity_group`
- Support new `*_update_rank` resources to allow changing the rank of policy sets or rules without impacting existing configurations
- Support active directory configurations without groups
- Added support for managing endpoints
- Added support for default user identity groups assignment under internal users
- Fix incorrect description attribute of `network_device_groups` configuration
- BREAKING CHANGE: `endpoint_identity_groups` and `user_identity_groups` now support nested children in favor of `parent` references

## 0.1.1

- Fix issue with error due to missing settings for `allowed_protocols` and EAP-TLS stateless session resume
- Add support for active directory configuration
- Added `ise_identity_source_sequence` support
- BREAKING CHANGE: Split `attribute_name` to `dictionary_name` and `attribute_name`
- BREAKING CHANGE: Removed `manage_*` variables
- Allow updating default policy sets and rules

## 0.1.0

- Initial release
