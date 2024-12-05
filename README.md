This application was developed for Web Application module, as coursework portfolio project @ WIUT by student ID: 00013219. 

The run the whole app, we should start from initializing the backend. To do that, the Visual Studio or Rider should be installed to your PC.

But installation let's clone the whole project:

```bash
git clone https://github.com/00013219/feedback-system.git
```

After installing any of these studios run the it, press Open Project, choose the directory where you cloned your project, choose backend. After opening the app, you should run the app, and the browser should be opened right away with Swagger UI. If you want to test the APIs I recommend downloading Postman, since we have authorization in our app the Swagger will be able to run only Register and Login endpoints. 

After running the backend, we should turn to the frontend initialization. Download Visual Studio Code, run it, press Open Folder, choose cloned repository direction, chose frontend. After all that, open Terminal in the VS Code and run the project with the command:

```bash
ng serve
```

Now you should be able to test the project. First Register, then Login, create Feedback, Edit it, Delete it, everything should work.
