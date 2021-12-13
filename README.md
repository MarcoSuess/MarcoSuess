
  

<img align="right" width="100" height="100"  src="https://user-images.githubusercontent.com/81395283/145882523-24839a22-b01b-4ab6-a461-31f2342f748d.png">


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






