Npm Publishing Demo
===================

First, make sure your npm using registry `https://registry.npmjs.org/`.

```
npm config get registry
```

If not, config it:

```
npm config set registry https://registry.npmjs.org/
```

Login
-----

```
npm login
```

Input correct username, password, email.

If no account or forgot, go to <http://npmjs.com> to create or reset it.

Publish
-------

```
cd to-publish
npm publish
```

If it fails, check for the following reason:

- Your package name is used by someone else, search it to confirm, and use another name (defined in `package.json`)
- Your package name is treated as spam, like `npm-publish-demo-37652342`, change it to normal name

After succeed, you should be able to find it in <http://npmjs.com>