<template>
    <div class="wrapper">
        <div class="main-container">
            <div class="container-one">
                <div class="profile">
                    <img src="../assets/profile.jpg" alt="">
                    <h3>WELMAR SUMAGANG</h3>
                    <p>GRAPHICS DESIGNER</p>
                </div>
                <div class="social-link">
                    <div class="link">
                        <a href="https://www.facebook.com/welmar02" target="blank">
                            <img src="../assets/fb.jpg" alt="">
                            <h2>FACEBOOK</h2>
                        </a>
                    </div>
                   
                    <div class="link">
                        <a href="https://github.com/Welmar3131" target="blank">
                            <img src="../assets/gb.jpg" alt="">
                            <h2>GITHUB</h2>
                        </a>
                    </div>
                   
                </div>
            </div>
            <div class="container-two">
                <div class="about me ">
                    <h1>About Me</h1>
                    <p>Welmar Sumagang, 23, is a resident of Olanggo. He is known for his dedication to community service and his passion for environmental conservation. In his spare time, he enjoys hiking through the lush landscapes of his hometown.</p>
                    <div class="Language-Section">
                        <h1>PROGRAMMING LANGUAGE Studied</h1>
                        <div class="logos">
                            <img src="../assets/css.jpg" alt="">
                            <img src="../assets/java.jpg" alt="">
                        
                            <div class="button-container">
                                <div class="project-button">
                                    <a href="">EMAIL : welmarsumagang@gmail.com</a>
                                </div>
                             
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>


<style scoped>
.wrapper {
    display: flex;
    justify-content: center;
}

img {
    height: 80px;
}

.main-container {
    display: flex;
    flex-direction: center; /* Change flex-direction to column for smaller screens */
    background-color: rgb(242, 246, 244);
  
}

.container-one {
    background-color: rgb(236, 239, 234);
    width: 70%; /* Take full width */
    padding: 10px; /* Add padding */
 
    margin-bottom: 20px; /* Add margin-bottom for spacing */
    box-shadow: 0px 3px 8px rgba(150, 10, 10, 0.5);
}

.profile img {
    height: 100px; /* Adjust height for profile image */
 /* Make the profile image circular */
    box-shadow: 0px 3px 8px rgba(144, 79, 79, 0.5);
}

.link a {
    text-decoration: none;
    color: #afceed;
    font-size: 14px; /* Increase font size for links */
    margin-bottom: 15px; /* Add margin bottom for spacing */
    display: block; /* Display links as block elements */
    border-radius: 50%;
}

.link img {
    height: 50px; 
    border-radius: 80%;/* Adjust height for social media icons */
}

.container-two {
    background-color: rgb(251, 255, 246);
    box-shadow: rgb(red, green, blue);
    margin: 2%;
    width: 100%; 
    height: 95%;
    padding: 5px; }
 

.about-me {
    text-align: center; /* Center align the text */
    margin-bottom: 20px; /* Add margin bottom for spacing */
}

.logos img {
    height: 50px; /* Adjust height for language logos */
    margin-right: 50px; /* Add margin-right for spacing between logos */
    border-radius: 100%; /* Make the logos circular */
}

.button-container {
    display: row;
    flex-wrap: wrap;
    justify-content: center; 
}

.project-button {
   
    border-radius: 3px;
    padding: 10px 20px; 
    margin: 30px; 
    box-shadow: 0px 3px 8px rgba(218, 21, 21, 0.5);
}

.project-button a {
    text-decoration: none;
    color: #000407;
    font-size: 20x;
}

@media only screen and (min-width: 880px) {
    .main-container {
        width: 80%; 
    }
}
</style>
