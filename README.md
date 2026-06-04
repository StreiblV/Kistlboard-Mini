# Kistlboard Mini

A self-hostable mini version of Kistlboard, linking the CMS and web app repositories for an easy full-project setup.

This repository acts as the main entry point for the mini version and links together the two required parts of the project:

* **Kistlboard-CMS Mini** – the backend / CMS
* **Kistlboard-Web Mini** – the frontend / web app

The goal of this project is to provide a simple starting point that can be cloned, customized, and deployed in your own environment.

---

## Repositories

This project consists of the following repositories:

| Repository              | Description                                   |
| ----------------------- | --------------------------------------------- |
| `Kistlboard-CMS-Mini` | Backend / CMS for managing the content        |
| `Kistlboard-Web-Mini` | Frontend / web app for displaying the content |

---

## Getting Started

This repository uses Git submodules to include both project parts.

To clone the full project, including all submodules, use:

```bash
git clone --recurse-submodules https://github.com/YOUR-USERNAME/Kistlboard-Mini.git
cd Kistlboard-Mini
```

If you already cloned the repository without submodules, run:

```bash
git submodule update --init --recursive
```

---

## Project Structure

```text
Kistlboard-Mini/
├── cms/    # Kistlboard CMS Mini
├── web/    # Kistlboard Web Mini
└── README.md
```

---

## Setup

Each part of the project has its own setup instructions.

Please check the README files inside the individual repositories:

```text
cms/README.md
web/README.md
```

Typical setup steps may include:

1. Install dependencies
2. Configure environment variables
3. Setup your DB for CMS
4. Start the CMS
5. Start the web app
6. Deploy the project to your own server or hosting environment

---

## Updating Submodules

To update the linked repositories to their latest versions, run:

```bash
git submodule update --remote --merge
```

Then commit the updated submodule references:

```bash
git add .
git commit -m "Update submodules"
git push
```

---

## Customization

You are free to customize this project to fit your own needs.

Possible changes include:

* adjusting the design
* changing the content structure
* modifying the CMS fields
* adapting the frontend layout
* deploying it to your own infrastructure

---

## License

This project is licensed under the MIT License.

Please note that the linked repositories should also include their own license files.

---

## Author

Created by **Contentkistl / StreiblV**.

