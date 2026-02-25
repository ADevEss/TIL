## [25/02/2026] Les fonctions fléchées (Arrow Functions)

### Ce que j'ai appris
- Utiliser `const` pour déclarer une fonction empêche de l'écraser par erreur plus tard.
- Contrairement aux fonctions classiques, elles ne sont pas "hoisted" : on doit les déclarer **avant** de les utiliser, ce qui force une structure de code plus logique (du haut vers le bas).
- Syntaxe plus courte et moderne.

### Exemple de Code
```javascript
// ✅ Bonne pratique : la fonction est protégée
const saluer = (nom) => {
    return `Salut ${nom} !`;
};

console.log(saluer("Dev"));
