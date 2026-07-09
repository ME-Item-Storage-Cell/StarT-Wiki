# [Official Wiki](https://start-dev-team.github.io/StarT-Wiki/) for Star Technology

Official documentation for the Minecraft mod Star Technology (Currently covering info for versions Eta 3 - Theta 1). This wiki aims to cover information such as chemical lines, resource production, gameplay mechanics, and more; with the main goal being a more widely accessible form of help towards new players.

**This wiki is a heavy WIP. If you play Star Technology and want to contribute, find out how to do so [here](https://start-dev-team.github.io/StarT-Wiki/Contributing-to-This-Wiki/)**

<img width="1895" height="916" alt="image" src="https://github.com/user-attachments/assets/8bd5ede2-247c-4982-b4d0-77172aec9a94" />

## Outdated Content
- Plastics (in relation to bacteria and Chem Plant)
- Plastic uses (eg PEEK being moved to UV)
- Resource generation (eg ARC does not exist anymore)

## Tech Stack
This wiki is built in Mkdocs. Other plugins/resources used are listed [here](https://start-dev-team.github.io/StarT-Wiki/Meet-the-Team/Credits/#resources)

## How it works
Works like you would expect from any wiki. You can navigate between categories using the navbar, and then select specific pages using the sidebar. The table of contents on the right hand side allows you to easily find specific information within a page.
<img width="1218" height="360" alt="image" src="https://github.com/user-attachments/assets/8db24e43-bf89-4691-9343-e5272695e8a5" />

The search bar allows you to find relavent pages using specific terms.
<img width="701" height="592" alt="image" src="https://github.com/user-attachments/assets/2a22d067-1479-405b-9d98-cfa4e3c5c084" />

## Running this wiki locally
### Prerequisites
- [Git](https://git-scm.com/downloads)
- [Visual Studio Code](https://code.visualstudio.com/download)
- [GitHub Account](https://github.com/)
- [Python](https://www.python.org/downloads/)

### Preparing the workspace
!!! Note This wiki uses [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) to generate documentation from markdown pages.

1. Fork the [repository](https://github.com/StarT-Dev-Team/StarT-Wiki).
2. Open Visual Studio Code.
3. From the *Welcome* page, click on **Clone Git repository**, select **Clone from GitHub**, and select `YOUR-NAME/StarT-Wiki`.
4. Open a new terminal from the toolbar.
5. Run the following commands:
   - To create the environment:
     ```console
     python -m venv venv
     ```
     or
     
     ```console
     py -m venv venv
     ```

   - To activate the environment:

     **Windows**
     ```console
     .\venv\Scripts\activate
     ```

     **Mac**
     ```console
     source venv/bin/activate
     ```

   - To install Material for MkDocs and other used plugins:
     ```console
     pip install mkdocs-material pymdown-extensions mkdocs-mermaid2-plugin mkdocs-panzoom-plugin
     ```

6. Run this command to launch the app:
   ```console
   mkdocs serve
   ```

   You can now access your local wiki copy at <http://127.0.0.1:8000/>. Any changes you make will be reflected in the browser automatically. To stop the app, press `Ctrl+C` in the terminal.
