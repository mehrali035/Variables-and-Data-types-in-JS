# Variables-and-Data-types-in-JS

/****👉 values and variables in JavaScript ****/

 var myname = 'Mehr Ali'
 var myage = 26;
 console.log(myname);
 console.log(myage);

/**** 👉 Data Types in JavaScript ****/

 var myname = 'Mehr Ali Malik'  
 console.log(typeof(myname)); 

    var iammehr = true; 
    console.log(iammehr);
    console.log(typeof(iammehr));

 console.log(10 + "20");               =1020( concat)
 console.log(9 - "5");                 =4  this is bug
 console.log( "java "  + "script");    = javascript 
 (concat) and if u give space after comma it will be "java script"
 console.log(" " + " "); empty space 
 console.log(true + false);            =1 becose true=1 and false=0
 console.log(false - true);            =-1
 console.log(true + true);             =2
 console.log(true - true);             =0
 console.log(false - false);           =0
 console.log(false + false);           =0
 console.log("Mehr " - "ali");         =NaN (IQ) 'not a number'

//Null VS Undefined

 var iAmUseless = null;
 console.log(iAmUseless);           =null (this is bug)
 console.log(typeof(iAmUseless));  

 var iamstandby;      
 console.log(iamstandby);
 console.log(typeof(iamstandby));  = undefined


//   NAN PARACTICE
 NaN === NaN;   = false
 Number.NaN === NaN; false
 isNaN(NaN);            true
 isNaN(Number.NaN); true
 Number.isNaN(NaN);  true

 console.log(NaN === NaN);
 console.log(Number.NaN === NaN);
 console.log( (isNaN)(NaN));
 console.log(Number.isNaN (NaN));


