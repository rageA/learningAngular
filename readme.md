# part 4 - Customizing components and directives

`ng generate interface housingLocation` - this will generate an interface called housingLocation.

`@Input({ required: true }) housingLocation!: HousingLocation;`  - used the 'required true' to enforce that this property needs to be passed down to this child component. The 'housingLocation!', the pling character is known as non-null property. tells property its safe without being initilize as its never going to be null.

# part 5 - basic routing

In this section we learn about how to create basic routes. how to pass data in the parameter.

# part 7 - basic form

- learn the basic of creating a form using ReactiveFormsModule.
 remember to declare it in the import otherwise in the HTML it wont like it when you bind the form.
