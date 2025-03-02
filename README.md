# Message Task Parser

Detail usage description is on my blog: https://blog.petrkucerak.cz/post/jak-poslat-velik%C3%A9-mno%C5%BEstv%C3%AD-sms-z-iphone

*README IS GENERATED BY CHAT GPT*

This project provides a simple web-based tool to generate personalized messages for a list of contacts. The generated messages are saved in a CSV file for easy distribution.

## Features
- Input a message template with a `<name>` wildcard.
- Provide a list of contacts in the format: `phone_number; name`.
- Automatically replace `<name>` with the corresponding contact name.
- Download the generated messages as a CSV file.

## Usage
1. Open `index.html` in a web browser.
2. Enter the message template, using `<name>` as a placeholder.
3. Paste the contact list in the provided format.
4. Click the **Generate File** button.
5. A file named `message_task.csv` will be downloaded, containing personalized messages.

## Example
**Input Message:**
```
Ahoj <name>, 👋
Rád bych Tě pozval do naší komunity na WhatsAppu...
```

**Input Contacts:**
```
+420123456789; Petře
+420987654321; Ludmilo
```

**Generated CSV:**
```
+420123456789;Ahoj Petře, 👋 Rád bych Tě pozval do naší komunity na WhatsAppu...
+420987654321;Ahoj Ludmilo, 👋 Rád bych Tě pozval do naší komunity na WhatsAppu...
```

## License
This project is open-source and available under the MIT License.

