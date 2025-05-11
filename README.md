# MedAIx - AI Medical Paper Collection Platform

MedAIx is a platform for collecting and managing AI-related medical research papers. It provides a modern web interface for browsing, searching, and filtering papers from various sources including PubMed.

## Features

- Automated paper collection from PubMed
- Modern web interface with card-based layout
- Advanced search and filtering capabilities
- Category-based organization
- Date-based sorting
- Responsive design

## Project Structure

```
medaix/
├── app/                # Backend application
│   ├── api/           # API endpoints
│   └── utils/         # Utility functions
├── frontend/          # Next.js frontend application
│   ├── components/    # React components
│   ├── pages/         # Next.js pages
│   └── styles/        # CSS styles
└── tests/             # Test files
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/loveyz1806/medaix.git
cd medaix
```

2. Install backend dependencies:
```bash
pip install -r requirements.txt
```

3. Install frontend dependencies:
```bash
cd frontend
npm install
```

## Running the Application

1. Start the backend server:
```bash
python -m app.main
```

2. Start the frontend development server:
```bash
cd frontend
npm run dev
```

The application will be available at http://localhost:3000

## Configuration

The application requires the following environment variables:

- `PUBMED_API_KEY`: Your PubMed API key
- `DATABASE_URL`: PostgreSQL database connection string
- `REDIS_URL`: Redis connection string (optional)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
