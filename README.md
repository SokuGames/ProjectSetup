# Project

## File Structure
- `assets/`: Contains all the front-end source files besides `index.html`.
  - `css/`: CSS files.
  - `img/`: Image assets.
  - `js/`: JavaScript files.
  - `about.html`, `contact.html`, etc: HTML files.
- `lib/`: External libraries.
- `server/`: Back-end related files.
- `.gitignore`: Files and directories to be ignored by Git.
- `index.html`: HTML index file.
- `package.json`: Project dependencies.
- `README.md`: Project documentation.

## Setup
1. Clone the repository:
    ```sh
    git clone https://github.com/SokuGames/ProjectSetup.git
    ```
2. Navigate into the project directory:
    ```sh
    cd ProjectSetup
    ```
3. (Optional) If using npm for dependencies, run:
    ```sh
    npm install
    ```

## Folder Setup
1. Delete:
    ```sh
    `README.md` file.
    ```
2. Delete if not using:
    ```sh
    `lib/` folder.
    `server/` folder.
    `package.json` file.
    ```
3. Delete CSS and JavaScript bootstrap `<link>` and `<script>` tag in the HTML if not using.

4. Add Author in the `<meta>` tag in the HTML