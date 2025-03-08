# Card Alert Interface for Fraud Analytics

This project integrates CardAlert's workflow with the Fraud Analytics (FA) system. The integration aims to improve detection times and automate manual processes around fraud detection and management.

## Project Overview

The primary goals of this project are:

1. Add counterfeit cards identified by FA to CardAlert's database
2. Efficiently transmit CardAlert Suspect Transactions directly to NYCE
3. Provide faster Suspect Transaction response times from NYCE to CardAlert
4. Enable faster fraud detection for quicker identification of Block & Reissue cards
5. Send Block & Reissue cards directly to FA with rules to action cards at lower scores or block them altogether

## Key Features

- Processing of suspect transaction files from CardAlert
- Handling of Block and Reissue transaction files
- Generation of Fraud cases files for CardAlert
- Integration with hotlist management for quick fraud response
- Automated workflows for improved efficiency

## Technology Stack

- **Backend:** Node.js with Express
- **Frontend:** HTML, JavaScript with Tailwind CSS
- **Database:** Oracle
- **Testing:** Jest for unit and integration tests

## Project Structure

```
card-alert-interface/
│── backend/                   # Backend API (Node.js, Express, Oracle DB)
│── frontend/                  # Frontend (HTML, JavaScript, Tailwind CSS)
│── database/                  # Database scripts (Oracle)
│── docs/                      # Documentation
│── tests/                     # Unit & integration tests
```

## Getting Started

1. Clone the repository
2. Install dependencies with `npm install`
3. Set up environment variables in `.env`
4. Run the database setup scripts in `database/`
5. Start the development server with `npm run dev`

## Documentation

For more detailed information, please refer to the following documentation:
- [API Documentation](./docs/API_Documentation.md)
- [File Formats](./docs/File_Formats.md)
- [Integration Setup](./docs/Integration_Setup.md)

## Contributing

Please read [CONTRIBUTING.md](./CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
