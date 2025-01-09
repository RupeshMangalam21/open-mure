# OpenMure: Open Music Removal Software

OpenMure is a free and open-source software designed to remove background music from recordings, specifically to counteract copyright-triggered censorship. This tool allows users to subtract background music from field recordings, ensuring critical content is preserved and accessible.

## Key Features
- Remove background music effectively using user-provided samples.
- Handle noisy and distorted field recordings.
- Simple and user-friendly web application interface.

## How It Works
1. Upload the field recording and the background music sample.
2. OpenMure processes the files to subtract the music.
3. Download the cleaned recording, ready for use.

## Technology Stack
- **Backend**: Python (FastAPI/Django), Machine Learning for audio processing.
- **Frontend**: React, Tailwind CSS.
- **Machine Learning Models**: Spleeter, librosa, TensorFlow/PyTorch.

## License
OpenMure is licensed under the Apache License 2.0. See [LICENSE](LICENSE) for more details.

## Contributing
We welcome contributions from the community. See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## Getting Started
1. Clone the repository:

   ```bash
   git clone https://github.com/RupeshMangalam21/open-mure.git


2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   npm install


3. Run the application:
  
   ```bash
    docker-compose up


## Roadmap
Implement a robust audio separation model.
Optimize for noisy and distorted recordings.
Deploy scalable web services for public use.

## Community
Join the discussion on [GitHub Discussions](https://github.com/RupeshMangalam21/open-mure/discussions).

## Support
If you encounter issues, please open an issue on GitHub.

## Acknowledgments
Inspired by the need to ensure freedom of information and protect public recordings.
