This repository demonstrates a subtle bug in TypeScript related to optional properties. The `bug.ts` file contains code that compiles without error but can cause runtime issues if an object with missing properties is passed to the function. The `bugSolution.ts` file shows the corrected code that uses optional properties and null checks to handle missing values appropriately. This showcases a case where TypeScript's type system doesn't entirely safeguard against possible runtime errors if proper null or undefined checks are not implemented.