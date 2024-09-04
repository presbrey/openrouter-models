# AI Models Table

This project is a web application that displays a table of AI models using data from the OpenRouter API. It's built with HTML, React, and Tailwind CSS, providing an interactive and responsive user interface.

**[View the live AI Models Table](https://presbrey.github.io/openrouter-models)** 👈 Check it out!

## Features

- Fetches AI model data from the OpenRouter API
- Displays models in a sortable and filterable table
- Allows filtering by model name, context length, and creation date
- Supports sorting by various fields (name, pricing, context length, modality, creation date)
- Responsive design using Tailwind CSS

## Technologies Used

- HTML5
- React 17
- Tailwind CSS
- Babel (for JSX transformation)

## Getting Started

1. Clone this repository to your local machine.
2. Open the `index.html` file in a modern web browser.

No build process is required as the project uses CDN-hosted libraries and Babel standalone for JSX transformation.

## Usage

- Use the input fields and dropdowns at the top of the page to filter and sort the AI models.
- Click on column headers to sort the table by that column.
- Click on a model name to visit its OpenRouter page for more details.

## API

This project uses the OpenRouter API to fetch AI model data. The API endpoint used is:

```
https://openrouter.ai/api/v1/models
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).
