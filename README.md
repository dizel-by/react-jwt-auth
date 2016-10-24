# React JWT Auth

### Token based authentication for react.

[![Build Status](https://travis-ci.org/fullstackforger/react-jwt-auth.svg?branch=master)](https://travis-ci.org/fullstackforger/react-jwt-auth)
[![Coverage Status](https://coveralls.io/repos/github/fullstackforger/react-jwt-auth/badge.svg?branch=master)](https://coveralls.io/github/fullstackforger/react-jwt-auth?branch=master)
[![npm](https://img.shields.io/npm/v/react-jwt-auth.svg)](https://www.npmjs.com/package/react-jwt-auth)
[![npm](https://img.shields.io/npm/l/react-jwt-auth.svg)]()

## Inspiration

Satellizer, for its simplicity, clear code and maturity was initial source of inspiration. 
As there is no need to reinvent the wheel, some of Satellizer code has been reused where possible and adopted to React.

## Setup

Before you start using component you should configure it, eg:
```
ReactDOM.render(
	<Auth baseUrl="http://localhost:8080/api/">
		<YourAwesomeComponents />
	</Auth>,
	document.getElementById('app')
);
```

More in docs, [configuration](./docs/configuration.md) section. 

## Social buttons

Here is simplest example of social buttons in use inside of your component `reder()` method.

```
render () {
	return (
		<div className="form-group">
			<Facebook clientId="310178806023492" />
			<Google clientId="389760969675-u3h2dgm1v3lqd22u8aloimkgd10i0rvf.apps.googleusercontent.com"	/>
		</div>
	)
}
```
