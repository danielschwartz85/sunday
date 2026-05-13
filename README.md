# 🚀 Task Manager

A powerful and elegant task management application with a modern dark theme interface. Built with vanilla JavaScript and designed for productivity.

## 🚀 Dev Setup 

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/task-manager.git
   ```
2. Open `index.html` in your web browser

That's it! No build steps or dependencies required.

## 🗄️ Database Persistence (2 options)

On first load, **the app prompts you to choose** a storage mode:

- **LocalStorage** — [default] tasks are stored only in your browser's `localStorage`. The sync button is disabled in this mode.

- **AirTable** — [optional] syncs tasks to an AirTable base. You will be prompted for your table name, Base ID, and API token. See [Airtable Credentials](#getting-your-airtable-credentials). These are saved to `localStorage` so you won't be asked again.


To reset your storage choice (e.g. to switch modes or update credentials), clear `localStorage` for the page and reload.


### Setting up AirTable:

* Open an AirTable base and create a new table for storing tasks - Free!
* The app expects a `data` field in the specified AirTable table:

  | Property   | Value      |
  |------------|------------|
  | Field name | `data`     |
  | Field type | Long text  |


### Getting Your Airtable Credentials
* When first loading the app the user is prompted to set his AirTable credentials, Air Tabel credentials can be found here:
  <img width="1455" height="488" alt="image" src="https://github.com/user-attachments/assets/dd883098-a0d3-4324-ac53-ab18d02a5b4b" />
* For API Key follow [this link](https://support.airtable.com/docs/creating-personal-access-tokens#creating-personal-access-tokens)


## 📝 License

Copyright © 2025 Daniel Schwartz Inc. All Rights Are All Right!

## 🡽 Live Demo

Visit the live application at [Sunday](https://danielschwartz85.github.io/sunday)
