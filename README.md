# AlgoPractice
algos related fun 

FizzBuzz: Modolu Operater: 

//Duy's Solution 

function fizzBuzz(num){
    for(let i = 1; i <=num; i++) {
        if(i % 3 === 0 && i % 5 === 0 ) console.log('fizzBuzz'); 
        else if (i % 3 === 0 ) console.log('fizz');
        else if (i % 5 === 0 ) console.log( 'buzz');  
        else console.log(i); 
    }
}

fizzBuzz(100); 


//video demo example 

for(var i=1; i<101; i++) {
    if(i % 15 == 0) {
        console.log("fizzBuzz"); 
    } else if (i % 3 == 0) {
        console.log("fizz"); 
    } else if(i % 5 == 0) {
        console.log("buzz"); 
    } else {
        console.log(i);
    }
}

