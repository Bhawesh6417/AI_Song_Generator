# Hindi Song Generator

This project generates Hindi song lyrics using Google's Gemini AI and then converts them into an audio format using Udio.

## Features
- Generates meaningful Hindi song lyrics based on user input.
- Uses Google's Gemini AI (`gemini-pro`) for text generation.
- Converts the generated lyrics into an audio file using Udio.

## Prerequisites
Make sure you have the following installed:
- Python 3.8+
- Required Python packages:
  - `google-generativeai`
  - `udio_wrapper`

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/hindi-song-generator.git
   cd hindi-song-generator
   ```

2. Install dependencies:
   ```sh
   pip install google-generativeai udio_wrapper
   ```

3. Set up API keys securely:
   - Open a terminal and set the API keys as environment variables:
     ```sh
     export GEMINI_API_KEY="your-gemini-api-key"
     export UDIO_AUTH_TOKEN="your-udio-auth-token"
     ```
   - On Windows (PowerShell):
     ```powershell
     $env:GEMINI_API_KEY="your-gemini-api-key"
     $env:UDIO_AUTH_TOKEN="your-udio-auth-token"
     ```

## Usage
Run the script:
```sh
python generate_song.py
```

The script will prompt you to enter the type of song you want (e.g., pop, rap, sad, happy). It will then:
1. Generate Hindi lyrics.
2. Convert the lyrics into an audio format.
3. Provide a URL to access the generated song.

## Example Output
```
Enter the type of song you want (e.g., pop, rap, sad, happy): sad

Generated Lyrics:

**Title: टूटे सपने (Toote Sapne - Broken Dreams)**

**(Verse 1)**
धुंधली यादें, धुंधला सा मंज़र,
बीते कल का, एक अधूरा सफ़र।
आँखों में नमी, दिल में है दर्द गहरा,
खो गया वो, जो था मेरा।
हर राह सूनी, हर रात काली,
ज़िंदगी जैसे, एक खाली डाली।

**(Chorus)**
टूटे सपने, बिखरे हैं ऐसे,
जैसे रेत हाथों से फिसले।
आंसू बनके, बहती है कहानी,
प्यार की ये, अधूरी निशानी।
टूटे सपने, टूटे सपने,
खो गए, सब अपने।

**(Verse 2)**
वो हँसी तेरी, वो बातें प्यारी,
अब लगती हैं, जैसे हों उधारी।
हर लम्हा जैसे, एक बोझ बन गया,
ज़िंदगी का, रंग ही उड़ गया।
तन्हाई में, ढूँढूं सहारा,
मिलता नहीं है, कोई किनारा।

**(Chorus)**
टूटे सपने, बिखरे हैं ऐसे,
जैसे रेत हाथों से फिसले।
आंसू बनके, बहती है कहानी,
प्यार की ये, अधूरी निशानी।
टूटे सपने, टूटे सपने,
खो गए, सब अपने।

**(Bridge)**
कैसे भुलाऊं, वो बीते पल,
कैसे सहूं, ये दर्द हर पल।
कोई तो बताए, क्या है वजह,
क्यों मिली है, ये ऐसी सज़ा।
क्या कोई उम्मीद, बाकी है अब भी,
या बस गम का, सागर ही है सब ही?

**(Chorus)**
टूटे सपने, बिखरे हैं ऐसे,
जैसे रेत हाथों से फिसले।
आंसू बनके, बहती है कहानी,
प्यार की ये, अधूरी निशानी।
टूटे सपने, टूटे सपने,
खो गए, सब अपने।

**(Outro)**
टूटे सपने... ओ... टूटे सपने...
खो गए... सब अपने...

```

## Notes
- Do **not** expose your API keys in public repositories.
- The song generation process may take a few minutes depending on server load.

## License
This project is licensed under the MIT License.
