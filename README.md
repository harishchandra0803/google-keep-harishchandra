# Google Keep Clone - Angular  

This project is a Google Keep clone built using Angular, providing users with a simple and intuitive note-taking experience. It replicates the core functionalities of Google Keep, allowing users to create, update, and delete notes while ensuring a clean UI/UX.



## Features  
- 📝 **Create New Notes** – Add notes with a title and content.  
- ✏ **Update Notes** – Edit existing notes.  
- 🗑 **Delete Notes** – Remove notes when no longer needed.  
- 🎨 **User-Friendly UI** – Inspired by Google Keep’s layout.  
- 💾 **Local Storage Support** – Notes persist even after page reload. 


</div>

# Project structure

It follows a simple structure :

```
📦
└─ src/
   ├─ app/
   │  ├─ components/
   │  │  ├─ input/
   │  │  ├─ main/
   │  │  ├─ navbar/
   │  │  ├─ sidenav/
   │  │  └─ notes/
   │  ├─ db/
   │  ├─ interfaces/
   │  ├─ pipes/
   │  ├─ services/
   │  ├─ app-routing.module.ts
   │  ├─ app.component.ts
   │  └─ app.module.ts
   └─ index.html
```



## Technologies Used  
- **Frontend:** Angular (TypeScript, HTML, CSS)  
- **State Management:** Component-based  
- **Storage:** LocalStorage for data persistence  
- **Styling:** Bootstrap / Tailwind CSS for responsive design  

## Installation & Setup  
1. Clone the repository:  
   ```sh
   git clone https://github.com/yourusername/google-keep-clone.git

   cd google-keep-clone


2.Install dependencies:
npm install
Run the development server:
ng serve
Open your browser and visit:
http://localhost:4200



## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.
