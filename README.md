# File Metadata Microservice

A REST API project for uploading files and retrieving their metadata, built with Node.js, Express, and Multer.

## Features

- Upload files via a form
- Receive file metadata: name, type, and size in bytes (JSON response)

## API Endpoints

### Upload a File

**POST** `/api/fileanalyse`  
Form field:  
- `upfile` (file input, required)

**Response:**
```json
{
  "name": "filename.ext",
  "type": "file/type",
  "size": 12345
}
```

## Getting Started

Clone the repo:
```bash
git clone https://github.com/sabbas-ctrl/File-Metadata-Microservice
cd File-Metadata-Microservice
```

Install dependencies:
```bash
npm install
```

Start the server:
```bash
npm run dev
```

The app runs on [http://localhost:3000](http://localhost:3000).

## Project Structure

- `index.js` – Main server file
- `public/` – Static assets (CSS)
- `views/` – HTML frontend

---