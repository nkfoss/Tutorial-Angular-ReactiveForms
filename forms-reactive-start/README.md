### Reactive Forms
This is actually more versatile than template-driven forms.

#### Required Modules
1. ReactiveFormsModule

#### Connections
1. [formGroup]="signupForm" ... this connects the HTML form to the typescript FormGroup object
2. formControlName= <name> ... this links the HTML form field to the typsecript FormObject's formControl field.
3.(ngSubmit)="onSubmit()" ... the function that's called when the submit button is pressed.

##### signupForm
Our formgroup now exists in the typescript, instead of the HTML.