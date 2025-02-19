# BETA-Engineering-Technology-Association Wiki
> wiki.betauia.net

This is the wiki for BETA, which is the student association for computer science students at UiA Grimstad.

Here you will find information about BETA and the different committees:
* BetaLan (Lan Party)
* BetaSec (Security)
  * UiACTF ()
* BetaDev (Development)
* Eventkom (Events)
* Bedkom (Company Presentations)

# For writers
If you want to contribute to the wiki fork it and make a pull request ;). The Board Members will take a look at it.

## Packages and mkdocs
This wiki is written in wikidocs and you can run the wiki on your machine locally with:

### Setting up a Python virtual environment
1. Navigate to the root directory of the wiki.
2. Create a virtual environment:
  ```sh
  python -m venv venv
  ```
3. Activate the virtual environment:
  - On Windows:
    ```sh
    .\venv\Scripts\activate
    ```
  - On macOS/Linux:
    ```sh
    source venv/bin/activate
    ```

### Installing required packages
1. Install `mkdocs` and `awesome-pages`:
  ```sh
  pip install mkdocs mkdocs-awesome-pages-plugin
  ```

### Running the wiki locally
1. Start the mkdocs server:
  ```sh
  mkdocs serve
  ```
2. Open your web browser and go to `http://127.0.0.1:8000` to view the wiki.