
  

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
     22, ![145882523-24839a22-b01b-4ab6-a461-31f2342f748d](https://user-images.githubusercontent.com/81395283/145893568-4159812c-4de8-48d1-8394-8c155747ae88.png)

    ['Javascript', 'Typescript', 'Angular', 'HTML', 'CSS', 'Firebase']
    );
  } 



```






