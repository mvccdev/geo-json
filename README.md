![](https://img.shields.io/static/v1?label=category&message=json&color=red)

# College Data

A collection of geographical data in JSON format for GET requests.

[Documentation](doc/toc.md)

## Example

	fetch("https://raw.githubusercontent.com/mvccdev/geo-data/main/api/{NAME}.json")
		.then((resp) => {
			resp.json().then((data) => {
				//
				// Iterate through the array here.
				//
			}
		});
	})

## Skill Prerequisites

A basic understanding of the following skills are necessary to use this project.

* [ES6](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [JSON](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON)

# Tool Dependencies

Install the following tools to use this project in your local development environment.

* [Node.js](https://nodejs.org/)
* [Git](https://git-scm.com/)
* [GitHub Desktop](https://desktop.github.com/)

## Installing

Follow these steps to install this project.

	git clone https://github.com/github-template/github-template.git
	cd github-template
	npm install
	npm run watch

## Building

Use the following CL commands to test or compile this project:

| Name          | Description                                          |
| ------------- | ---------------------------------------------------- |
| npm run watch | Test the project in a local development server       |
| npm run build | Build the project                                    |

## Contributing

Pull requests are encouraged and welcome.

## Thanks

Most information has been gathered from the following:

* [Samayo](https://github.com/samayo/country-json/)
* [World Population Review](https://worldpopulationreview.com/)

## License

MIT
