* NgRx
  * 👀== Angular's framework -- for -- building reactive applications 👀 /
    * provides libraries for
      * managing global & local state
      * isolate side effects
        * -> cleaner component architecture
      * entity collection management
      * -- integrate with -- Angular Router
      * developer tooling / enhances developer experience | building MANY different types of applications

## Packages

### State

- [Store](../guide/store)
  - == RxJS powered global state management | Angular apps
    - -- inspired by -- Redux
- [Effects](../guide/effects)
  - == side effect model -- for -- @ngrx/store
- [Router Store](../guide/router-store) 
  - == bindings / connect the Angular Router -- to -- @ngrx/store
- [Entity](../guide/entity)
  - == entity State adapter / manage record collections
- [Signals](../guide/signals)
  - == Reactive store + set of utilities | Angular Signals
- [ComponentStore](../guide/component-store)
  - == standalone library / manage local/component state
- [Operators](../guide/operators) 
  - == Shared RxJS operators -- for -- NgRx libraries

### Data

- [Data](../guide/data)
  - == extension -- for -- simplified entity data management

### View

- [Component](../guide/component) 
  - == extension -- for -- building reactive Angular templates

### Developer Tools

- [Store Devtools](../guide/store-devtools)
  - == instrumentation for @ngrx/store / enables
    - visual tracking of state
    - time-travel debugging
- [Schematics](../guide/schematics)
  - == Scaffolding library for Angular applications -- via -- NgRx libraries
- [ESLint Plugin](../guide/eslint-plugin) 
  - == ESLint rules / warn against bad practices + automatic fixes
