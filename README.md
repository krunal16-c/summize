![summizelogo](https://github.com/krunal16-c/summize/assets/64957243/86a6e6ce-50ca-4de4-b4eb-1f5d376e99bc)
# Summize

Summize is an AI-powered web application built with VITE+React that allows users to quickly summarize long articles. It leverages the power of Rapid API to provide efficient and accurate article summarization.

![Summize Demo](demo.gif)

## Features

- **Article Summarization:** Summize uses advanced natural language processing techniques to analyze and summarize lengthy articles, making it easier for users to grasp the main points and key information quickly.

- **User-Friendly Interface:** The application offers a clean and intuitive user interface, ensuring a smooth user experience. It allows users to input articles or URLs directly and provides summarized results in a readable format.

- **Customizable Summary Length:** Summize enables users to specify the desired summary length according to their preferences. Whether users want a concise summary or a more detailed overview, the application adapts to their needs.

- **Instantaneous Results:** With the help of Rapid API, Summize provides near-instantaneous summarization results, eliminating the need for users to wait for extended periods to obtain the summaries.

## How to Use

1. Visit the Summize web application at [this link](https://phenomenal-melba-240dca.netlify.app/).

2. In the input area, either paste the full article or provide a valid URL to the article you wish to summarize.

3. Click the "enter" button to initiate the summarization process.

4. Summize will analyze the input and generate a summary based on the provided length. The summary will be displayed on the screen for easy reading.

5. Users can copy the summarized text or share it directly via social media platforms using the provided sharing buttons.

## Installation and Setup

To run Summize locally, follow these steps:

1. Clone this repository to your local machine.

```bash
git clone https://github.com/your-username/summize.git
```

2. Navigate to the project directory.

```bash
cd summize
```

3. Install the dependencies using npm or yarn.

```bash
npm install
```
or
```bash
yarn install
```

4. Obtain a Rapid API key by signing up at [https://rapidapi.com](https://rapidapi.com).

5. Create a `.env` file in the project root directory and add your Rapid API key.

```bash
REACT_APP_RAPIDAPI_KEY=YOUR_RAPID_API_KEY
```

6. Start the development server.

```bash
npm run dev
```
or
```bash
yarn dev
```

7. Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to access Summize.

## Dependencies

The following dependencies are used in this project:

- Vite - Build tool and development server for modern web applications.
- React - JavaScript library for building user interfaces.
- Axios - HTTP client for making requests to the Rapid API.

## Contributing

Contributions are welcome! If you have any suggestions or improvements for this project, please feel free to submit a pull request.

1. Fork the repository.

2. Create a new branch for your feature or bug fix.

```bash
git checkout -b my-feature
```

3. Make your modifications and commit your changes.

```bash
git commit -m

 "Added a new feature"
```

4. Push your branch to GitHub.

```bash
git push origin my-feature
```

5. Open a pull request and describe your changes in detail.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
