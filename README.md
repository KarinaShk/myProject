Задача 3

const students = [
    { name: 'alex', age: 20 },
    { name: 'mike', age: 24 },
    { name: 'masha', age: 20 },
    { name: 'stas', age: 18 },
];
const studentsWithNameAndAge = students.map( students=> {
     return{
         ...students,
        NameAndAge: `${students.name}${students.age}`,
}
    } );
    studentsWithNameAndAge
    .forEach(students => console.log (students.NameAndAge)); 
