# Make sure FormsModule is imported into app.module.ts

# You can make angular recognize the form by putting

# ngModel name="" on the Inputs

# To get access to the data from ngForm

# <form (ngSubmit)="onSubmit(f)" #f="ngForm">

# onSubmit(form: NgForm) {

    console.log(form);

}

# This puts the data into an ngForm, you can access the value from there.
