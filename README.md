```ts
export class Info {

  name: string = 'Fábio Pereira'
  age: number = 25
  nationality: string = 'Portuguese'
  languages: Record<string, string>[] = [{ 'English': 'C1' }, { 'Portuguese': 'native' }]
  occupation: string = 'Junior Dev || Software Engineer'
  company: string = 'KCS IT'
  university: string = 'Universidade Lusófona do Porto'
  freetime: string[] = ['Dog walks', 'Gaming', 'Cars', 'Eight-ball', 'Learning']

}

export class Programming {

  languages: string[] = ['Golang', 'Java', 'Python', 'JS']
  stylesheets: string[] = ['CSS', 'Bootstrap']
  frameworks: string[] = ['Gin/Fiber', 'Spring', 'Django', 'React Native']
  databases: string[] = ['PostgreSQL', 'MongoDB', 'MySQL']
  cloud: string[] = ['AWS', 'Azure']
  learning: string[] = ['Terraform']
  projects: string[] = [] // private

}

export class Social {

  github: string = 'Chokopikku'
  instagram: string = '@fabiorafa14'
  discord: string = 'Fabeks#3903'

}
```
