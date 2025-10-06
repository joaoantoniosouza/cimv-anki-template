# CIMV Anki Template

A **clean, minimalist, and highly readable Anki template** designed for Mairo Vergara's English course. Ideal for learning vocabulary, grammar, pronunciation, and reviewing efficiently.

![Preview GIF](./assets/preview.gif)
_Quick preview of cards in action_

## Installation & Usage

There are **two ways** to install the template in Anki:

### Option 1 – Import the example deck

1. Download the provided `.apkg` file from this repository.
2. Open **Anki** and go to **File → Import**.
3. Select the `.apkg` file and import it.
4. The example deck will appear with the theme already applied — ready to use or customize.

### Option 2 – Create a new Note Type manually

1. In Anki, open **Tools → Manage Note Types → Add → Add: Basic** or similar.
2. Open the new note type and go to the **Fields...** section.
3. Add the following fields if they don’t exist:
   - `Front` - the front side of the card
   - `Back` - the back side of the card
   - `Audio` - optional audio pronunciation
   - `IPA` - optional phonetic transcription (International Phonetic Alphabet)
4. Then go to the **Cards...** section.
5. Replace the content of each tab with the corresponding file from this repository:
   - **Front Template:** use the contents of `front.html`
   - **Back Template:** use the contents of `back.html`
   - **Styling:** use the contents of `style.css`
6. Save your changes.

After completing either of the steps above, the new Note Type will be available when you create cards in any of your decks; simply select it to use the CIMV template.

## Credits

Inspired by Mairo Vergara's English course.

## License

This project is **open source** under the **MIT License**, free for personal or educational use.
