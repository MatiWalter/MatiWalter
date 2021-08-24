# Hola! Soy Matías 👋🏻

## 🙎🏻‍♂️ Sobre Mi

Soy estudiante de la Licenciatura en Sistemas de Informacion en la Universidad Nacional de Luján
y en mis tiempos libres estudio Desarrollo Web

Mis hobbies son:

- 🎮 Jugar videojuegos.
- 📺 Mirar anime, series y/o películas.
- ⚽ Jugar y mirar Futbol.

### // AboutMe.ts

```tsx
  export interface Person = {
    name: string;
    age: number;
    country: string;
    profession: string;
    skills: string[];
  }  

  const me: Person = {
    name: 'Matías Walter',
    age: 24,
    country: 'Argentina',
    profession: 'Desarrollador Web Fullstack',
    skills: ['Typescript', 'React Js', 'Redux' ,'Next Js', 'Node Js', 'Firebase', 'MongoDb']
  }

  const toString(person: Person): string => {
    const greeting: string = `Hola! Soy ${person.name}, tengo ${person.age} años y soy ${person.profession}`
    return greeting;
  }

  console.log(toString(me));
  console.log('Mis skills principales son => ', me.skills);

  console.log('Gracias por visitarme!');

```

### 🤝🏻 Contactame

[![linkedin](https://img.icons8.com/plasticine/100/000000/linkedin.png)](https://www.linkedin.com/in/matias-walter/)[![gamil](https://img.icons8.com/plasticine/100/000000/gmail.png)](mailto:matiwalter97@gmail.com)
