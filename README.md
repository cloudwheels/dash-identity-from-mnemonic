# Get Registered Dash Platform Identities for an Account Mnenomic

This functionality is not currently availble in DashJS, so when a wallet is reloaded from mnemonic the registered identities (and therefore names) cannot be retrieved.
There is some initial code in early versions of platform console which is not complete: https://gist.github.com/dashameter/69b823de831395ff4e1c95a2951ed6e3. 

The demo is available at: http://dashid.cloudwheels.net/

(Enter mnemonic or click submit to use the test placeholder value to find Platform identities registered by that account.)

Please note that due to limitations with the underlying wallet-lib function only a single identity will be returned rather than all registered identities.
