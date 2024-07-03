# AI职升姬v3
 AI职升姬v3
# AI Resume Generator

This project is an AI-powered resume generator that can extract information from PDF and DOCX files, and optimize resume content using AI.

## Setup

1. Clone the repository
2. Install Docker and Docker Compose
3. Set up environment variables:
   - SPARK_APPID
   - SPARK_API_SECRET
   - SPARK_API_KEY
4. Run `docker-compose up --build`
5. Access the application at http://localhost:7860

## Usage

1. Upload a PDF or DOCX resume file
2. Click "Extract Information" to process the file
3. Use the "Optimize Content" feature to improve specific sections of your resume

## Testing

Run tests using pytest:

```
pytest tests/
```

## Contributing

Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.