# Svirbutovich Eugen
---
### Contacts: 
**e-mail:** azenkurit@gmail.com

---
### About myself:
---
***I’m interested in Web Development ( Fullstack JS)***

### Skills and Proficiency:

- HTML5, CSS3
- JavaScript Basics, Typescript
- Git, GitHub
- VS Code
- React

---

### Code example:
```javascript
module.exports = function towelSort (matrix) {  
  if ( !matrix ) { return [] }
  let rez = [];
  let direction = 1;
  for ( let i=0; i< matrix.length; i++ ) {
    if ( direction === 1 ) {
      for ( let j=0; j<matrix[i].length; j++ ) {
        rez.push( matrix[i][j])
      }
      direction = -1;
    }
    else {
      for ( let j=matrix[i].length-1; j>=0; j-- ) {
        rez.push( matrix[i][j])
      }
      direction = 1;
    }
  }
  return rez;
}
```
---
### Courses:
- Rsschool JS/FE Pre-School 2022 (https://app.rs.school/certificate/ckf8o7cg)
---
### Languages:

- English \- Intermediate/Upper-intermediate 
- Russian \- Native
- Belorussian \-Native