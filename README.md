# Telegram JSON Parser

Welcome to the **Telegram JSON Parser**! This tool allows you to easily search, filter, and view messages from your Telegram JSON export files.

## Features

- **Search Messages**: Search for specific words or phrases in your Telegram messages. Supports search operators like **OR**, **AND**, and **NOT**.
- **Filter by Date**: Filter messages within a specific date range using the start and end date filters.
- **Case Sensitivity**: Toggle case sensitivity for more precise searches.
- **View and Analyze Messages**: Displays messages in an easy-to-read format with details such as message type, ID, date, and actor.

## How to Use

1. **Open the Tool**: Visit the following link to open the Telegram JSON Parser in your browser: [Telegram JSON Parser](https://denpydev.github.io/TelegramTakeoutManager/).
   
2. **Upload Your JSON File**: Click the input box to select your Telegram JSON file (`.json`). This file should contain the exported messages from your Telegram account.

3. **Filter and Search Messages**:
   - **Search Box**: Use the search box to enter keywords or phrases you want to search for. You can combine multiple operators for advanced searches. Here are some examples:
     - **Single Keyword Search**: Enter `birthday` to find all messages containing the word "birthday".
     - **Phrase Search**: Enter `happy birthday` to search for the exact phrase without any logical operators.
     - **Combining `OR` and `AND` Operators**: Use `OR` and `AND` together to refine your search. For example, `birthday AND party OR anniversary` will find messages that contain both "birthday" and "party", or messages that contain "anniversary".
     - **Using `NOT` with Other Operators**: Exclude specific terms while combining with other operators. For example, `birthday AND party NOT surprise` will find messages that contain both "birthday" and "party" but do not include the word "surprise".
     - **Complex Searches**: Combine multiple operators for advanced searches. For example, `birthday AND (party OR dinner) NOT surprise` will find messages containing "birthday" and either "party" or "dinner", but exclude any that contain "surprise".
   - **Case Sensitivity**: Check the **"Case Sensitive"** checkbox if you want your search to differentiate between uppercase and lowercase letters.
   - **Date Range Filters**: Use the **start** and **end date** fields to filter messages by a specific date range. This is useful for finding messages from a certain period.

4. **View Results**: The filtered messages will be displayed below with their respective details. You can scroll through the messages and view them in a formatted layout.


- Large JSON files might take a bit longer to load, so please be patient.

## License

This project is open source and available under the [MIT License](LICENSE).
