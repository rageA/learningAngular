# part 4 - Customizing components and directives

`ng generate interface housingLocation` - this will generate an interface called housingLocation.

`@Input({ required: true }) housingLocation!: HousingLocation;`  - used the 'required true' to enforce that this property needs to be passed down to this child component. The 'housingLocation!', the pling character is known as non-null property. tells property its safe without being initilize as its never going to be null.
