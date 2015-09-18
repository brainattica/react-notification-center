# React Notification Center

Notification center worked on top of react and inspired on Flux to dispatch events

This is prepared to be used with Webpack and written with ES6.

You should have to use a transpiler like Babel.

You can use it like this

	var NotificationCenter = require('react-notification-center');

	class MyComponent extends React.Component {

		render() {
			<div>
				<NotificationCenter />
			</div>
		}

	}