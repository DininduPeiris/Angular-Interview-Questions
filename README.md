# Angular-Interview-Questions
This repo is a resource for anyone who is going to face an Angular interview

Video - https://www.youtube.com/watch?v=-jeoyDJDsSM

1. What is the use of Angular?
* Angular is a JavaScript UI framework.
* Helps to build SPA.

2. Difference between AngularJs and Angular?
<img width="1156" height="576" alt="image" src="https://github.com/user-attachments/assets/9a4b031d-b225-47b1-a78e-49120c5c02a3" />

3. What are directives in Angular?
* Directives are Angular syntaxes that we write inside HTML.
* Directives change the behavior of HTML DOM.
<img width="1117" height="232" alt="image" src="https://github.com/user-attachments/assets/2a9e1cc4-3a27-45af-9125-dfe707d49e0e" />

4. Explain the different types of Angular directives.
* There are 3 kinds of directives.
<img width="613" height="343" alt="image" src="https://github.com/user-attachments/assets/9fb51cfa-7f5f-46ea-8ba1-6c8d74f58642" />

* Structural directives - Change the DOM layout by adding and removing elements.
<img width="556" height="322" alt="image" src="https://github.com/user-attachments/assets/46f7f20f-9cc9-4385-b31e-163648af92e5" />

* Attribute directives - Change the appearance and behavior of HTML elements.
<img width="636" height="152" alt="image" src="https://github.com/user-attachments/assets/e373770e-dd36-4c47-90ef-a7627b24fbdb" />

* Component directives - Directives with templates. It's like a user control.
<img width="836" height="210" alt="image" src="https://github.com/user-attachments/assets/106050e7-4bcf-4eb1-ba2c-befb9112f439" />
<img width="1150" height="500" alt="image" src="https://github.com/user-attachments/assets/4c535e3c-82ee-40fd-abe2-ecd22aa02267" />

5. Explain the importance of the NPM and the Node_Modules folder?
* NPM helps to install any package
* "node_modules" is the folder where all the packages are installed.

6. What is the importance of the package.json file?
* It has all the JavaScript references needed for a project.

7. What is TypeScript, and why do we need?
* TypeScript superset of JavaScript. It added types to JavaScript.
* TypeScript extends JavaScript by adding types to the language.

8. Explain the importance of Angular CLI?
* Angular CLI is a command-line interface by which we can create an initial Angular project template. So rather than starting from scratch, we have some boilerplate code. (npm install @angular/cli -> ng new myapp)

9. Explain the importance of the Component and Modules.
* Component is where you write your binding code.
* Module logically groups components.

10. What is a decorator in Angular?
* Decorator defines what kind of Angular class it is. For example, if you decorate "@Component", then it says it's an Angular Component; if you put "@NgNodule", it becomes an Angular Module.

11. What is a template?
* An HTML view of Angular in which we can write directives.
* There are two ways of defining a Template: one is Inline, and the other is a separate HTML file.

12. What is data binding?
* Data binding in Angular defines how the view and component communicate with each other. 

13. Explain the four types of Data bindings in Angular?
* Expression/ Interpolation {{}} - Data flows from the component to the view, and we can mix the same with HTML tags.
* Property binding [] - Data flows from the component to the view.
* Event binding () - when you want to send an event from the view to the component.
* Two-way binding [()] - Data flows from the component to the view and vice versa.

14. Explain the architecture of Angular.
![WhatsApp Image 2025-12-07 at 10 41 25_ebbb5bc1](https://github.com/user-attachments/assets/811e869f-61ed-4028-b523-3c06d80895cb)

1. Template - The HTML view of Angular
2. Component - Binds the View and Module
3. Modules - Group components logically
4. Bindings - Defines how the view and component communicate
5. Directive - Changes the HTML DOM behavior
6. Services - Helps to share common logic across the project
7. DI - helps to inject instances across the constructor.

* Template is an HTML view.
* A group of components is logically put into a module.
* To share common logic in the project, we need to have a Service.
* For service, the object is not actually created; it is injected.
* When we have services that we want to put across all the components, then they use Dependency Injection.

* Dependency Injection (DI) is a design pattern used in software development to make code more modular, testable and maintainable. Instead of a class creating its own dependencies, those dependencies are provided (injected) from outside.
<img width="781" height="291" alt="image" src="https://github.com/user-attachments/assets/8233890f-e9d2-4cf0-a5f5-4c7cfd535b77" />
<img width="771" height="460" alt="image" src="https://github.com/user-attachments/assets/b7a6f5a6-7828-4183-b88d-761083c4d8f6" />

15. What is SPA?
* Single Page Application
* Load the UI once and do not reload it again and again.

16. How to implement SPA in Angular?
* To implement SPA in Angular, we need to use Angular Routing.

17. What is Routing?
* Routing is a simple collection that has two things URL and when this URL is called, which component to load.

18. What is Lazy Loading?
* On-demand loading or loading what is essential.

19. How can we implement lazy loading in Angular?
* Divide your project into modules.
* Use "loadChildren" to load modules.

20. What are services in Angular?
* Services help to share common logic across the Angular project.

21. What is Dependency Injection?
* DI is an application design pattern where, rather than creating object instances from within the component, Angular injects it via the constructor. 

22. What are the benefits of DI?
* Decoupling - When you add new dependencies, you do not have to change everywhere.

23. What is the difference between ng serve and ng build?
* "ng serve builds in memory while "ng build" builds on the hard disk. So when you want to go for production "ng build" command is used.

24. Explain the --prod parameter in ng build?
* Ng build --prod flag compresses your JS file, removes comments, creates GUIDs of your JS files, and makes your application ready for production. 

