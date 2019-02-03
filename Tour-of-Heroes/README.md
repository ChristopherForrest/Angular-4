

## Achievements 

* Created the initial application structure using the Angular CLI.
* Learned that Angular components display data.
* Used the double curly braces of interpolation to display the app title.
* Used the CLI to create a second HeroesComponent.
* Displayed the HeroesComponent by adding it to the AppComponent shell.
* Applied the UppercasePipe to format the name.
* Used two-way data binding with the ngModel directive.
* Learned about the AppModule.
* Imported the FormsModule in the AppModule so that Angular would recognize and apply the ngModel directive.
* Learned the importance of declaring components in the AppModule and appreciated that the CLI declared it for you.
* Tour of Heroes app displays a list of heroes in a Master/Detail view.
* User can select a hero and see that hero's details.
* Used *ngFor to display a list.
* Used *ngIf to conditionally include or exclude a block of HTML.
* Can toggle a CSS style class with a class binding.
* Created a separate, reusable HeroDetailComponent.
* Used a property binding to give the parent HeroesComponent control over the child HeroDetailComponent.
* Used the @Input decorator to make the hero property available for binding by the external HeroesComponent.
* Refactored data access to the HeroService class.
* Registered the HeroService as the provider of its service at the root level so that it can be injected anywhere in the app.
* Used Angular Dependency Injection to inject it into a component.
* Gave the HeroService get data method an asynchronous signature.
* Discovered Observable and the RxJS Observable library.
* Used RxJS of() to return an observable of mock heroes (Observable<Hero[]>).
* Component's ngOnInit lifecycle hook calls the HeroService method, not the constructor.
* Created a MessageService for loosely-coupled communication between classes.
* HeroService injected into a component is created with another injected service, MessageService.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.
