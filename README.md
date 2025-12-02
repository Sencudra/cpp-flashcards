# cpp-flashcards

A simple C++ flashcard deck for Anki or similar tools.

## Project Structure

- `deck.json` — The flashcard deck in JSON format.
- `media/` — Media files (images, audio, etc.) referenced by the deck.

## Usage

1. Edit `deck.json` to add or update flashcards.
2. Place any required media files in the `media/` directory.
3. Use the deck with your preferred flashcard application.

### Import/Export

This deck is designed to be used with the [CrowdAnki](https://ankiweb.net/shared/info/1788670778) Anki add-on for easy import and export.

## Development

- All JSON files are validated automatically via GitHub Actions on push and pull request.
- To manually check JSON validity:
  ```sh
  jq empty deck.json
  ```

## License

MIT
