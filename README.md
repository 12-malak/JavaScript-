# JavaScript-
//JavaScript to remove a property from an object


const student = { 

    name: 'Piyush',

    age: 23,
    
    hobbies: ['singing', 'reading', 'coding'],
    
    greet: function()
    
    {
        console.log('Hello everyone.');
        

    },
    
    score: {
        maths: 100,
        science: 55
    }
    
};

// deleting a property from an object

delete student.greet;

delete student['score'];

console.log(student);
