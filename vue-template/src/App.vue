<template>
  <div class="container">
    <h3>{{title}}</h3>
    <form>
    <textarea placeholder="Add new task"></textarea>
    <button type="button">Add Task</button>
    </form>
    <ul>
    <li> v-for="task in tasks">{{ task }}</li>
    </ul>      

  
    </div>
    </template>

    <script>
    export default{
      data:function(){
        return{
          title:'my task manager',          
          task:{
            "Task one",
            "Task two", 
            "Task three",
            "Task four",
          }
        }
      }
    }

 

</script>

