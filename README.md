# ReproAngularSsr

1. `ng new repro-angular-ssr --minimal --skip-tests --strict --style css --inline-template --inline-style`
2. `ng generate @angular/core:standalone` (selected bootstrap at path `./`)

#### This now fails:

`ng add @nguniversal/express-engine --verbose`

Error:

```log
ℹ Using package manager: npm
⠋ Searching for compatible package version...Locating potential npmrc files:
✔ Found compatible package version: @nguniversal/express-engine@15.2.0.
✔ Package information loaded.

The package @nguniversal/express-engine@15.2.0 will be installed and executed.
Would you like to proceed? Yes
✔ Packages successfully installed.
Bootstrap call not found
```
