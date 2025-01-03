# Tesla App
 Created by - Heet Goyani
# Dashboard UI Task - Next.js Implementation

This project is a dashboard UI built using **Next.js (v14.x)** with **TypeScript**, based on a Figma design. The dashboard is mobile-responsive and fetches dynamic data from a provided JSON file. It also includes functionality to interact with an external API for downloading a Base64-encoded image.

---

## Features

### 1. Responsive Dashboard UI
- Visually replicates the provided Figma design.
- Fully responsive, with creative improvisation for mobile devices.

### 2. Dynamic Data Fetching
- Fetches data dynamically from a JSON file during runtime.
- Ensures flexibility and scalability by avoiding hardcoded JSON data.

### 3. Download Functionality
- Retrieves the `api_secret` from the JSON file and sends it as a POST request to the given API endpoint.
- Converts the API's Base64 image response into a downloadable file for the user.

### 4. Deployment
- Deployed using **Vercel** for easy access.
- Codebase hosted privately on **GitHub**.

---

## Getting Started

### Prerequisites
- **Node.js** installed on your local system.
- A **GitHub** account for accessing the private repository.

### To Run Locally:
## Installation

To install the Tesla app, follow these steps:

1. Clone the repository:
```
git clone https://github.com/your-username/tesla-app.git
```
2. Navigate to the project directory:
```
cd tesla-app
```
3. Install the dependencies:
```
npm install
```

## Usage

To start the development server, run:
```
npm run dev
```
This will start the app in development mode and open it in your default browser at `http://localhost:3000`.

## API

The Tesla app uses the following APIs:

- **Toaster**: A custom UI component for displaying notifications.

## Contributing

If you would like to contribute to the Tesla app, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Submit a pull request to the main repository.
<!-- ## License

This project is licensed under the [MIT License](LICENSE).

## Testing

To run the tests, use the following command:
```
npm test
```
This will run the test suite and report the results. -->
