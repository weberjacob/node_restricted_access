# Node Restricted Access
<img src="https://badgen.net/badge/version/8.x-1.0.0/cyan?icon=github" alt="Version: 8.x-1.0"/>  **OR** 
<img src="https://badgen.net/badge/version/2.0/cyan?icon=github" alt="Version: 2.0"/>

Custom module that adds a permission to allow specific roles to view restricted content.

## Usage
Download and enable the module for either [D8](https://github.com/weberjacob/node_restricted_access/tree/8.x-1) or [D9](https://github.com/weberjacob/node_restricted_access/tree/2.0) from the respective branch. During install the permissions should be rebuilt automatically.

* Add a `field_restricted_access` boolean field to any node to allow restricting the access.
* Update permissions on roles to allow viewing of restricted content.