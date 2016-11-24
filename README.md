# typescript
TypeScript Style Guide

* Always define the return type of functions.
* Types should be used whenever necessary (no implicit any).
* Arrays should be defined as ```Array<type>``` instead of ```type[]```.
* Use the any type sparingly, it is always better to define an interface.
* All TypeScript files must have a ".ts" extension.
* They should be all lower case, and only include letters, numbers, and periods.
* Files should include in the filename what they represent, as in (app.component.ts or users.service.ts)
* All files should end in a new line. This is necessary for some Unix systems.
* All variable and function names should be formed with alphanumeric A-Z, a-z and underscore _ characters.
* Variable, module, and function names should use lowerCamelCase.
* Use ```cons```t where appropriate, for values that should never change
* Use ```let``` everywhere else
* Avoid using ```var```
