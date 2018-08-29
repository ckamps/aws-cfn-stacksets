# Example CloudFormation Template Using Custom Stack Set Resource

This example demonstrates use of the custom Stack Set resource to manage multiple stack set resources.

The `Regions` and `Accounts` settings under `StackInstances` can be changed after initial provisioning and those changes can be rolled out by updating the associated stack.

The `Regions` and `Accounts` settings do not have to be consistent across stack set resources.

In this example, the `Version` tag is used to represent a change to this template in those cases where the CloudFormation templates referenced in each stack set resource has changed.
