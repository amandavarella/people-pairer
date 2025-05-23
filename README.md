# People Pairing Tool

A simple web-based utility to quickly generate pairs (or pairs and a trio) from a list of names. Ideal for organizing groups, teams, or random pairings for activities.

**Live Demo:** [https://amandavarella.github.io/people-pairer/](https://amandavarella.github.io/people-pairer/)

## Features

* **Easy Input:** Enter names separated by commas in a user-friendly text area.
* **Smart Pairing Logic:**
    * If an **even** number of people are entered, the tool creates pairs.
    * If an **odd** number of people are entered, the tool creates one trio and the rest are pairs.
* **Randomized Groups:** Names are shuffled before pairing to ensure randomness.
* **Clear Output:** Generated groups are displayed in easy-to-read cards.
* **Responsive Design:** Works well on desktop and mobile devices.

## How to Use

1.  **Navigate** to the [People Pairing Tool](https://amandavarella.github.io/people-pairer/).
2.  **Enter Names:** In the text area labeled "Enter Names:", type or paste the names of the people you want to group. Separate each name with a comma (e.g., `Alice, Bob, Charlie, Diana, Eve`).
3.  **Generate:** Click the "Generate Pairs" button.
4.  **View Results:** The generated pairs (and a trio, if applicable) will be displayed below the button.

## Technical Details

* **Frontend:** Built with plain HTML, CSS, and JavaScript.
* **Styling:** Uses [Tailwind CSS](https://tailwindcss.com/) for a modern and responsive design.
* **Logic:**
    * The JavaScript code parses the comma-separated input.
    * It shuffles the array of names using the Fisher-Yates shuffle algorithm.
    * Based on whether the count of names is even or odd, it iterates through the shuffled names to form groups:
        * **Even:** Groups of 2.
        * **Odd:** The first three names form a trio, and the remaining names are grouped into pairs.

## To Run Locally (Optional)

1.  Clone this repository:
    ```bash
    git clone [https://github.com/amandavarella/people-pairer.git](https://github.com/amandavarella/people-pairer.git)
    ```
2.  Navigate to the directory:
    ```bash
    cd people-pairer
    ```
3.  Open the `index.html` file in your web browser.

## Contributing

Suggestions and improvements are welcome! Feel free to open an issue or submit a pull request.

---

*Created by Amanda Varella.*
