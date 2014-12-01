alicorns-ui
==========

Alicorns UI = Semantic UI + Stylus + React.js + Bacon.js + Browserify + Gulp

This is in early stages of development and is really little more then a starting point for working with React + Semantic UI.

```
const React = require('React'),
	Aui = require('aui').Aui;

export const Login = React.createClass({
	render() {
		return (
			<Aui>
				<form ui form>
					<div ui large fluid icon input>
						<label> Username: </label>
						<input type="text" name="username" placeholder="username..." />
						<i ui lock icon />
					</div>
					<div ui large fluid icon input>
						<label> Password: </label>
						<input type="password"	name="password" placeholder="password..." />
						<i ui privacy icon />
					</div>
					<div ui divider />
					<div ui large white fluid button> Login </div>
				</form>
			</Aui>
		);
	}
});
```

Public Domain (Unliscense)