# AI Course Generator: Transforming Videos into Structured Learning

![AI Course Generator](https://img.shields.io/badge/AI%20Course%20Generator-v1.0-brightgreen)  
[![Releases](https://img.shields.io/badge/Releases-Check%20Here-blue)](https://github.com/FaizaBatool/AI-course-generator/releases)

---

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Project Overview

The **AI Course Generator** is an innovative project developed during the SensAI'25 Hackathon. This tool automatically converts long educational videos into structured online courses. It provides users with transcripts, modules, lessons, and quizzes, enhancing the learning experience.

By leveraging advanced technologies like OpenAI Whisper for audio transcription and GPT-4 Vision for visual analysis, this project creates rich, multimodal course content. It aims to make educational resources more accessible and organized, allowing learners to grasp concepts more effectively.

---

## Features

- **Automatic Video Transcription**: Utilizes OpenAI Whisper to transcribe spoken content from videos into text.
- **Structured Course Creation**: Generates modules and lessons based on the video content, making learning easier.
- **Interactive Quizzes**: Creates quizzes to test understanding and reinforce learning.
- **Multimodal Content**: Combines audio and visual data to create engaging course material.
- **User-Friendly Interface**: Designed with simplicity in mind, ensuring easy navigation for users.
- **Scalable Architecture**: Built to handle multiple videos and large datasets efficiently.

---

## Technologies Used

- **Flask**: A lightweight web framework for building the application.
- **OpenAI Whisper**: For accurate audio transcription.
- **GPT-4 Vision**: For visual analysis of video content.
- **NLP**: Natural Language Processing techniques for understanding and organizing course material.
- **HTML/CSS/JavaScript**: For frontend development, ensuring a responsive and interactive user interface.
- **Python**: The primary programming language used for backend development.
- **Scene Segmentation**: For breaking down video content into meaningful segments.
- **Multimodal AI**: To integrate different types of data (audio, video, text) seamlessly.

---

## Installation

To set up the **AI Course Generator** on your local machine, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/FaizaBatool/AI-course-generator.git
   cd AI-course-generator
   ```

2. **Install Dependencies**:
   Make sure you have Python installed. Then, run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the root directory and add your API keys for OpenAI services.

4. **Run the Application**:
   Start the Flask server:
   ```bash
   python app.py
   ```

5. **Access the Application**:
   Open your web browser and navigate to `http://localhost:5000`.

For downloadable files and specific versions, check the [Releases](https://github.com/FaizaBatool/AI-course-generator/releases) section.

---

## Usage

Using the **AI Course Generator** is straightforward:

1. **Upload a Video**: Use the provided interface to upload your educational video.
2. **Select Settings**: Choose options for course structure, such as the number of modules and quiz frequency.
3. **Generate Course**: Click on the generate button. The tool will process the video and create a structured course.
4. **Review Content**: Once the course is generated, review the transcripts, modules, and quizzes.
5. **Export or Share**: You can export the course for your use or share it with others.

For any issues or bugs, please refer to the [Releases](https://github.com/FaizaBatool/AI-course-generator/releases) section.

---

## Contributing

Contributions are welcome! If you would like to contribute to the **AI Course Generator**, please follow these steps:

1. **Fork the Repository**: Click the fork button on the top right of the repository page.
2. **Create a Branch**: Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. **Make Changes**: Implement your changes in the code.
4. **Commit Changes**: Commit your changes with a clear message:
   ```bash
   git commit -m "Add your message here"
   ```
5. **Push to Your Branch**:
   ```bash
   git push origin feature/YourFeatureName
   ```
6. **Create a Pull Request**: Go to the original repository and create a pull request.

Thank you for considering contributing to this project!

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

For any inquiries, suggestions, or issues, please reach out:

- **Faiza Batool**  
  GitHub: [FaizaBatool](https://github.com/FaizaBatool)  
  Email: faiza@example.com

For updates and new features, keep an eye on the [Releases](https://github.com/FaizaBatool/AI-course-generator/releases) section.

--- 

![Educational Technology](https://images.unsplash.com/photo-1593642632740-9c6f1a5d3c9b)  
*Image Source: Unsplash*