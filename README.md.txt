# ?? Random Quote Generator

## ?? Author
**[Mikhail Poliakov]**  
?? mpolakov976@gmail.com| ?? [https://github.com/mpolakov976-lang]

## ?? Description
**Random Quote Generator** is a lightweight desktop GUI application built with Python. It generates random quotes from a built-in collection, tracks generation history, allows filtering by author or topic, and lets users expand the database with custom quotes. The history is automatically saved to a local JSON file and fully restored on the next application launch.

## ? Key Features
- ?? **Random Generation**: Fetch a random quote with a single click.
- ?? **History Tracking**: Chronological table of all viewed and added quotes.
- ?? **Real-time Filtering**: Filter the history table by author or topic.
- ? **Custom Quotes**: Add new quotes with strict input validation.
- ?? **Persistent Storage**: Auto-saves and loads history from `history.json`.
- ?? **Clean UI**: Modern `tkinter` + `ttk` interface with adaptive theming.

## ?? Tech Stack
- `Python 3.8+`
- `tkinter` / `ttk` (Standard GUI library)
- `random`, `json`, `os` (Built-in modules)
- ?? *Zero external dependencies required*

## ?? Installation & Usage
1. Ensure **Python 3.8 or newer** is installed.
2. Clone or download the project:
   ```bash
   git clone https://github.com/YOUR_USERNAME/random-quote-generator.git
   cd random-quote-generator