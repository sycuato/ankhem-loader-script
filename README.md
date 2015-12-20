# ankhem-loader-script
Ankhem Component: Loader for script

ES6, React

## Usage

Your webpack.config.js maybe like this:

```javascript
module.exports = {
	module: {
		loaders: [
			{
				test: /\.jsx?$/,
				// exclude: /(node_modules|bower_components)/,
				loader: 'babel',
				query:
				{
					presets:['react', "es2015"]
				}
			}
		]
	}
};
```
