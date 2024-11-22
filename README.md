


# Camel-Detect

Camel-Detect is a project aimed at detecting camels in various environments using advanced image processing techniques. 

Uses the resnet152 to detect if there is camel in the picture. If there is a newly trained instance of the resnet152 gives this camel a score for an auction

## Features

- **High Accuracy**: Utilizes state-of-the-art algorithms to ensure precise detection.
- **Real-Time Processing**: Capable of processing images and videos in real-time.
- **Scalability**: Designed to handle large datasets efficiently.
- **Background remover** Automatically removes background for better classification

## Installation

To install Camel-Detect, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/schamori/Camel-Detect.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Camel-Detect
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

After installation, you can use Camel-Detect by running:
```bash
python detect.py --input /path/to/your/image_or_video
```

Replace `/path/to/your/image_or_video` with the path to the image or video file you want to process.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
