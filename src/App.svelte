<script>
let age
 age = 2
 function onclick() {
   age = age + 1
 }
 function onClick() {
   age = age - 1
 }
 function onCLick() {
   age = age + 10
 }
 function onCLIck() {
   age = age - 10
 }
 
  </script>
  
<h1>
hello i am a person
</h1>
<h1>
i have a dog, she is {age}

</h1>

<button on:click={onclick}>Change something on this page! (age +1)</button>
<button on:click={onClick}>Change something else on this page!! (age -1)</button>
<button on:click={onCLick}>Change a third thing on this page!!! (age +10)</button>
<button on:click={onCLIck}>How about a fourth thing!!!! (age -10)</button>


<h2>
dogs are better then cats 

</h2>
<button on:click={onCLICk}>Yes</button>
<button on:click={onCLICK}>No</button>
<p>
 They just are 
 
 </p>

<style>
h1 {background: aquamarine
}
h2 {background: blue
}
p {background: navy
}
</style>



