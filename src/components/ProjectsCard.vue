<template>
<div class="main-container">
        <div>
        <div class="project-card" v-for="(items, index) in projectData.ProjectsArray" v-bind:key="items">
            <h2> {{projectData.ProjectsArray[index].Title}}</h2>
            <img :src="projectData.ProjectsArray[index].Image" alt="">
            <p> {{projectData.ProjectsArray[index].About}}</p>
            <div class="links">
                <a :href="projectData.ProjectsArray[index].Link1" target="blank"><img src="../assets/gb.jpg" alt=""></a>
                <a :href="projectData.ProjectsArray[index].Link2" target="blank"><img src="../assets/fb.jpg" alt=""></a>
               
            </div>
        </div>
    </div>
    
    </div>
</template>

<script>
import jsonData from "/projects.json"
export default{
    data(){
        return {
            projectData: jsonData
        }
    }

}

</script>

<style scoped>
.main-container{
display: flex;

}
.project-card{
   
    margin: 5px;
    padding: 20px;
    flex-direction: center;
    background-color: white;
   
    border-radius:150px;
    box-shadow: rgb(0, 0, 0,)0px 3px 8px;
}
.project-card img{
height: 35rem;
margin: 5%;
flex-wrap: wrap;
}
.links{
    display: flex;
    flex-direction: center
    
}
.links img{
    height: 5rem;
    margin: 5px;
    border-radius: 50px;
    flex-wrap: wrap;
}
</style>