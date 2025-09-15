# DeepClean - AI-Powered Data Preparation Assistant

DeepClean is a powerful AI-driven application that helps users prepare, clean, and enhance various types of data including CSV files, PDFs, and images. The application leverages advanced AI capabilities to automate data quality checks, implement data cleaning operations, and provide intelligent data processing solutions.

## Features

### CSV Data Processing
- Automated data quality checks
- Intelligent data cleaning and preparation
- Interactive data preview and analysis
- Summary statistics generation
- AI-powered data transformation suggestions

### PDF Processing
- Automatic page orientation correction
- OCR (Optical Character Recognition) capabilities
- Noise and artifact removal
- Text formatting and alignment fixes
- Blank page detection and removal

### Image Enhancement
- Interactive image enhancement controls
- Brightness, contrast, sharpness, and saturation adjustment
- Quality issue detection
- Format optimization
- Batch processing capabilities

## Installation

1. Clone the repository:
```bash
git clone https://github.com/doodle-pro/DeepClean.git
cd DeepClean
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

3. Set up environment variables:
- Create a `.env` file in the root directory
- Add your Google API key:
```
GOOGLE_API_KEY=your_api_key_here
```

## Usage

1. Start the application:
```bash
streamlit run streamlit_app.py
```

2. Access the web interface through your browser at `http://localhost:8501`

3. Use the sidebar to upload your files:
   - CSV files for data preparation
   - PDF files for document processing
   - Images for enhancement

4. Navigate between tabs:
   - **Data Quality Explorer**: View and analyze data quality issues
   - **AI Data Prep**: Select issues to resolve and apply AI-powered solutions

## Project Structure

```
DeepClean/
├── backend/
│   ├── data_preparation_gemini.py
│   ├── data_quality_checks.py
│   ├── image_processing.py
│   └── pdf_processing.py
├── streamlit_app.py
├── requirements.txt
└── README.md
```

## Dependencies

- streamlit
- pandas
- numpy
- scikit-learn
- scipy
- statsmodels
- google-generativeai
- datasketch
- python-dotenv
- PyMuPDF
- pytesseract
- Pillow
- opencv-python
- pywavelets

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Google Generative AI for powering the intelligent data preparation features
- Streamlit for the interactive web interface
- The open-source community for various data processing libraries