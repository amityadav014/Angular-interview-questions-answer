# Angular Interview Questions and Answers
---
---

### Table of Contents

| No. | Questions |
|---- | ---------
|1 | [What is Angular Framework?](#what-is-angular-framework)|
|2 | [What is the difference between AngularJS and Angular?](#what-is-the-difference-between-angularjs-and-angular)|
|3 | [What is TypeScript?](#what-is-typescript)|
|4 | [Write a pictorial diagram of Angular architecture?](#write-a-pictorial-diagram-of-angular-architecture)|
|5 | [What are the key components of Angular?](#what-are-the-key-components-of-angular)|
|6 | [What are directives?](#what-are-directives)|
|7 | [What are components?](#what-are-components)|
|8 | [What are the differences between Component and Directive?](#what-are-the-differences-between-component-and-directive)|
|9 | [What is a template?](#what-is-a-template)|
|10| [What is a module?](#what-is-a-module)|
|11| [What are lifecycle hooks available?](#what-are-lifecycle-hooks-available)|
|12| [What is a data binding?](#what-is-a-data-binding)|
|13| [What is metadata?](#what-is-metadata)|
|14| [What is Angular CLI?](#what-is-angular-cli)|
|15| [What is the difference between constructor and ngOnInit?](#what-is-the-difference-between-constructor-and-ngoninit)|
|16| [What is a service](#what-is-a-service)|
|17| [What is dependency injection in Angular?](#what-is-dependency-injection-in-angular)|
|18| [What is the option to choose between inline and external template file?](#what-is-the-option-to-choose-between-inline-and-external-template-file)|
|19| [What is the purpose of *ngFor directive?](#what-is-the-purpose-of-ngfor-directive)|
|20| [What is the purpose of ngIf directive?](#what-is-the-purpose-of-ngif-directive)|
|21| [What is interpolation?](#what-is-interpolation)|
|22| [What are template expressions?](#what-are-template-expressions)|
|23| [What are template statements?](#what-are-template-statements)|
|24| [How do you categorize data binding types?](#how-do-you-categorize-data-binding-types)|
|25| [What are pipes?](#what-are-pipes)|
|26| [What is a parameterized pipe?](#what-is-a-parameterized-pipe)|
|27| [How do you chain pipes?](#how-do-you-chain-pipes)|
|28| [What is a custom pipe?](#what-is-a-custom-pipe)|
|29| [Give an example of custom pipe?](#give-an-example-of-custom-pipe)|
|30| [What is the difference between pure and impure pipe?](#what-is-the-difference-between-pure-and-impure-pipe)|
|31| [What is a bootstrapping module?](#what-is-a-bootstrapping-module)|
|32| [What are observables?](#what-are-observables)|
|33| [What is HttpClient and its benefits?](#what-is-httpclient-and-its-benefits)|
|34| [Explain on how to use HttpClient with an example?](#explain-on-how-to-use-httpclient-with-an-example)|
|35| [What is RxJS?](#what-is-rxjs)|
|36| [What is subscribing?](#what-is-subscribing)|
|37| [What is an observable?](#what-is-an-observable)|
|38| [What is an observer?](#what-is-an-observer)|
|39| [What is the difference between promise and observable?](#what-is-the-difference-between-promise-and-observable)|
|40| [What is multicasting?](#what-is-multicasting)|
|41| [How do you perform error handling in observables?](#how-do-you-perform-error-handling-in-observables)|
|42| [What is the shorthand notation for subscribe method?](#what-is-the-shorthand-notation-for-subscribe-method)|
|43| [What are observable creation functions?](#what-are-observable-creation-functions)|
|44| [What are the various kinds of directives?](#what-are-the-various-kinds-of-directives)|
|45| [How do you create directives using CLI?](#how-do-you-create-directives-using-cli)|
|46| [What is Angular Router?](#what-is-angular-router)|
|47| [What is the purpose of base href tag?](#what-is-the-purpose-of-base-href-tag)|
|48| [What are the router imports?](#what-are-the-router-imports)|
|49| [What is router outlet?](#what-is-router-outlet)|
|50| [What are router links?](#what-are-router-links)|
|51| [What are active router links?](#what-are-active-router-links)|
|52| [What is router state?](#what-is-router-state)|
|53| [What are router events?](#what-are-router-events)|
|54| [What is activated route?](#what-is-activated-route)|
|55| [How do you define routes?](#how-do-you-define-routes)|
|56| [What is the purpose of Wildcard route?](#what-is-the-purpose-of-wildcard-route)|
|57| [Do I need a Routing Module always?](#do-i-need-a-routing-module-always)|
|58| [What is Angular Universal?](#what-is-angular-universal)|
|59| [What are different types of compilation in Angular?](#what-are-different-types-of-compilation-in-angular)|
|60| [What is JIT?](#what-is-jit)|
|61| [What is AOT?](#what-is-aot)|
|62| [Why do we need compilation process?](#why-do-we-need-compilation-process)|
|63| [What are the advantages with AOT?](#what-are-the-advantages-with-aot)|
|64| [What are the ways to control AOT compilation?](#what-are-the-ways-to-control-aot-compilation)|
|65| [What are the restrictions of metadata?](#what-are-the-restrictions-of-metadata)|
|66| [What are the three phases of AOT?](#what-are-the-three-phases-of-aot)|
|67| [Can I use arrow functions in AOT?](#can-i-use-arrow-functions-in-aot)|
|68| [What is the purpose of metadata json files?](#what-is-the-purpose-of-metadata-json-files)|
|69| [Can I use any javascript feature for expression syntax in AOT?](#can-i-use-any-javascript-feature-for-expression-syntax-in-aot)|
|70| [What is folding?](#what-is-folding)|
|71| [What are macros?](#what-are-macros)|
|72| [How do you provide configuration inheritance?](#how-do-you-provide-configuration-inheritance)|
|73| [What is transition function?](#what-is-transition-function)|
|74| [How to inject the dynamic script in angular?](#how-to-inject-the-dynamic-script-in-angular)|
|75| [What is Angular Ivy?](#what-is-angular-ivy)|
|76| [What are the features included in ivy preview?](#what-are-the-features-included-in-ivy-preview)|
|77| [Can I use AOT compilation with Ivy?](#can-i-use-aot-compilation-with-ivy)|
|78| [What are the class decorators in Angular?](#what-are-the-class-decorators-in-angular)|
|79| [What are class field decorators?](#what-are-class-field-decorators)|
|80| [What is declarable in Angular?](#what-is-declarable-in-angular)|
|81| [What is an rxjs Subject?](#what-is-an-rxjs-Subject)|
|82| [What happens if I import the same module twice?](#what-happens-if-i-import-the-same-module-twice)|
|83| [How do you pass headers for HTTP client?](#how-do-you-pass-headers-for-http-client)|
|84| [What is lazy loading?](#what-is-lazy-loading)|
|85| [How do you upgrade angular version?](#how-do-you-upgrade-angular-version)|
|86| [What is Angular Material?](#what-is-angular-material)|
|87| [How do you upgrade location service of angularjs?](#how-do-you-upgrade-location-service-of-angularjs)|
|88| [What are the differences of various versions of Angular?](#what-are-the-differences-of-various-versions-of-angular)|
|89| [How do you find angular CLI version?](#how-do-you-find-angular-cli-version)|
|90| [What is Angular security model for preventing XSS attacks?](#what-is-angular-security-model-for-preventing-xss-attacks)|
|91| [What are the various security contexts in Angular?](#what-are-the-various-security-contexts-in-Angular)|
|92| [What is Sanitization? Is angular supports it?](#what-is-sanitization?Is-angular-supports-it)|
|93| [What is the purpose of innerHTML?](#what-is-the-purpose-of-innerhtml)|
|94| [What is the difference between interpolated content and innerHTML?](#what-is-the-difference-between-interpolated-content-and-innerhtml)|
|95| [What are Http Interceptors?](#what-are-http-interceptors)|
|96| [What are the applications of HTTP interceptors?](#what-are-the-applications-of-http-interceptors)|
|97| [How can I use interceptor for an entire application?](#how-can-i-use-interceptor-for-an-entire-application)|
|98| [What is AOT compiler?](#what-is-aot-compiler)|
|99| [What is protractor?](#what-is-protractor)|
|100| [How do you use jquery in Angular?](#how-do-you-use-jquery-in-angular)|
|101| [What is the reason for No provider for HTTP exception?](#what-is-the-reason-for-no-provider-for-http-exception)|
|102| [What is router state?](#what-is-router-state)|
|103| [How can I use SASS in angular project?](#how-can-i-use-sass-in-angular-project)|
|104| [What is the purpose of hidden property?](#what-is-the-purpose-of-hidden-property)|
|105| [What is the difference between ngIf and hidden property?](#what-is-the-difference-between-ngif-and-hidden-property)|
|106| [What is slice pipe?](#what-is-slice-pipe)|
|107| [What is the purpose of ngFor trackBy?](#what-is-the-purpose-of-ngfor-trackby)|
|108| [What is the purpose of ngSwitch directive?](#what-is-the-purpose-of-ngswitch-directive)|
|109| [What is the precedence between pipe and ternary operators?](#what-is-the-precedence-between-pipe-and-ternary-operators)
|110| [What is a bootstrapped component?](#what-is-a-bootstrapped-component)|
|111| [How do you manually bootstrap an application?](#how-do-you-manually-bootstrap-an-application)|
|112| [Is it necessary for bootstrapped component to be entry component?](#is-it-necessary-for-bootstrapped-component-to-be-entry-component)|
|113| [What is a routed entry component?](#what-is-a-routed-entry-component#)|
|114| [Why is not necessary to use entryComponents array every time?](#why-is-not-necessary-to-use-entrycomponents-array-every-time)|
|115| [Do I still need to use entryComponents array in Angular9?](#do-i-still-need-to-use-entrycomponents-array-in-angular9#)|
|116| [Is it all components generated in production build?](#is-it-all-components-generated-in-production-build)|
|117| [What is Angular compiler?](#what-is-angular-compiler)|
|118| [What is the role of ngModule metadata in compilation process?](#what-is-the-role-of-ngmodule-metadata-in-compilation-process)|
|119| [How does angular finds components, directives and pipes?](#how-does-angular-finds-components-directives-and-pipes)|
|120| [What is a shared module?](#what-is-a-shared-module)|
|121| [What are reactive forms?](#what-are-reactive-forms)|
|122| [What are dynamic forms?](#what-are-dynamic-forms)|
|123| [What are template driven forms?](#what-are-template-driven-forms)|
|124| [What are the differences between reactive forms and template driven forms?](#what-are-the-differences-between-reactive-forms-and-template-driven-forms)|
|125| [What is the purpose of FormBuilder?](#what-is-the-purpose-of-formbuilder)|
|126| [How do you reset the form?](#how-do-you-reset-the-form)|
|127| [Can you give an example of built-in validators?](#can-you-give-an-example-of-built-in-validators)|
|128| [How to set ngFor and ngIf on the same element?](#how-to-set-ngfor-and-ngif-on-the-same-element)|




1. ### What is Angular Framework?

    Angular is a **TypeScript-based open-source** front-end platform that makes it easy to build web, mobile and desktop applications. The major features of this framework include declarative templates, dependency injection, end to end tooling which ease application development.

2. ### What is the difference between AngularJS and Angular?
    Angular is a completely revived component-based framework in which an application is a tree of individual components.

    Here are some of the major differences in tabular format:-

    | AngularJS | Angular |
    |---- | ---------
    | It is based on MVC architecture| This is based on Service/Controller|
    | It uses JavaScript to build the application| Uses TypeScript to build the application|
    | Based on controllers concept| This is a component based UI approach|
    | No support for mobile platforms| Fully supports mobile platforms|
    | Difficult to build SEO friendly application| Ease to build SEO friendly applications|


3. ### What is TypeScript?
    TypeScript is a strongly typed superset of JavaScript created by Microsoft that adds optional types, classes, async/await and many other features, and compiles to plain JavaScript. Angular is written entirely in TypeScript as a primary language.
    You can install TypeScript globally as
    ```cmd
    npm install -g typescript
    ```
    Let's see a simple example of TypeScript usage:-
    ```typescript
    function greeter(person: string) {
        return "Hello, " + person;
    }

    let user = "Sudheer";

    document.body.innerHTML = greeter(user);
    ```
    The greeter method allows only string type as argument.


4. ### Write a pictorial diagram of Angular architecture?
    The main building blocks of an Angular application are shown in the diagram below:-
    ![ScreenShot](images/architecture.png)


5. ### What are the key components of Angular?
    Angular has the key components below,
    1. **Component:** These are the basic building blocks of an Angular application to control HTML views.
    2. **Modules:** An Angular module is a set of angular basic building blocks like components, directives, services etc. An application is divided into logical pieces and each piece of code is called as "module" which perform a single task.
    3. **Templates:** These represent the views of an Angular application.
    4. **Services:** Are used to create components which can be shared across the entire application.
    5. **Metadata:** This can be used to add more data to an Angular class.

6. ### What are directives?
    Directives add behaviour to an existing DOM element or an existing component instance.
    ```typescript
    import { Directive, ElementRef, Input } from '@angular/core';

    @Directive({ selector: '[myHighlight]' })
    export class HighlightDirective {
        constructor(el: ElementRef) {
           el.nativeElement.style.backgroundColor = 'yellow';
        }
    }
    ```

    Now this directive extends HTML element behavior with a yellow background as below
    ```html
    <p myHighlight>Highlight me!</p>
    ```
 

7. ### What are components?
    Components are the most basic UI building block of an Angular app, which form a tree of Angular components. These components are a subset of directives. Unlike directives, components always have a template, and only one component can be instantiated per element in a template.
    Let's see a simple example of Angular component
    ```typescript
    import { Component } from '@angular/core';

    @Component ({
       selector: 'my-app',
       template: ` <div>
          <h1>{{title}}</h1>
          <div>Learn Angular6 with examples</div>
       </div> `,
    })

    export class AppComponent {
       title: string = 'Welcome to Angular world';
    }
    ```


8. ### What are the differences between Component and Directive?
    In a short note, A component(@component) is a directive-with-a-template.

    Some of the major differences are mentioned in a tabular form

    | Component | Directive |
    |---- | ---------
    | To register a component we use @Component meta-data annotation  | To register a directive we use @Directive meta-data annotation |
    | Components are typically used to create UI widgets| Directives are used to add behavior to an existing DOM element |
    | Component is used to break down the application into smaller components| Directive is used to design re-usable components|
    | Only one component can be present per DOM element | Many directives can be used per DOM element |
    | @View decorator or templateurl/template are mandatory | Directive doesn't use View|

9. ### What is a template?
    A template is a HTML view where you can display data by binding controls to properties of an Angular component. You can store your component's template in one of two places. You can define it inline using the template property, or you can define the template in a separate HTML file and link to it in the component metadata using the @Component decorator's templateUrl property.

    **Using inline template with template syntax,**
    ```typescript
    import { Component } from '@angular/core';

    @Component ({
       selector: 'my-app',
       template: '
          <div>
             <h1>{{title}}</h1>
             <div>Learn Angular</div>
          </div>
       '
    })

    export class AppComponent {
       title: string = 'Hello World';
    }
    ```
    **Using separate template file such as app.component.html**
    ```typescript
    import { Component } from '@angular/core';

    @Component ({
       selector: 'my-app',
       templateUrl: 'app/app.component.html'
    })

    export class AppComponent {
       title: string = 'Hello World';
    }
    ```


10. ### What is a module?

    Modules are logical boundaries in your application and the application is divided into separate modules to separate the functionality of your application.
    Lets take an example of **app.module.ts** root module declared with **@NgModule** decorator as below,
    ```typescript
    import { NgModule }      from '@angular/core';
    import { BrowserModule } from '@angular/platform-browser';
    import { AppComponent }  from './app.component';

    @NgModule ({
       imports:      [ BrowserModule ],
       declarations: [ AppComponent ],
       bootstrap:    [ AppComponent ],
       providers: []
    })
    export class AppModule { }
    ```
    The NgModule decorator has five important (among all) options:
    1. The imports option is used to import other dependent modules. The BrowserModule is required by default for any web based angular application.
    2. The declarations option is used to define components in the respective module.
    3. The bootstrap option tells Angular which Component to bootstrap in the application.
    4. The providers option is used to configure a set of injectable objects that are available in the injector of this module.
    5. The entryComponents option is a set of components dynamically loaded into the view.

11. ### What are lifecycle hooks available?
    Angular application goes through an entire set of processes or has a lifecycle right from its initiation to the end of the application.
    The representation of lifecycle in pictorial representation as follows,

    ![ScreenShot](images/lifecycle.png)

    The description of each lifecycle method is as below,
    1. **ngOnChanges:** When the value of a data bound property changes, then this method is called.
    2. **ngOnInit:** This is called whenever the initialization of the directive/component after Angular first displays the data-bound properties happens.
    3. **ngDoCheck:** This is for the detection and to act on changes that Angular can't or won't detect on its own.
    4. **ngAfterContentInit:** This is called in response after Angular projects external content into the component's view.
    5. **ngAfterContentChecked:** This is called in response after Angular checks the content projected into the component.
    6. **ngAfterViewInit:** This is called in response after Angular initializes the component's views and child views.
    7. **ngAfterViewChecked:** This is called in response after Angular checks the component's views and child views.
    8. **ngOnDestroy:** This is the cleanup phase just before Angular destroys the directive/component.

12. ### What is a data binding?
    Data binding is a core concept in Angular and allows to define communication between a component and the DOM, making it very easy to define interactive applications without worrying about pushing and pulling data. There are four forms of data binding(divided as 3 categories) which differ in the way the data is flowing.
    1. **From the Component to the DOM:**

        **Interpolation:** {{ value }}: Adds the value of a property from the component
        ```html
        <li>Name: {{ user.name }}</li>
        <li>Address: {{ user.address }}</li>
        ```
        **Property binding:** [property]=”value”: The value is passed from the component to the specified property or simple HTML attribute
        ```html
        <input type="email" [value]="user.email">
        ```
    2. **From the DOM to the Component:**
        **Event binding: (event)=”function”:** When a specific DOM event happens (eg.: click, change, keyup), call the specified method in the component
        ```html
        <button (click)="logout()"></button>
        ```
    3. **Two-way binding:**
        **Two-way data binding:** [(ngModel)]=”value”: Two-way data binding allows to have the data flow both ways. For example, in the below code snippet, both the email DOM input and component email property are in sync
        ```html
        <input type="email" [(ngModel)]="user.email">
        ```

13. ### What is metadata?
    Metadata is used to decorate a class so that it can configure the expected behavior of the class. The metadata is represented by decorators
    1. **Class decorators**, e.g. @Component and @NgModule
        ```typescript
        import { NgModule, Component } from '@angular/core';

        @Component({
          selector: 'my-component',
          template: '<div>Class decorator</div>',
        })
        export class MyComponent {
          constructor() {
            console.log('Hey I am a component!');
          }
        }

        @NgModule({
          imports: [],
          declarations: [],
        })
        export class MyModule {
          constructor() {
            console.log('Hey I am a module!');
          }
        }
        ```
    2. **Property decorators** Used for properties inside classes, e.g. @Input and @Output
        ```typescript
        import { Component, Input } from '@angular/core';

        @Component({
            selector: 'my-component',
            template: '<div>Property decorator</div>'
        })

        export class MyComponent {
            @Input()
            title: string;
        }
        ```
    3. **Method decorators** Used for methods inside classes, e.g. @HostListener
        ```typescript
        import { Component, HostListener } from '@angular/core';

        @Component({
            selector: 'my-component',
            template: '<div>Method decorator</div>'
        })
        export class MyComponent {
            @HostListener('click', ['$event'])
            onHostClick(event: Event) {
                // clicked, `event` available
            }
        }
        ```
    4. **Parameter decorators** Used for parameters inside class constructors, e.g. @Inject, @Optional
        ```typescript
        import { Component, Inject } from '@angular/core';
        import { MyService } from './my-service';

        @Component({
            selector: 'my-component',
            template: '<div>Parameter decorator</div>'
        })
        export class MyComponent {
            constructor(@Inject(MyService) myService) {
                console.log(myService); // MyService
            }
        }
        ```


14. ### What is angular CLI?
    Angular CLI(**Command Line Interface**) is a command line interface to scaffold and build angular apps using nodejs style (commonJs) modules.
    You need to install using below npm command,
    ```
    npm install @angular/cli@latest
    ```
    Below are the list of few commands, which will come handy while creating angular projects
    1. **Creating New Project:** ng new <project-name>

    2. **Generating Components, Directives & Services:** ng generate/g <feature-name>
        The different types of commands would be,
        * ng generate class my-new-class: add a class to your application
        * ng generate component my-new-component: add a component to your application
        * ng generate directive my-new-directive: add a directive to your application
        * ng generate enum my-new-enum: add an enum to your application
        * ng generate module my-new-module: add a module to your application
        * ng generate pipe my-new-pipe: add a pipe to your application
        * ng generate service my-new-service: add a service to your application

    3. **Running the Project:** ng serve



15. ### What is the difference between constructor and ngOnInit?
    The **Constructor** is a default method of the class that is executed when the class is instantiated and ensures proper initialisation of fields in the class and its subclasses. Angular, or better Dependency Injector (DI), analyses the constructor parameters and when it creates a new instance by calling new MyClass() it tries to find providers that match the types of the constructor parameters, resolves them and passes them to the constructor.  
    **ngOnInit** is a life cycle hook called by Angular to indicate that Angular is done creating the component.  
    Mostly we use ngOnInit for all the initialization/declaration and avoid stuff to work in the constructor. The constructor should only be used to initialize class members but shouldn't do actual "work".
    So you should use constructor() to setup Dependency Injection and not much else. ngOnInit() is better place to "start" - it's where/when components' bindings are resolved.

    ```typescript
    export class App implements OnInit{
      constructor(private myService: MyService){
         //called first time before the ngOnInit()
      }

      ngOnInit(){
         //called after the constructor and called  after the first ngOnChanges()
         //e.g. http call...
      }
    }
    ```


16. ### What is a service?
    A service is used when a common functionality needs to be provided to various modules. Services allow for greater separation of concerns for your application and better modularity by allowing you to extract common functionality out of components.

    Let's create a repoService which can be used across components,

    ```typescript
    import { Injectable } from '@angular/core';
    import { Http } from '@angular/http';

    @Injectable({ // The Injectable decorator is required for dependency injection to work
      // providedIn option registers the service with a specific NgModule
      providedIn: 'root',  // This declares the service with the root app (AppModule)
    })
    export class RepoService{
      constructor(private http: Http){
      }

      fetchAll(){
        return this.http.get('https://api.github.com/repositories');
      }
    }
    ```
    The above service uses Http service as a dependency.



17. ### What is dependency injection in Angular?
    Dependency injection (DI), is an important application design pattern in which a class asks for dependencies from external sources rather than creating them itself. Angular comes with its own dependency injection framework for resolving dependencies( services or objects that a class needs to perform its function).So you can have your services depend on other services throughout your application.



20. ### What is the option to choose between inline and external template file?
    You can store your component's template in one of two places. You can define it inline using the **template** property, or you can define the template in a separate HTML file and link to it in the component metadata using the **@Component** decorator's **templateUrl** property.

    The choice between inline and separate HTML is a matter of taste, circumstances, and organization policy. But normally we use inline template for small portion of code and external template file for bigger views. By default, the Angular CLI generates components with a template file. But you can override that with the below command,
    ```
    ng generate component hero -it
    ```



21. ### What is the purpose of `*ngFor` directive?
    We use Angular `*ngFor` directive in the template to display each item in the list. For example, here we can iterate over a list of users:
    ```html
    <li *ngFor="let user of users">
      {{ user }}
    </li>
    ```
    The user variable in the `*ngFor` double-quoted instruction is a **template input variable**.


22. ### What is the purpose of `*ngIf` directive?
    Sometimes an app needs to display a view or a portion of a view only under specific circumstances. The Angular `*ngIf` directive inserts or removes an element based on a truthy/falsy condition. Let's take an example to display a message if the user age is more than 18:
    ```html
    <p *ngIf="user.age > 18">You are not eligible for student pass!</p>
    ```
    **Note:** Angular isn't showing and hiding the message. It is adding and removing the paragraph element from the DOM. That improves performance, especially in the larger projects with many data bindings.

24. ### What is interpolation?

    Interpolation is a special syntax that Angular converts into property binding. It’s a convenient alternative to property binding. It is represented by double curly braces({{}}). The text between the braces is often the name of a component property. Angular replaces that name with the string value of the corresponding component property.

    Let's take an example,
    ```html
    <h3>
      {{title}}
      <img src="{{url}}" style="height:30px">
    </h3>
    ```
    In the example above, Angular evaluates the title and url properties and fills in the blanks, first displaying a bold application title and then a URL.



25. ### What are template expressions?
    A template expression produces a value similar to any Javascript expression. Angular executes the expression and assigns it to a property of a binding target; the target might be an HTML element, a component, or a directive. In the property binding, a template expression appears in quotes to the right of the = symbol as in `[property]="expression"`.
    In interpolation syntax, the template expression is surrounded by double curly braces. For example, in the below interpolation, the template expression is `{{username}}`,

    ```html
    <h3>{{username}}, welcome to Angular</h3>
    ```

    The below javascript expressions are prohibited in template expression
    1. assignments (=, +=, -=, ...)
    2. new
    3. chaining expressions with ; or ,
    4. increment and decrement operators (++ and --)
    ----------------------------------



26. ### What are template statements?
    A template statement responds to an event raised by a binding target such as an element, component, or directive. The template statements appear in quotes to the right of the = symbol like `(event)="statement"`.

    Let's take an example of button click event's statement

    ```html
    <button (click)="editProfile()">Edit Profile</button>
    ```
    In the above expression, editProfile is a template statement. The below JavaScript syntax expressions are not allowed.
    1. new
    2. increment and decrement operators, ++ and --
    3. operator assignment, such as += and -=
    4. the bitwise operators | and &
    5. the template expression operators
    --------------------------------------


27. ### How do you categorize data binding types?

     Binding types can be grouped into three categories distinguished by the direction of data flow. They are listed as below,
     1. From the source-to-view
     2. From view-to-source
     3. View-to-source-to-view

     The possible binding syntax can be tabularized as below,

      | Data direction | Syntax | Type |
      |---- | --------- | ---- |
      | From the source-to-view(One-way)  | 1. {{expression}} 2. [target]="expression" 3. bind-target="expression" | Interpolation, Property, Attribute, Class, Style|
      | From view-to-source(One-way) | 1. (target)="statement" 2. on-target="statement" | Event |
      | View-to-source-to-view(Two-way)| 1. [(target)]="expression" 2. bindon-target="expression"| Two-way |



28. ### What are pipes?
    Pipes are simple functions that use [template expressions](#what-are-template-expressions) to accept data as input and transform it into a desired output. For example, let us take a pipe to transform a component's birthday property into a human-friendly date using **date** pipe.

    ```javascript
    import { Component } from '@angular/core';

    @Component({
      selector: 'app-birthday',
      template: `<p>Birthday is {{ birthday | date }}</p>`
    })
    export class BirthdayComponent {
      birthday = new Date(1987, 6, 18); // June 18, 1987
    }
    ```

29. ### What is a parameterized pipe?
    A pipe can accept any number of optional parameters to fine-tune its output. The parameterized pipe can be created by declaring the pipe name with a colon ( : ) and then the parameter value. If the pipe accepts multiple parameters, separate the values with colons. Let's take a birthday example with a particular format(dd/MM/yyyy):

    ```javascript
    import { Component } from '@angular/core';

        @Component({
          selector: 'app-birthday',
          template: `<p>Birthday is {{ birthday | date:'dd/MM/yyyy'}}</p>` // 18/06/1987
        })
        export class BirthdayComponent {
          birthday = new Date(1987, 6, 18);
        }
    ```
    **Note:** The parameter value can be any valid template expression, such as a string literal or a component property.


30. ### How do you chain pipes?
    You can chain pipes together in potentially useful combinations as per the needs. Let's take a birthday property which uses date pipe(along with parameter) and uppercase pipes as below

    ```javascript
    import { Component } from '@angular/core';

            @Component({
              selector: 'app-birthday',
              template: `<p>Birthday is {{  birthday | date:'fullDate' | uppercase}} </p>` // THURSDAY, JUNE 18, 1987
            })
            export class BirthdayComponent {
              birthday = new Date(1987, 6, 18);
            }

    ```


31. ### What is a custom pipe?
    Apart from built-in pipes, you can write your own custom pipe with the below key characteristics:
    1. A pipe is a class decorated with pipe metadata `@Pipe` decorator, which you import from the core Angular library
       For example,
        ```javascript
            @Pipe({name: 'myCustomPipe'})
        ```
    2. The pipe class implements the **PipeTransform** interface's transform method that accepts an input value followed by optional parameters and returns the transformed value.
       The structure of `PipeTransform` would be as below,
        ```javascript
        interface PipeTransform {
          transform(value: any, ...args: any[]): any
        }
        ```
    3. The `@Pipe` decorator allows you to define the pipe name that you'll use within template expressions. It must be a valid JavaScript identifier.
        ```javascript
        template: `{{someInputValue | myCustomPipe: someOtherValue}}`
        ```


32. ### Give an example of custom pipe?
    You can create custom reusable pipes for the transformation of existing value. For example, let us create a custom pipe for finding file size based on an extension,
      ```javascript
        import { Pipe, PipeTransform } from '@angular/core';

        @Pipe({name: 'customFileSizePipe'})
        export class FileSizePipe implements PipeTransform {
          transform(size: number, extension: string = 'MB'): string {
            return (size / (1024 * 1024)).toFixed(2) + extension;
          }
        }
      ```
    Now you can use the above pipe in template expression as below,
      ```javascript
         template: `
            <h2>Find the size of a file</h2>
            <p>Size: {{288966 | customFileSizePipe: 'GB'}}</p>
          `
      ```


33. ### What is the difference between pure and impure pipe?
    A pure pipe is only called when Angular detects a change in the value or the parameters passed to a pipe. For example, any changes to a primitive input value (String, Number, Boolean, Symbol) or a changed object reference (Date, Array, Function, Object). An impure pipe is called for every change detection cycle no matter whether the value or parameters changes. i.e, An impure pipe is called often, as often as every keystroke or mouse-move.



34. ### What is a bootstrapping module?
    Every application has at least one Angular module, the root module that you bootstrap to launch the application is called as bootstrapping module. It is commonly known as `AppModule`. The default structure of `AppModule` generated by AngularCLI would be as follows:
	
	```javascript
        import { BrowserModule } from '@angular/platform-browser';
        import { NgModule } from '@angular/core';
        import { FormsModule } from '@angular/forms';
        import { HttpClientModule } from '@angular/common/http';

        import { AppComponent } from './app.component';

        /* the AppModule class with the @NgModule decorator */
        @NgModule({
          declarations: [
            AppComponent
          ],
          imports: [
            BrowserModule,
            FormsModule,
            HttpClientModule
          ],
          providers: [],
          bootstrap: [AppComponent]
        })
        export class AppModule { }
	```


35. ### What are observables?
    Observables are declarative which provide support for passing messages between publishers and subscribers in your application. They are mainly used for event handling, asynchronous programming, and handling multiple values. In this case, you define a function for publishing values, but it is not executed until a consumer subscribes to it. The subscribed consumer then receives notifications until the function completes, or until they unsubscribe.



36. ### What is HttpClient and its benefits?
    Most of the Front-end applications communicate with backend services over `HTTP` protocol using either `XMLHttpRequest` interface or the `fetch()` API. Angular provides a simplified client HTTP API known as `HttpClient` which is based on top of `XMLHttpRequest` interface. This client is available from `@angular/common/http` package.
    You can import in your root module as below:

    ```javascript
    import { HttpClientModule } from '@angular/common/http';
    ```

    The major advantages of HttpClient can be listed as below,
    1. Contains testability features
    2. Provides typed request and response objects
    3. Intercept request and response
    4. Supports Observalbe APIs
    5. Supports streamlined error handling


37. ### Explain on how to use `HttpClient` with an example?
    Below are the steps need to be followed for the usage of `HttpClient`.
    1. Import `HttpClient` into root module:
        ```javascript
        import { HttpClientModule } from '@angular/common/http';
        @NgModule({
          imports: [
            BrowserModule,
            // import HttpClientModule after BrowserModule.
            HttpClientModule,
          ],
          ......
          })
         export class AppModule {}
        ```
    2. Inject the `HttpClient` into the application:
        Let's create a userProfileService(`userprofile.service.ts`) as an example. It also defines get method of `HttpClient`:
        ```javascript
        import { Injectable } from '@angular/core';
        import { HttpClient } from '@angular/common/http';

        const userProfileUrl: string = 'assets/data/profile.json';

        @Injectable()
        export class UserProfileService {
          constructor(private http: HttpClient) { }

          getUserProfile() {
            return this.http.get(this.userProfileUrl);
          }
        }
        ```
    3. Create a component for subscribing service:
        Let's create a component called UserProfileComponent(`userprofile.component.ts`), which injects `UserProfileService` and invokes the service method:
        ```javascript
        fetchUserProfile() {
          this.userProfileService.getUserProfile()
            .subscribe((data: User) => this.user = {
                id: data['userId'],
                name: data['firstName'],
                city:  data['city']
            });
        }
        ```
    Since the above service method returns an Observable which needs to be subscribed in the component.


40. ### What is RxJS?
    RxJS is a library for composing asynchronous and callback-based code in a functional, reactive style using Observables. Many APIs such as  HttpClient produce and consume RxJS Observables and also uses operators for processing observables.

    For example, you can import observables and operators for using HttpClient as below,
    ```javascript
    import { Observable, throwError } from 'rxjs';
    import { catchError, retry } from 'rxjs/operators';
    ```


41. ### What is subscribing?
    An Observable instance begins publishing values only when someone subscribes to it. So you need to subscribe by calling the `subscribe()` method of the instance, passing an observer object to receive the notifications.

    Let's take an example of creating and subscribing to a simple observable, with an observer that logs the received message to the console.
    ```javascript
    // Creates an observable sequence of 5 integers, starting from 1
    const source = range(1, 5);

    // Create observer object
    const myObserver = {
      next: x => console.log('Observer got a next value: ' + x),
      error: err => console.error('Observer got an error: ' + err),
      complete: () => console.log('Observer got a complete notification'),
    };

    // Execute with the observer object and Prints out each item
    source.subscribe(myObserver);
    // => Observer got a next value: 1
    // => Observer got a next value: 2
    // => Observer got a next value: 3
    // => Observer got a next value: 4
    // => Observer got a next value: 5
    // => Observer got a complete notification
    ```


42. ### What is an observable?
    An Observable is a unique Object similar to a Promise that can help manage async code. Observables are not part of the JavaScript language so we need to rely on a popular Observable library called RxJS.
    The observables are created using new keyword.

    Let see the simple example of observable,
    ```javascript
    import { Observable } from 'rxjs';

    const observable = new Observable(observer => {
      setTimeout(() => {
        observer.next('Hello from a Observable!');
      }, 2000);
    });
    ```


43. ### What is an observer?
    Observer is an interface for a consumer of push-based notifications delivered by an Observable. It has below structure,

    ```javascript
    interface Observer<T> {
      closed?: boolean;
      next: (value: T) => void;
      error: (err: any) => void;
      complete: () => void;
    }
    ```
    A handler that implements the Observer interface for receiving observable notifications will be passed as a parameter for observable as below,

    ```javascript
    myObservable.subscribe(myObserver);
    ```
    **Note:** If you don't supply a handler for a notification type, the observer ignores notifications of that type.



44. ### What is the difference between promise and observable?
    Below are the list of differences between promise and observable:

       | Observable | Promise |
       |---- | --------- |
       | Declarative: Computation does not start until subscription, so they can run whenever you need the result | Executes immediately on creation|
       | Provides multiple values over time | Provides only one |
       | Subscribe method is used for error handling that facilitates centralized and predictable error handling | Push errors to the child promises |
       | Provides chaining and subscription to handle complex applications | Uses only `.then()` clause |



45. ### What is multicasting?
    Multi-casting is the practice of broadcasting to a list of multiple subscribers in a single execution.

    Let's demonstrate the multi-casting feature:
    ```javascript
    var source = Rx.Observable.from([1, 2, 3]);
    var subject = new Rx.Subject();
    var multicasted = source.multicast(subject);

    // These are, under the hood, `subject.subscribe({...})`:
    multicasted.subscribe({
      next: (v) => console.log('observerA: ' + v)
    });
    multicasted.subscribe({
      next: (v) => console.log('observerB: ' + v)
    });

    // This is, under the hood, `s
    ```


46. ### How do you perform error handling in observables?
    You can handle errors by specifying an **error callback** on the observer instead of relying on `try`/`catch`, which are ineffective in asynchronous environment.

    For example, you can define error callback as below,
    ```javascript
    myObservable.subscribe({
      next(num) { console.log('Next num: ' + num)},
      error(err) { console.log('Received an errror: ' + err)}
    });
    ```


49. ### What are observable creation functions?
    RxJS provides creation functions for the process of creating observables from promises, events, timers and Ajax requests. Let us explain each of them with an example:
    1. Create an observable from a promise
        ```javascript
        import { from } from 'rxjs'; // from function
        const data = from(fetch('/api/endpoint')); //Created from Promise
        data.subscribe({
         next(response) { console.log(response); },
         error(err) { console.error('Error: ' + err); },
         complete() { console.log('Completed'); }
        });
        ```
    2. Create an observable that creates an AJAX request
        ```javascript
        import { ajax } from 'rxjs/ajax'; // ajax function
        const apiData = ajax('/api/data'); // Created from AJAX request
        // Subscribe to create the request
        apiData.subscribe(res => console.log(res.status, res.response));
        ```
    3. Create an observable from a counter
        ```javascript
        import { interval } from 'rxjs'; // interval function
        const secondsCounter = interval(1000); // Created from Counter value
        secondsCounter.subscribe(n =>
          console.log(`Counter value: ${n}`));
        ```
    4. Create an observable from an event
        ```javascript
        import { fromEvent } from 'rxjs';
        const el = document.getElementById('custom-element');
        const mouseMoves = fromEvent(el, 'mousemove');
        const subscription = mouseMoves.subscribe((e: MouseEvent) => {
          console.log(`Coordnitaes of mouse pointer: ${e.clientX} * ${e.clientY}`);
          });
        ```


60. ### What are the various kinds of directives?
    There are mainly three kinds of directives:
    1. **Components** — These are directives with a template.
    2. **Structural directives** — These directives change the DOM layout by adding and removing DOM elements.
    3. **Attribute directives** — These directives change the appearance or behavior of an element, component, or another directive.


63. ### What is Angular Router?
    Angular Router is a mechanism in which navigation happens from one view to the next as users perform application tasks. It borrows the concepts or model of browser's application navigation. It enables developers to build Single Page Applications with multiple views and allow navigation between these views.

64. ### What is the purpose of base href tag?
    The routing application should add <base> element to the index.html as the first child in the <head> tag in order to indicate how to compose navigation URLs. If app folder is the application root then you can set the href value as below

    ```html
    <base href="/">
    ```

65. ### What are the router imports?
    The Angular Router which represents a particular component view for a given URL is not part of Angular Core. It is available in library named `@angular/router` to import required router components. For example, we import them in app module as below,

    ```javascript
    import { RouterModule, Routes } from '@angular/router';
    ```


66. ### What is router outlet?
    The RouterOutlet is a directive from the router library and it  acts as a placeholder that marks the spot in the template where the router should display the components for that outlet. Router outlet is used like a component,

    ```html
    <router-outlet></router-outlet>
    <!-- Routed components go here -->
    ```


67. ### What are router links?
    The RouterLink is a directive on the anchor tags give the router control over those elements. Since the navigation paths are fixed, you can assign string values to router-link directive as below,

    ```html
    <h1>Angular Router</h1>
    <nav>
      <a routerLink="/todosList" >List of todos</a>
      <a routerLink="/completed" >Completed todos</a>
    </nav>
    <router-outlet></router-outlet>
    ```


68. ### What are active router links?
    RouterLinkActive is a directive that toggles css classes for active RouterLink bindings based on the current RouterState. i.e, The Router will add CSS classes when this link is active and remove when the link is inactive. For example, you can add them to RouterLinks as below.

    ```html
    <h1>Angular Router</h1>
    <nav>
      <a routerLink="/todosList" routerLinkActive="active">List of todos</a>
      <a routerLink="/completed" routerLinkActive="active">Completed todos</a>
    </nav>
    <router-outlet></router-outlet>
    ```


69. ### What is router state?
    RouterState is a tree of activated routes. Every node in this tree knows about the "consumed" URL segments, the extracted parameters, and the resolved data. You can access the current RouterState from anywhere in the application using the `Router service` and the `routerState` property.

    ```javascript
    @Component({templateUrl:'template.html'})
    class MyComponent {
      constructor(router: Router) {
        const state: RouterState = router.routerState;
        const root: ActivatedRoute = state.root;
        const child = root.firstChild;
        const id: Observable<string> = child.params.map(p => p.id);
        //...
      }
    }
    ```


70. ### What are router events?
    During each navigation, the Router emits navigation events through the Router.events property allowing you to track the lifecycle of the route.

    The sequence of router events is as below,

    1. NavigationStart,
    2. RouteConfigLoadStart,
    3. RouteConfigLoadEnd,
    4. RoutesRecognized,
    5. GuardsCheckStart,
    6. ChildActivationStart,
    7. ActivationStart,
    8. GuardsCheckEnd,
    9. ResolveStart,
    10. ResolveEnd,
    11. ActivationEnd
    12. ChildActivationEnd
    13. NavigationEnd,
    14. NavigationCancel,
    15. NavigationError
    16. Scroll


71. ### What is activated route?
    ActivatedRoute contains the information about a route associated with a component loaded in an outlet. It can also be used to traverse the router state tree. The ActivatedRoute will be injected as a router service to access the information. In the below example, you can access route path and parameters,

    ```javascript
    @Component({...})
    class MyComponent {
      constructor(route: ActivatedRoute) {
        const id: Observable<string> = route.params.pipe(map(p => p.id));
        const url: Observable<string> = route.url.pipe(map(segments => segments.join('')));
        // route.data includes both `data` and `resolve`
        const user = route.data.pipe(map(d => d.user));
      }
    }
    ```


72. ### How do you define routes?
     A router must be configured with a list of route definitions. You configures the router with routes via the `RouterModule.forRoot()` method, and adds the result to the AppModule's `imports` array.

    ```javascript
     const appRoutes: Routes = [
      { path: 'todo/:id',      component: TodoDetailComponent },
      {
        path: 'todos',
        component: TodosListComponent,
        data: { title: 'Todos List' }
      },
      { path: '',
        redirectTo: '/todos',
        pathMatch: 'full'
      },
      { path: '**', component: PageNotFoundComponent }
    ];

    @NgModule({
      imports: [
        RouterModule.forRoot(
          appRoutes,
          { enableTracing: true } // <-- debugging purposes only
        )
        // other imports here
      ],
      ...
    })
    export class AppModule { }
    ```

73. ### What is the purpose of Wildcard route?
    If the URL doesn't match any predefined routes then it causes the router to throw an error and crash the app. In this case, you can use wildcard route. A wildcard route has a path consisting of two asterisks to match every URL.

    For example, you can define PageNotFoundComponent for wildcard route as below
    ```javascript
    { path: '**', component: PageNotFoundComponent }
    ```


74. ### Do I need a Routing Module always?
    No, the Routing Module is a design choice. You can skip routing Module (for example, AppRoutingModule) when the configuration is simple and merge the routing configuration directly into the companion module (for example, AppModule). But it is recommended when the configuration is complex and includes specialized guard and resolver services.

75. ### What is Angular Universal?
    Angular Universal is a server-side rendering module for Angular applications in various scenarios. This is a community driven project and available under @angular/platform-server package. Recently Angular Universal is integrated with Angular CLI.


76. ### What are different types of compilation in Angular?
    Angular offers two ways to compile your application,
    1. Just-in-Time (JIT)
    2. Ahead-of-Time (AOT)


77. ### What is JIT?
    Just-in-Time (JIT) is a type of compilation that compiles your app in the browser at runtime. JIT compilation was the default until Angular 8, now default is AOT. When you run the ng build (build only) or ng serve (build and serve locally) CLI commands, the type of compilation (JIT or AOT) depends on the value of the aot property in your build configuration specified in angular.json. By default, aot is set to true.


78. ### What is AOT?
    Ahead-of-Time (AOT) is a type of compilation that compiles your app at build time. This is the default starting in Angular 9. When you run the ng build (build only) or ng serve (build and serve locally) CLI commands, the type of compilation (JIT or AOT) depends on the value of the aot property in your build configuration specified in angular.json. By default, aot is set to true.
    
    ```cmd
    ng build
    ng serve
    ```


79. ### Why do we need compilation process?
    The Angular components and templates cannot be understood by the browser directly. Due to that Angular applications require a compilation process before they can run in a browser. For example, In AOT compilation, both Angular HTML and TypeScript code converted into efficient JavaScript code during the build phase before browser runs it.


80. ### What are the advantages with AOT?
    Below are the list of AOT benefits,

    1. **Faster rendering:** The browser downloads a pre-compiled version of the application. So it can render the application immediately without compiling the app.
    2. **Fewer asynchronous requests:** It inlines external HTML templates and CSS style sheets within the application javascript which eliminates separate ajax requests.
    3. **Smaller Angular framework download size:** Doesn't require downloading the Angular compiler. Hence it dramatically reduces the application payload.
    4. **Detect template errors earlier:** Detects and reports template binding errors during the build step itself
    5. **Better security:** It compiles HTML templates and components into JavaScript.  So there won't be any injection attacks.


81. ### What are the ways to control AOT compilation?
    You can control your app compilation in two ways,
    1. By providing template compiler options in the `tsconfig.json` file
    2. By configuring Angular metadata with decorators


82. ### What are the restrictions of metadata?
    In Angular, You must write metadata with the following general constraints,
    1. Write expression syntax with in the supported range of javascript features
    2. The compiler can only reference symbols which are exported
    3. Only call the functions supported by the compiler
    4. Decorated and data-bound class members must be public.


83. ### What are the three phases of AOT?
    The AOT compiler works in three phases,
    1. **Code Analysis:** The compiler records a representation of the source
    2. **Code generation:** It handles the interpretation as well as places restrictions on what it interprets.
    3. **Validation:** In this phase, the Angular template compiler uses the TypeScript compiler to validate the binding expressions in templates.


84. ### Can I use arrow functions in AOT?
    No, Arrow functions or lambda functions can’t be used to assign values to the decorator properties. For example, the following snippet is invalid:

    ```javascript
    @Component({
      providers: [{
        provide: MyService, useFactory: () => getService()
      }]
    })
    ```

    To fix this, it has to be changed as following exported function:

    ```javascript
    function getService(){
      return new MyService();
    }

    @Component({
      providers: [{
        provide: MyService, useFactory: getService
      }]
    })
    ```

    If you still use arrow function, it generates an error node in place of the function. When the compiler later interprets this node, it reports an error to turn the arrow function into an exported function.
    **Note:** From Angular5 onwards, the compiler automatically performs this rewriting while emitting the .js file.



85. ### What is the purpose of metadata json files?
    The metadata.json file can be treated as a diagram of the overall structure of a decorator's metadata, represented as an abstract syntax tree(AST). During the analysis phase, the AOT collector scan the metadata recorded in the Angular decorators and outputs metadata information in .metadata.json files, one per .d.ts file.

86. ### Can I use any javascript feature for expression syntax in AOT?
    No, the AOT collector understands a subset  of (or limited) JavaScript features. If an expression uses unsupported syntax, the collector writes an error node to the .metadata.json file. Later point of time, the compiler reports an error if it needs that piece of metadata to generate the application code.


87. ### What is folding?
    The compiler can only resolve references to exported symbols in the metadata. Where as some of the non-exported members are folded while generating the code. i.e Folding is a process in which the collector evaluate an expression during collection and record the result in the .metadata.json instead of the original expression.
    For example, the compiler couldn't refer selector reference because it is not exported

    ```javascript
    let selector = 'app-root';
    @Component({
      selector: selector
    })
    ```
    Will be folded into inline selector

    ```javascript
    @Component({
          selector: 'app-root'
        })
    ```
    Remember that the compiler can’t fold everything. For example, spread operator on arrays, objects created using new keywords and function calls.


88. ### What are macros?
    The AOT compiler supports macros in the form of functions or static methods that return an expression in a `single return expression`.
    For example, let us take a below macro function,

    ```javascript
    export function wrapInArray<T>(value: T): T[] {
      return [value];
    }
    ```

    You can use it inside metadata as an expression,

    ```javascript
    @NgModule({
      declarations: wrapInArray(TypicalComponent)
    })
    export class TypicalModule {}
    ```

    The compiler treats the macro expression as it written directly

    ```javascript
    @NgModule({
      declarations: [TypicalComponent]
    })
    export class TypicalModule {}
    ```

91. ### How do you provide configuration inheritance?
    Angular Compiler supports configuration inheritance through extends in the tsconfig.json on angularCompilerOptions. i.e, The configuration from the base file(for example, tsconfig.base.json) are loaded first, then overridden by those in the inheriting config file.

    ```javascript
    {
      "extends": "../tsconfig.base.json",
      "compilerOptions": {
        "experimentalDecorators": true,
        ...
      },
      "angularCompilerOptions": {
        "fullTemplateTypeCheck": true,
        "preserveWhitespaces": true,
        ...
      }
    }
    ```

106. ### What is transition function?
     The animation transition function is used to specify the changes that occur between one state and another over a period of time. It accepts two arguments: the first argument accepts an expression that defines the direction between two transition states, and the second argument accepts an animate() function.

     Let's take an example state transition from open to closed with an half second transition between states.

     ```javascript
     transition('open => closed', [
       animate('500ms')
     ]),
     ```


107. ### How to inject the dynamic script in angular?
     Using DomSanitizer we can inject the dynamic Html,Style,Script,Url.

     ```
     import { Component, OnInit } from '@angular/core';
     import { DomSanitizer } from '@angular/platform-browser';
     @Component({
        selector: 'my-app',
        template: `
            <div [innerHtml]="htmlSnippet"></div>
        `,
     })
     export class App {
            constructor(protected sanitizer: DomSanitizer) {}
            htmlSnippet: string = this.sanitizer.bypassSecurityTrustScript("<script>safeCode()</script>");
        }
     ```

 111. ### What is Angular Ivy?
      Angular Ivy is a new rendering engine for Angular. You can choose to opt in a preview version of Ivy from Angular version 8.

      1. You can enable ivy in a new project by using the --enable-ivy flag with the ng new command

          ```bash
          ng new ivy-demo-app --enable-ivy
          ```
      2. You can add it to an existing project by adding `enableIvy` option in the `angularCompilerOptions` in your project's `tsconfig.app.json`.

          ```javascript
          {
            "compilerOptions": { ... },
            "angularCompilerOptions": {
              "enableIvy": true
            }
          }
          ```


 112. ### What are the features included in ivy preview?
      You can expect below features with Ivy preview,

      1. Generated code that is easier to read and debug at runtime
      2. Faster re-build time
      3. Improved payload size
      4. Improved template type checking


 113. ### Can I use AOT compilation with Ivy?
      Yes, it is a recommended configuration. Also, AOT compilation with Ivy is faster. So you need set the default build options(with in angular.json) for your project to always use AOT compilation.

      ```javascript
      {
        "projects": {
          "my-project": {
            "architect": {
              "build": {
                "options": {
                  ...
                  "aot": true,
                }
              }
            }
          }
        }
      }
      ```


 125. ### What are the class decorators in Angular?
      A class decorator is a decorator that appears immediately before a class definition, which declares the class to be of the given type, and provides metadata suitable to the type

      The following list of decorators comes under class decorators,

      1. @Component()
      2. @Directive()
      3. @Pipe()
      4. @Injectable()
      5. @NgModule()


 126. ### What are class field decorators?
      The class field decorators are the statements declared immediately before a field in a class definition that defines the type of that field. Some of the examples are: @input and @output,

      ```javascript
      @Input() myProperty;
      @Output() myEvent = new EventEmitter();
      ```

 127. ### What is declarable in Angular?
      Declarable is a class type that you can add to the declarations list of an NgModule. The class types such as components, directives, and pipes comes can be declared in the module. The structure of declarations would be,

      ```javascript
      declarations: [
        YourComponent,
        YourPipe,
        YourDirective
      ],
      ```

131. ### what is an rxjs subject in Angular
     An RxJS Subject is a special type of Observable that allows values to be multicasted to many Observers. While plain Observables are unicast (each subscribed Observer owns an independent execution of the Observable), Subjects are multicast.
      
     A Subject is like an Observable, but can multicast to many Observers. Subjects are like EventEmitters: they maintain a registry of many listeners.

     ``` typescript
      import { Subject } from 'rxjs';
 
        const subject = new Subject<number>();

        subject.subscribe({
          next: (v) => console.log(`observerA: ${v}`)
        });
        subject.subscribe({
          next: (v) => console.log(`observerB: ${v}`)
        });

        subject.next(1);
        subject.next(2);
     ```


137. ### What happens if I import the same module twice?
     If multiple modules imports the same module then angular evaluates it only once (When it encounters the module first time). It follows this condition even the module appears at any level in a hierarchy of imported NgModules.



140. ### How do you pass headers for HTTP client?
     You can directly pass object map for http client or create HttpHeaders class to supply the headers.

     ```javascript
     constructor(private _http: HttpClient) {}
     this._http.get('someUrl',{
        headers: {'header1':'value1','header2':'value2'}
     });

     (or)
     let headers = new HttpHeaders().set('header1', headerValue1); // create header object
     headers = headers.append('header2', headerValue2); // add a new header, creating a new object
     headers = headers.append('header3', headerValue3); // add another header

     let params = new HttpParams().set('param1', value1); // create params object
     params = params.append('param2', value2); // add a new param, creating a new object
     params = params.append('param3', value3); // add another param

     return this._http.get<any[]>('someUrl', { headers: headers, params: params })
     ```


142. ### Is Angular supports dynamic imports?
     Yes, Angular 8 supports dynamic imports in router configuration. i.e, You can use the import statement for lazy loading the module using `loadChildren` method and it will be understood by the IDEs(VSCode and WebStorm), webpack, etc.
     Previously, you have been written as below to lazily load the feature module. By mistake, if you have typo in the module name it still accepts the string and throws an error during build time.
     ```javascript
     {path: ‘user’, loadChildren: ‘./users/user.module#UserModulee’},
     ```
     This problem is resolved by using dynamic imports and IDEs are able to find it during compile time itself.
     ```javascript
     {path: ‘user’, loadChildren: () => import(‘./users/user.module’).then(m => m.UserModule)};
     ```


143. ### What is lazy loading?
     Lazy loading is one of the most useful concepts of Angular Routing. It helps us to download the web pages in chunks instead of downloading everything in a big bundle. It is used for lazy loading by asynchronously loading the feature module for routing whenever required using the property `loadChildren`. Let's load both `Customer` and `Order` feature modules lazily as below,
     ```javascript
     const routes: Routes = [
       {
         path: 'customers',
         loadChildren: () => import('./customers/customers.module').then(module => module.CustomersModule)
       },
       {
         path: 'orders',
         loadChildren: () => import('./orders/orders.module').then(module => module.OrdersModule)
       },
       {
         path: '',
         redirectTo: '',
         pathMatch: 'full'
       }
     ];
     ```


145. ### How do you upgrade angular version?
     The Angular upgrade is quite easier using Angular CLI `ng update` command as mentioned below. For example, if you upgrade from Angular 7 to 8 then your lazy loaded route imports will be migrated to the new import syntax automatically.
     ```bash
     $ ng update @angular/cli @angular/core
     ```


146. ### What is Angular Material?
     Angular Material is a collection of Material Design components for Angular framework following the Material Design spec. You can apply Material Design very easily using Angular Material. The installation can be done through npm or yarn,
     ```bash
     npm install --save @angular/material @angular/cdk @angular/animations
     (OR)
     yarn add @angular/material @angular/cdk @angular/animations
     ```
     It supports the most recent two versions of all major browsers. The latest version of Angular material is 8.1.1


152. ### What are the differences of various versions of Angular?
     There are different versions of Angular framework. Let's see the features of all the various versions,

     1. **Angular 1:**
        * Angular 1 (AngularJS) is the first angular framework released in the year 2010.
        * AngularJS is not built for mobile devices.
        * It is based on controllers with MVC architecture.
     2. **Angular 2:**
        * Angular 2 was released in the year 2016. Angular 2 is a complete rewrite of Angular1 version.
        * The performance issues that Angular 1 version had has been addressed in Angular 2 version.
        * Angular 2 is built from scratch for mobile devices unlike Angular 1 version.
        * Angular 2 is components based.
     3. **Angular 3:**
        * The following are the different package versions in Angular 2:
          * @angular/core v2.3.0
          * @angular/compiler v2.3.0
          * @angular/http v2.3.0
          * @angular/router v3.3.0
        * The router package is already versioned 3 so to avoid confusion switched to Angular 4 version and skipped 3 version.
     4. **Angular 4:**
        * The compiler generated code file size in AOT mode is very much reduced.
        * With Angular 4 the production bundles size is reduced by hundreds of KB’s.
        * Animation features are removed from angular/core and formed as a separate package.
        * Supports Typescript 2.1 and 2.2.
        * Angular Universal
        * New HttpClient
     5. **Angular 5:**
        * Angular 5 makes angular faster. It improved the loading time and execution time.
        * Shipped with new build optimizer.
        * Supports Typescript 2.5.
        * Service Worker
     6. **Angular 6:**
        * It is released in May 2018.
        * Includes Angular Command Line Interface (CLI), Component Development KIT (CDK), Angular Material Package, Angular Elements.
        * Service Worker bug fixes.
        * i18n
        * Experimental mode for Ivy.
        * RxJS 6.0
        * Tree Shaking
     7. **Angular 7:**
        * It is released in October 2018.
        * TypeScript 3.1
        * RxJS 6.3
        * New Angular CLI
        * CLI Prompts capability provide an ability to ask questions to the user before they run. It is like interactive dialog between the user and the CLI
        * With the improved CLI Prompts capability, it helps developers to make the decision. New ng commands ask users for routing and CSS styles types(SCSS) and ng add @angular/material asks for themes and gestures or animations.
      8. **Angular 8:**
         * It is released in May 2019.
         * TypeScript 3.4
      9. **Angular 9:**
         * It is released in February 2020.
         * TypeScript 3.7
         * Ivy enabled by default
      10. **Angular 10:**
            * It is released in June 2020.
            * TypeScript 3.9 
            * TSlib 2.0


156. ### How do you find angular CLI version?
     Angular CLI provides it's installed version using below different ways using ng command,

     ```bash
     ng v
     ng version
     ng -v
     ng --version
     ```
     and the output would be as below,

     ```bash
     Angular CLI: 1.6.3
     Node: 8.11.3
     OS: darwin x64
     Angular:
     ...
     ```


162. ### What is Angular security model for preventing XSS attacks?
     Angular treats all values as untrusted by default. i.e, Angular sanitizes and escapes untrusted values When a value is inserted into the DOM from a template, via property, attribute, style, class binding, or interpolation.


164. ### What are the various security contexts in Angular?
     Angular defines the following security contexts for sanitization,

     1. **HTML:** It is used when interpreting a value as HTML such as binding to innerHtml.
     2. **Style:** It is used when binding CSS into the style property.
     3. **URL:** It is used for URL properties such as `<a href>`.
     4. **Resource URL:** It is a URL that will be loaded and executed as code such as `<script src>`.

165. ### What is Sanitization? Is angular supports it?
     **Sanitization** is the inspection of an untrusted value, turning it into a value that's safe to insert into the DOM. Yes, Angular suppports sanitization. It sanitizes untrusted values for HTML, styles, and URLs but sanitizing resource URLs isn't possible because they contain arbitrary code.

166. ### What is the purpose of innerHTML?
     The innerHtml is a property of HTML-Elements, which allows you to set it's html-content programmatically. Let's display the below html code snippet in a `<div>` tag as below using innerHTML binding,

     ```html
     <div [innerHTML]="htmlSnippet"></div>
     ```
     and define the htmlSnippet property from any component
     ```javascript
     export class myComponent {
       htmlSnippet: string = '<b>Hello World</b>, Angular';
     }
     ```
     Unfortunately this property could cause Cross Site Scripting (XSS) security bugs when improperly handled.


167. ### What is the difference between interpolated content and innerHTML?
     The main difference between interpolated and innerHTML code is the behavior of code interpreted. Interpolated content is always escaped i.e,  HTML isn't interpreted and the browser displays angle brackets in the element's text content. Where as in innerHTML binding, the content is interpreted i.e, the browser will convert < and > characters as HTMLEntities. For example, the usage in template would be as below,

     ```html
     <p>Interpolated value:</p>
     <div >{{htmlSnippet}}</div>
     <p>Binding of innerHTML:</p>
     <div [innerHTML]="htmlSnippet"></div>
     ```
     and the property defined in a component.

     ```javascript
     export class InnerHtmlBindingComponent {
       htmlSnippet = 'Template <script>alert("XSS Attack")</script> <b>Code attached</b>';
     }
     ```
     Even though innerHTML binding create a chance of XSS attack, Angular recognizes the value as unsafe and automatically sanitizes it.



173. ### What are Http Interceptors?
     Http Interceptors are part of @angular/common/http, which inspect and transform HTTP requests from your application to the server and vice-versa on HTTP responses. These interceptors can perform a variety of implicit tasks, from authentication to logging.

     The syntax of HttpInterceptor interface looks like as below,

     ```javascript
     interface HttpInterceptor {
       intercept(req: HttpRequest<any>, next: HttpHandler): Observable<HttpEvent<any>>
     }
     ```
     You can use interceptors by declaring a service class that implements the intercept() method of the HttpInterceptor interface.

     ```javascript
     @Injectable()
     export class MyInterceptor implements HttpInterceptor {
         constructor() {}
         intercept(req: HttpRequest<any>, next: HttpHandler): Observable<HttpEvent<any>> {
             ...
         }
     }
     ```
     After that you can use it in your module,

     ```javascript
     @NgModule({
         ...
         providers: [
             {
                 provide: HTTP_INTERCEPTORS,
                 useClass: MyInterceptor,
                 multi: true
             }
         ]
         ...
     })
     export class AppModule {}
     ```

174. ### What are the applications of HTTP interceptors?
     The HTTP Interceptors can be used for different variety of tasks,

     1. Authentication
     2. Logging
     3. Caching
     4. Fake backend
     5. URL transformation
     6. Modifying headers

176. ### How can I use interceptor for an entire application?
     You can use same instance of `HttpInterceptors` for the entire app by importing the `HttpClientModule` only in your AppModule, and add the interceptors to the root application injector.
     For example, let's define a class that is injectable in root application.
      ```javascript
      @Injectable()
      export class MyInterceptor implements HttpInterceptor {
        intercept(
          req: HttpRequest<any>,
          next: HttpHandler
        ): Observable<HttpEvent<any>> {

          return next.handle(req).do(event => {
            if (event instanceof HttpResponse) {
                 // Code goes here
            }
          });

        }
      }
      ```
     After that import HttpClientModule in AppModule
     ```javascript
     @NgModule({
       declarations: [AppComponent],
       imports: [BrowserModule, HttpClientModule],
       providers: [
         { provide: HTTP_INTERCEPTORS, useClass: MyInterceptor, multi: true }
       ],
       bootstrap: [AppComponent]
     })
     export class AppModule {}
     ```

190. ### What is AOT compiler?
     The AOT compiler is part of a build process that produces a small, fast, ready-to-run application package, typically for production. It converts your Angular HTML and TypeScript code into efficient JavaScript code during the build phase before the browser downloads and runs that code.

193. ### What is protractor?
     Protractor is an end-to-end test framework for Angular and AngularJS applications. It runs tests against your application running in a real browser, interacting with it as a user would.
     ```javascript
     npm install -g protractor
     ```

196. ### How do you use jquery in Angular?
     You can use jquery in Angular using 3 simple steps,
     1. **Install the dependency:** At first, install the jquery dependency using npm
         ```cmd
            npm install --save jquery
         ```
     2. **Add the jquery script:** In Angular-CLI project, add the relative path to jquery in the angular.json file.
         ```javascript
         "scripts": [
            "node_modules/jquery/dist/jquery.min.js"
         ]
         ```
     3. **Start using jquery:** Define the element in template. Whereas declare the jquery variable and apply CSS classes on the element.
         ```html
         <div id="elementId">
           <h1>JQuery integration</h1>
         </div>
         ```
         ```javascript
         import {Component, OnInit} from '@angular/core';

         declare var $: any; // (or) import * as $ from 'jquery';

         @Component({
           selector: 'app-root',
           templateUrl: './app.component.html',
           styleUrls: ['./app.component.css']
         })
         export class AppComponent implements OnInit {
           ngOnInit(): void {
             $(document).ready(() => {
               $('#elementId').css({'text-color': 'blue', 'font-size': '150%'});
             });
           }
         }
         ```

197. ### What is the reason for No provider for HTTP exception?
     This exception is due to missing HttpClientModule in your module. You just need to import in module as below,
     ```javascript
     import { HttpClientModule } from '@angular/common/http';

     @NgModule({
       imports: [
         BrowserModule,
         HttpClientModule,
       ],
       declarations: [ AppComponent ],
       bootstrap:    [ AppComponent ]
     })
     export class AppModule { }
     ```

198. ### What is router state?
     The RouteState is an interface which represents the state of the router as a tree of activated routes.
     ```javascript
     interface RouterState extends Tree {
       snapshot: RouterStateSnapshot
       toString(): string
     }
     ```
     You can access the current RouterState from anywhere in the Angular app using the Router service and the routerState property.


199. ### How can I use SASS in angular project?
     When you are creating your project with angular cli, you can use `ng new`command. It generates all your components with predefined sass files.
     ```javascript
     ng new My_New_Project --style=sass
     ```
     But if you are changing your existing style in your project then use `ng set` command,
     ```javascript
     ng set defaults.styleExt scss
     ```


200. ### What is the purpose of hidden property?
     The hidden property is used  to show or hide the associated DOM element, based on an expression. It can be compared close to `ng-show` directive in AngularJS. Let's say you want to show user name based on the availability of user using `hidden` property.
     ```javascript
     <div [hidden]="!user.name">
       My name is: {{user.name}}
     </div>
     ```

201. ### What is the difference between ngIf and hidden property?
     The main difference is that *ngIf will remove the element from the DOM, while [hidden] actually plays with the CSS style by setting `display:none`. Generally it is expensive to add and remove stuff from the DOM for frequent actions.

202. ### What is slice pipe?
     The slice pipe is used to create a new Array or String containing a subset (slice) of the elements. The syntax looks like as below,
     ```javascript
     {{ value_expression | slice : start [ : end ] }}
     ```
     For example, you can provide 'hello' list based on a greeting array,
     ```javascript
     @Component({
       selector: 'list-pipe',
       template: `<ul>
         <li *ngFor="let i of greeting | slice:0:5">{{i}}</li>
       </ul>`
     })
     export class PipeListComponent {
       greeting: string[] = ['h', 'e', 'l', 'l', 'o', 'm','o', 'r', 'n', 'i', 'n', 'g'];
     }
     ```


204. ### What is the purpose of ngFor trackBy?
     The main purpose of using *ngFor with trackBy option is performance optimization. Normally if you use NgFor with large data sets, a small change to one item by removing or adding an item, can trigger a cascade of DOM manipulations. In this case, Angular sees only a fresh list of new object references and to replace the old DOM elements with all new DOM elements. You can help Angular to track which items added or removed by providing a `trackBy` function which takes the index and the current item as arguments and needs to return the unique identifier for this item.

     For example, lets set trackBy to the trackByTodos() method
     ```javascript
     <div *ngFor="let todo of todos; trackBy: trackByTodos">
       ({{todo.id}}) {{todo.name}}
     </div>
     ```
     and define the trackByTodos method,
     ```javascript
     trackByTodos(index: number, item: Todo): number { return todo.id; }
     ```

205. ### What is the purpose of ngSwitch directive?
     **NgSwitch** directive is similar to JavaScript switch statement which displays one element from among several possible elements, based on a switch condition. In this case only the selected element placed into the DOM. It has been used along with `NgSwitch`, `NgSwitchCase` and `NgSwitchDefault` directives.

     For example, let's display the browser details based on selected browser using ngSwitch directive.
     ```javascript
     <div [ngSwitch]="currentBrowser.name">
       <chrome-browser    *ngSwitchCase="'chrome'"    [item]="currentBrowser"></chrome-browser>
       <firefox-browser   *ngSwitchCase="'firefox'"     [item]="currentBrowser"></firefox-browser>
       <opera-browser     *ngSwitchCase="'opera'"  [item]="currentBrowser"></opera-browser>
       <safari-browser     *ngSwitchCase="'safari'"   [item]="currentBrowser"></safari-browser>
       <ie-browser  *ngSwitchDefault           [item]="currentItem"></ie-browser>
     </div>
     ```


212. ### What is the precedence between pipe and ternary operators?
     The pipe operator has a higher precedence than the ternary operator (?:). For example, the expression `first ? second : third | fourth` is parsed as `first ? second : (third | fourth)`.



214. ### What is a bootstrapped component?
     A bootstrapped component is an entry component that Angular loads into the DOM during the bootstrap process or application launch time. Generally, this bootstrapped or root component is named as `AppComponent` in your root module using `bootstrap` property as below.
     ```js
     @NgModule({
       declarations: [
         AppComponent
       ],
       imports: [
         BrowserModule,
         FormsModule,
         HttpClientModule,
         AppRoutingModule
       ],
       providers: [],
       bootstrap: [AppComponent] // bootstrapped entry component need to be declared here
     })
     ```

223. ### How does angular finds components, directives and pipes?
     The Angular compiler finds a component or directive in a template when it can match the selector of that component or directive in that template. Whereas it finds a pipe if the pipe's name appears within the pipe syntax of the template HTML.


238. ### What is a shared module?
     The Shared Module is the module in which you put commonly used directives, pipes, and components into one module that is shared(import it) throughout the application.

     For example, the below shared module imports CommonModule, FormsModule for common directives and components, pipes and directives based on the need,
     ```js
     import { CommonModule } from '@angular/common';
     import { NgModule } from '@angular/core';
     import { FormsModule } from '@angular/forms';
     import { UserComponent } from './user.component';
     import { NewUserDirective } from './new-user.directive';
     import { OrdersPipe } from './orders.pipe';

     @NgModule({
      imports:      [ CommonModule ],
      declarations: [ UserComponent, NewUserDirective, OrdersPipe ],
      exports:      [ UserComponent, NewUserDirective, OrdersPipe,
                      CommonModule, FormsModule ]
     })
     export class SharedModule { }
     ```


256. ### What are reactive forms?
     Reactive forms is a model-driven approach for creating forms in a reactive style(form inputs changes over time). These are built around observable streams, where form inputs and values are provided as streams of input values. Let's follow the below steps to create reactive forms,
     1. Register the reactive forms module which declares reactive-form directives in your app
         ```js
         import { ReactiveFormsModule } from '@angular/forms';

         @NgModule({
           imports: [
             // other imports ...
             ReactiveFormsModule
           ],
         })
         export class AppModule { }
         ```
     2. Create a new FormControl instance and save it in the component.
         ```js
         import { Component } from '@angular/core';
         import { FormControl } from '@angular/forms';

         @Component({
           selector: 'user-profile',
           styleUrls: ['./user-profile.component.css']
         })
         export class UserProfileComponent {
           userName = new FormControl('');
         }
         ```
     3. Register the FormControl in the template.
         ```js
         <label>
           User name:
           <input type="text" [formControl]="userName">
         </label>
         ```
     Finally, the component with reactive form control appears as below,
     ```js
     import { Component } from '@angular/core';
     import { FormControl } from '@angular/forms';
	
     @Component({
       selector: 'user-profile',
       styleUrls: ['./user-profile.component.css'],
       template: `
         <label>
           User name:
           <input type="text" [formControl]="userName">
         </label>
       `
     })
     export class UserProfileComponent {
       userName = new FormControl('');
     }
     ```


257. ### What are dynamic forms?
     Dynamic forms is a pattern in which we build a form dynamically based on metadata that describes a business object model. You can create them based on reactive form API.

258. ### What are template driven forms?
     Template driven forms are model-driven forms where you write the logic, validations, controls etc, in the template part of the code using directives. They are suitable for simple scenarios and uses two-way binding with [(ngModel)] syntax.
     For example, you can create register form easily by following the below simple steps,

     1. Import the FormsModule into the Application module's imports array
         ```js
            import { BrowserModule } from '@angular/platform-browser';
            import { NgModule } from '@angular/core';
            import {FormsModule} from '@angular/forms'
            import { RegisterComponent } from './app.component';
            @NgModule({
              declarations: [
                RegisterComponent,
              ],
              imports: [
                BrowserModule,
                FormsModule
              ],
              providers: [],
              bootstrap: [RegisterComponent]
            })
            export class AppModule { }
         ```
     2. Bind the form from template to the component using ngModel syntax
         ```html
         <input type="text" class="form-control" id="name"
           required
           [(ngModel)]="model.name" name="name">
         ```
     3.  Attach NgForm directive to the <form> tag in order to create FormControl instances and register them
         ```js
         <form #registerForm="ngForm">
         ```
     4. Apply the validation message for form controls
         ```html
         <label for="name">Name</label>
         <input type="text" class="form-control" id="name"
                required
                [(ngModel)]="model.name" name="name"
                #name="ngModel">
         <div [hidden]="name.valid || name.pristine"
              class="alert alert-danger">
           Please enter your name
         </div>
         ```
     5. Let's submit the form with ngSubmit directive and add type="submit" button at the bottom of the form to trigger form submit.
         ```html
         <form (ngSubmit)="onSubmit()" #heroForm="ngForm">
         // Form goes here
         <button type="submit" class="btn btn-success" [disabled]="!registerForm.form.valid">Submit</button>
         ```
     Finally, the completed template-driven registration form will be appeared as follow.
     ```html
     <div class="container">
       <h1>Registration Form</h1>
       <form (ngSubmit)="onSubmit()" #registerForm="ngForm">
         <div class="form-group">
           <label for="name">Name</label>
             <input type="text" class="form-control" id="name"
                    required
                    [(ngModel)]="model.name" name="name"
                    #name="ngModel">
             <div [hidden]="name.valid || name.pristine"
                  class="alert alert-danger">
               Please enter your name
             </div>
         </div>
         <button type="submit" class="btn btn-success" [disabled]="!registerForm.form.valid">Submit</button>
         </form>
     </div>
     ```

259. ### What are the differences between reactive forms and template driven forms?
     Below are the main differences between reactive forms and template driven forms

     | Feature | Reactive | Template-Driven |
     |---- |---- | --------- |
     | Form model setup | Created(FormControl instance) in component explicitly | Created by directives  |
     | Data updates | Synchronous | Asynchronous |
     | Form custom validation | Defined as Functions | Defined as Directives |
     | Testing | No interaction with change detection cycle | Need knowledge of the change detection process |
     | Mutability | Immutable(by always returning new value for FormControl instance) | Mutable(Property always modified to new value) |
     | Scalability | More scalable using low-level APIs | Less scalable using due to abstraction on APIs|


262. ### What is the purpose of FormBuilder?
     FormBuilder is used as syntactic sugar for easily creating instances of a FormControl, FormGroup, or FormArray. This is helpful to reduce the amount of boilerplate needed to build complex reactive forms. It is available as an injectable helper class of the `@angular/forms` package.

     For example, the user profile component creation becomes easier as shown here.
     ```js
     export class UserProfileComponent {
       profileForm = this.formBuilder.group({
         firstName: [''],
         lastName: [''],
         address: this.formBuilder.group({
           street: [''],
           city: [''],
           state: [''],
           zip: ['']
         }),
       });
       constructor(private formBuilder: FormBuilder) { }
       }
     ```


265. ### How do you reset the form?
     In a model-driven form, you can reset the form just by calling the function `reset()` on our form model.
     For example, you can reset the form model on submission as follows,
     ```js
     onSubmit() {
       if (this.myform.valid) {
         console.log("Form is submitted");
         // Perform business logic here
         this.myform.reset();
       }
     }
     ```
     Now, your form model resets the form back to its original pristine state.


267. ### Can you give an example of built-in validators?
     In reactive forms, you can use built-in validator like `required` and `minlength` on your input form controls. For example, the registration form can have these validators on name input field
     ```js
     this.registrationForm = new FormGroup({
         'name': new FormControl(this.hero.name, [
           Validators.required,
           Validators.minLength(4),
         ])
       });
     ```
     Whereas in template-driven forms, both `required` and `minlength` validators available as attributes.


269. ### How to set ngFor and ngIf on the same element?
     Sometimes you may need to both ngFor and ngIf on the same element but unfortunately you are going to encounter below template error.
     ```cmd
      Template parse errors: Can't have multiple template bindings on one element.
     ```
      In this case, You need to use either ng-container or ng-template.
      Let's say if you try to loop over the items only when the items are available, the below code throws an error in the browser
      ```html
      <ul *ngIf="items" *ngFor="let item of items">
        <li></li>
      </ul>
      ```
      and it can be fixed by
      ```html
      <ng-container *ngIf="items">
        <ul *ngFor="let item of items">
          <li></li>
        </ul>
      </ng-container>
      ```

