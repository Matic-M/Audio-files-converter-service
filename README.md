# Audio File Upload and Conversion Service

## Overview

This web service allows users to upload audio files to the server. It supports only files in WAV and FLAC formats. If a FLAC file is uploaded, it is converted to WAV format. All files are then further processed to be in 16-bit PCM, 16 KSPS, and MONO format.

The service performs the following tasks:
- Verifies the file extension to ensure it is either WAV or FLAC.
- Converts FLAC files to WAV format.
- Transforms the audio files to 16-bit PCM, 16 KSPS, MONO format.
- Ensures that the sequence number provided by the user is unique.
- Saves the file on the server with a name that includes the sequence number and the upload date and time.
- Responds to the user with details about the file format and the success of the conversion.

## Technologies Used

- **Flask**: Web framework for building the REST API.
- **Bootstrap**: Frontend framework for styling and responsive design.
- **Python Libraries**: For file conversion and processing.
- **REST**: To handle HTTP requests and responses.
- **HTML, CSS, JavaScript**: For frontend development.

## Setup Instructions

* Clone the Repository

```bash
git clone https://github.com/your-repo/audio-file-upload-service.git
cd audio-file-upload-service
```

* Made in collaboration with [Vukp17](https://github.com/Vukp17) and [lukablagic](https://github.com/lukablagic)
