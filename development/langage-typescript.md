# TypeScript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- l'intéret de TypeScript dans l'IDE ✔️
- les types de bases ✔️
- comment et pourquoi étendre une interface ✔️
- les classes et les decorators ❌

## 💻 J'utilise

### Un exemple personnel commenté ❌

- les types de bases :
  -Primitifs :
    const unknowed:any
    const simpleTrueFalse:boolean
    const name:string
    const age:number
    const returnNothing:void
    const nothing:null
    const nothing:undefined
  -Personnalisés :
    - Array
    const anArray : number[] = [1, 20, 3];
    - Tuple
    let aSimpleTuple: [string, number];  
    aSimpleTuple = ["stack", 1, "trace", 3];
    - Function
    function aSimpleFunction(a: number, b: number): number {  
            return a + b;  
     } 
    - Enum
      enum aSimpleEnum {
        Newsletter = "NEWSLETTER",
        Magazine = "MAGAZINE",
        Livre = "LIVRE"
      }
      aSimpleEnum.Livre; //retourne LIVRE
      aSimpleEnum['Magazine'];//returns MAGAZINE
    - Class ...
    - Interface ...


- comment et pourquoi étendre une interface :

    interface IPerson {
        name: string;
    }

    interface IEmployee extends IPerson {
        empCode: number;
    }

    let my_emp:IEmployee = {
        empCode:109,
        name:"StackTrace",
    }
    
 - 

### Utilisation dans un projet ❌

[lien github](...)

Description :

### Utilisation en production si applicable❌

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌

Description :

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌
Les cas de base OK mais quand le code se complexifie j'ai plus de mal, comme typer les objets ou des classes complexes

Description:

Plan d'action : (à valider par le formateur)

- Faire un exercice en Typescript afin de voir se que je peut faire et à partir de quand je bloque ❌
- Trouver un site pour s'exercer en TypeScript


Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
