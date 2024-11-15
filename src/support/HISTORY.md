Release History
===============

2.0.1
-----
* Remove dependency on msrestazure

2.0.0
-----
* Upgrade CLI Support extension to new Support RP API 2024-04-01
* Remove command groups `support tickets`
* Add command groups `support in-subscription`
* Add command groups `support no-subscription` 

1.0.4
-----
* Add deprecated message for commands before new upcoming version

1.0.3
-----
* Migrate to track 2 SDK

1.0.2
-----
* Removed custom error message in lieu of error message coming from backend.
* Added missing condition for quota change request payload.

1.0.1
-----
* Remove resource id existence check in lieu of backend based check

1.0.0
-----

* GA release of "support" extension for Azure CLI.
* Command `update` under command group `tickets` supports new parameter `status`.
* `Severity` parameter used by command `update` and `create` under command group `tickets` supports an additional value `highestcriticalimpact`.

0.1.1
-----

* Remove the limitation of max compatible cli core version

0.1.0
-----

* Initial release of "support" extension for Azure CLI.
* Adding two major command groups, `az support services` and `az support tickets` to manage support ticket and related resources.
