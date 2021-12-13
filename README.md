
<h1> Hi there 👋 </h1>

<h2> A little more about me...    </h2>




 
  

```javascript  
export class Developer() {
  
  name: string;
  age: number;
  skills: string[];

  constructor(name: string, age: number, skills: string[]) {
    this.name = name;
    this.age = age;
    this.skills = skills;
  }

}

 ngOnInit() {
    let Marco: Developer = new Developer(
    'Marco',
     22, 
    ['Javascript', 'Typescript', 'Angular', 'HTML', 'CSS', 'Firebase']
    );
  } 



```






