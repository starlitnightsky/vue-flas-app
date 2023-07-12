# Vue Flask Template

📦 A template for quickly building web applications! The frontend uses the progressive framework [Vue](https://github.com/vuejs/vue), and the backend uses the microframework [Flask](https://github.com/pallets/flask).

## Instructions

1. Click the green button `Use this template` in the upper right corner of this project, enter a name and description, and complete the creation.

2. Clone the newly created project to the local. Here we take this project as an example. In actual operation, you need to replace your own project.

   ```bash
   git clone https://github.com/Ailln/vue-flask-template.git --depth 1
   ```

3. The installation environment is dependent. This project requires a Node environment and a Python environment. If you are not familiar with this part, please refer to the reference article at the end of this document.

   > Note: Version requirements Node version 12+, Python version 3.6+.

   ```bash
   # The front-end environment depends on the installation
   cd front
   npm install

   # The backend environment depends on the installation
   cd back
   pip install -r requirements.txt
   ```

4. Open two terminals and start the front-end and back-end respectively.

   ```bash
   # start the frontend
   cd front
   npm run dev

   # start the backend
   cd back
   python app.py
   ```

5. Open: `http://localhost:3000/` in the browser to preview.

6. Modify the code according to your needs.

## Project structure

```
.
├── front # front end
│ ├── package.json # front-end dependencies
│ ├── package-lock.json
│ ├── public
│ ├── src
│ │ ├── App.vue # main page
│ │ ├── components # Subcomponents
│ │ │ └── HelloWorld.vue
│ │ ├── assets # Static resources
│ │ └── main.js
│ └── vite.config.js
├── back # backend
│ ├── app.py
│ └── requirements.txt # Backend dependencies
├── README.md
├── LICENSE
└── .gitignore
```

## License

[![](https://award.dovolopor.com?lt=License&rt=MIT&rbc=green)](./LICENSE)

## refer to

- [Vue3 Tutorial](https://v3.cn.vuejs.org/)
- [Vite official Chinese document](https://cn.vitejs.dev/guide/why.html)
- [Flask Official Documentation](https://flask.palletsprojects.com/en/1.1.x/)
- [How to install the Node development environment? ](https://www.v2ai.cn/2018/11/11/linux/7-node-install/)
- [How to install the Python development environment? ](https://www.v2ai.cn/2018/04/29/python/2-python-install/)
