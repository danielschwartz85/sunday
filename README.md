  # Sunday
  
  A minimal, offline-capable task manager. No build step, no dependencies — just open `index.html`.
  
  **[Live Demo](https://danielschwartz85.github.io/sunday)**
  
  ## Quick Start
  
  ```bash
  git clone https://github.com/your-username/task-manager.git
  ```
  
  Open `index.html` in a browser, or serve it with GitHub Pages.
  
  ## Storage
  
  On first load you pick a mode:
  
  | Mode | Description |
  |------|-------------|
  | **LocalStorage** | Default. Tasks stay in your browser. |
  | **AirTable** | Syncs to an AirTable base (prompts for credentials once). |
  
  ### AirTable Setup
  
  1. [Sign up for AirTable](https://airtable.com/signup) (free) and create a new "base"
  2. Add a table with a single **Long text** field named `data`
  3. Grab your Base ID and table name from the AirTable URL:

  <img width="1455" height="488" alt="Airtable credentials" src="https://github.com/user-attachments/assets/dd883098-a0d3-4324-ac53-ab18d02a5b4b" />

  4. Create a [Personal Access Token](https://support.airtable.com/docs/creating-personal-access-tokens#creating-personal-access-tokens)
