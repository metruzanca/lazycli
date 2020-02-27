# Description

Created to make creating e.g. new components more streamlined.

Imagine this situation: You're in react-typescript and you wanna create a new component.
First you gotta `touch index.tsx style.scss` then you need to enter into those files and add your react imports, import your sass variables/mixin file, create your component structure, which can be done with snippets, but maybe this specific project has a specific style or structure. React with/without typescript, hooks/class components. Many things can change.

The goal of this project is to add a bunch of templates to call upon e.g. `<npx> lazy rfc` which by default grab a default template but can be overridden by a .lazy/ templates folder making these templates a available to the whole team.