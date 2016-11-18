How To Use
==========

1. Navigate to **Settings | Command Line Tool Support** in PhpStorm
2. Press **Add**
3. Choose **Custom Tool** and select the visibility you want
4. Enter the tool details and press OK:
    - Alias (e.g. **dc** for Docker Compose)
    - The path to the tool itself
    - A short description
5. Replace the generated XML definition with the appropriate one for the tool chosen (e.g. **docker-compose.xml** for **Docker Compose**)
6. Open up the **Command Line Tools Console** (Ctl + Shift + X on Windows) and type the alias chosen in step 4 to trigger command completion prompts