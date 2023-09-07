# File Metadata Microservice

This is a Node.js web application that allows users to upload files for analysis. It provides information about the uploaded file, such as its name, MIME type, and size.

## Getting Started

These instructions will help you set up and run the File Analyzer web application locally.

### Prerequisites

Make sure you have the following prerequisites installed on your system:

- Node.js (version 10 or higher)
- npm (Node Package Manager)

## Usage

1. Access the web application by opening your web browser and navigating to [http://localhost:3000](http://localhost:3000).

2. You will see a simple web page with an upload form.

3. Select a file using the "Choose File" button and click the "Upload" button.

4. The application will analyze the uploaded file and display information about it, including the file's name, MIME type, and size.

## Configuration

This application uses environment variables for configuration. Create a `.env` file in the root directory and specify the following variables if needed:

- `PORT`: The port on which the application will run (default is 3000).

## API Endpoints

The application exposes the following API endpoint:

- `/api/fileanalyse`: This endpoint allows users to upload a file for analysis and returns information about the uploaded file.

   - **Method**: POST
   - **Parameters**: `upfile` (File)
   - **Response**: JSON object containing file information (name, type, size)

## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

