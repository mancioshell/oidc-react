[oidc-react](../README.md) / [AuthContextInterface](../modules/authcontextinterface.md) / AuthProviderSignOutProps

# Interface: AuthProviderSignOutProps

[AuthContextInterface](../modules/authcontextinterface.md).AuthProviderSignOutProps

## Table of contents

### Properties

- [signoutRedirect](authcontextinterface.authprovidersignoutprops.md#signoutredirect)

## Properties

### signoutRedirect

• `Optional` **signoutRedirect**: *unknown*

Trigger a redirect of the current window to the end session endpoint

You can also provide an object. This object will be sent with the
function.

**`example`** 
```javascript
const config = {
 signOutRedirect: {
   state: 'abrakadabra',
 },
};
```

Defined in: [src/AuthContextInterface.ts:30](https://github.com/bjerkio/oidc-react/blob/2957e85/src/AuthContextInterface.ts#L30)