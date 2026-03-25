# Typescript
Daily Type-script learning 
<div>Source:- 
  <h1 align="center">
  <a href="https://www.youtube.com/playlist?list=PLu71SKxNbfoBkkr8lblqtsJvxrw3j1tWC">
    Chai aur TypeScript ▶️
  </a>
    </br>
    </br>
    <a href="https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html">
    Documentation 📄
  </a>
</h1>
  </br>
  <p>
    
     1. TypeScript is addon on Javascript.
     
     2. TypeScript works on process and give the javascript.
     
    [ts]--->[process]--->[js]
    
     3.Features :-
      -> TypeChecker
      -> Consistency
</p>

<h1>Basic Syntax</h1>
<p>
       
      
      function greet(name: string): string { -->string: type checking
            return `Hello this is ${name} `;
          } 
          
      console.log(greet("ark"));
   
</p>



<p>
#Type anotation and inference
       
    Type anotation means giving a dataype to a variable.
    Infernce means passing a another data type to a variable which is already declared.
   
</p>


<p>
#Union and Any
  
      Union means passing multiple value to a single variable:-
           1. let data:string | number = "data"
           2. let apiRequest : 'pending' | 'sucess'| 'error' = 'pending'
           these values will work as suggestions.
     Any means passing any value to a variable:-
           1. let data : string | undefined 
          it may be undefined or any value
</p>

</div>
