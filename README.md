# XQ Learning Experience Evaluation System

An AI-powered tool that evaluates lesson plans according to the XQ Learning Experience design principles. This system uses multiple specialized agents to analyze different aspects of your lesson plan and provide comprehensive, actionable feedback.

## Features

- Comprehensive lesson plan evaluation
- Analysis based on XQ Learning Experience design principles
- Specialized feedback for multiple dimensions of learning
- Actionable recommendations for improvement
- Easy-to-use web interface
- Downloadable evaluation reports

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/xq-lesson-evaluator.git
cd xq-lesson-evaluator
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the root directory and add your OpenAI API key:
```
OPENAI_API_KEY=your-api-key-here
```

## Usage

1. Start the application:
```bash
streamlit run app.py
```

2. Open your web browser and navigate to the provided URL (typically http://localhost:8501)

3. Enter your lesson plan in the text area

4. Click "Evaluate" to receive comprehensive feedback

## Evaluation Areas

The system analyzes lesson plans across seven key dimensions:

1. Multi-dimensional Learning
2. Project-based Learning
3. High Interest & Engagement
4. Authenticity
5. Academic Rigor
6. Time & Space Usage
7. Overall Integration

## Output Format

Each evaluation includes:
- Overall assessment
- Specific strengths
- Areas for improvement
- Actionable recommendations
- Implementation roadmap

## Requirements

- Python 3.10+
- OpenAI API key
- Internet connection
- Modern web browser

## Technology Stack

- Python
- Streamlit
- AutoGen
- OpenAI API

## Contributing

Contributions are welcome! Please read the contributing guidelines before submitting pull requests.

## License

MIT License - see LICENSE.md for details

## Support

For support, please open an issue in the GitHub repository or contact [your-email@example.com]

## Acknowledgments

- Based on the XQ Learning Experience design principles
- Uses OpenAI's GPT-4 for analysis
- Built with AutoGen framework

## FAQ

**Q: How long does evaluation take?**
A: Typically 2-3 minutes for a complete analysis.

**Q: What format should my lesson plan be in?**
A: Plain text format including objectives, activities, assessments, and timeline.

**Q: Can I save the evaluation results?**
A: Yes, results can be downloaded in multiple formats.

**Q: Is my lesson plan data secure?**
A: All data is processed securely and not stored after evaluation.

## Getting Started Guide

1. **Prepare Your Lesson Plan**
   - Include clear objectives
   - Detail activities and timeline
   - Specify assessment methods
   - List required materials

2. **Run the Evaluation**
   - Paste your lesson plan
   - Click "Evaluate"
   - Wait for complete analysis

3. **Review Results**
   - Examine each section
   - Read recommendations
   - Check implementation plan

4. **Implement Changes**
   - Follow the provided roadmap
   - Make prioritized improvements
   - Re-evaluate as needed

## Tips for Best Results

1. Provide detailed lesson plans
2. Include all key components
3. Be specific about activities and assessments
4. Include timeline information
5. Specify grade level and subject area

## Contact

For questions or support:
- GitHub Issues: [Repository Issues]
- Email: [your-email@example.com]
- Twitter: [@yourusername]
