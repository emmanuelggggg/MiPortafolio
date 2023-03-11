<script>
export default {

    name: 'ComponenteMain',
    data() {
        return {
            nombre: 'Jesús Emmanuel',
        }
    },
};
</script>
<template>
    <div id="ComponentMain">
        <header class="masthead">
            <div class="container px-5">
                <div class="row gx-5 align-items-center">
                    <div class="col-lg-6">
                        <!-- Mashead text and app badges-->
                        <div class="mb-5 mb-lg-0 text-center text-lg-start">
                            <h1 class="display-1 lh-1 mb-3">{{ nombre }}</h1>
                            <p class="lead fw-normal text-muted mb-5">Software Development Engineer!</p>
                            <div class="iconos ">
                                <ul class="list-unstyled d-flex justify-content-center aling-item-center ">
                                    <li class="ms-3 "><a class="google link-dark" href="mailto:Many1997XD@gmail.com" target="_blank">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" fill="white" class="bi bi-google" viewBox="0 0 16 16">
                                        <path d="M15.545 6.558a9.42 9.42 0 0 1 .139 1.626c0 2.434-.87 4.492-2.384 5.885h.002C11.978 15.292 10.158 16 8 16A8 8 0 1 1 8 0a7.689 7.689 0 0 1 5.352 2.082l-2.284 2.284A4.347 4.347 0 0 0 8 3.166c-2.087 0-3.86 1.408-4.492 3.304a4.792 4.792 0 0 0 0 3.063h.003c.635 1.893 2.405 3.301 4.492 3.301 1.078 0 2.004-.276 2.722-.764h-.003a3.702 3.702 0 0 0 1.599-2.431H8v-3.08h7.545z"/>
                                        </svg>
                                        </a></li>
                                    <li class="ms-3 "><a class="twitter link-dark" href="https://twitter.com/JesusEm50037139" target="_blank">
                                            <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" fill="white"
                                                class="bi bi-twitter" viewBox="0 0 16 16">
                                                <path
                                                    d="M5.026 15c6.038 0 9.341-5.003 9.341-9.334 0-.14 0-.282-.006-.422A6.685 6.685 0 0 0 16 3.542a6.658 6.658 0 0 1-1.889.518 3.301 3.301 0 0 0 1.447-1.817 6.533 6.533 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.325 9.325 0 0 1-6.767-3.429 3.289 3.289 0 0 0 1.018 4.382A3.323 3.323 0 0 1 .64 6.575v.045a3.288 3.288 0 0 0 2.632 3.218 3.203 3.203 0 0 1-.865.115 3.23 3.23 0 0 1-.614-.057 3.283 3.283 0 0 0 3.067 2.277A6.588 6.588 0 0 1 .78 13.58a6.32 6.32 0 0 1-.78-.045A9.344 9.344 0 0 0 5.026 15z" />
                                            </svg>
                                        </a></li>
                                    <li class="ms-3 "><a class="linkedin link-dark"
                                            href="https://www.linkedin.com/in/jesus-emmanuel-carballo-caballero-ab1a39269/" target="_blank">
                                            <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" fill="white" class="bi bi-linkedin" viewBox="0 0 16 16">
                                            <path d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854V1.146zm4.943 12.248V6.169H2.542v7.225h2.401zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248-.822 0-1.359.54-1.359 1.248 0 .694.521 1.248 1.327 1.248h.016zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016a5.54 5.54 0 0 1 .016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225h2.4z"/>
                                            </svg>
                                        </a></li>
                                    <li class="ms-3 "><a class="gitHub link-dark"
                                            href="https://github.com/emmanuelggggg" target="_blank">
                                            <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" fill="white"
                                                class="bi bi-github" viewBox="0 0 16 16">
                                                <path
                                                    d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.012 8.012 0 0 0 16 8c0-4.42-3.58-8-8-8z" />
                                            </svg>
                                        </a></li>
                                </ul>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-6">
                        <!-- Masthead device mockup feature-->
                        <div class="masthead-device-mockup ">
                            <svg class="circle" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
                                <defs>
                                    <linearGradient id="circleGradient" gradientTransform="rotate(45)">
                                        <stop class="gradient-start-color" offset="0%"></stop>
                                        <stop class="gradient-end-color" offset="100%"></stop>
                                    </linearGradient>
                                </defs>
                                <circle cx="50" cy="50" r="50"></circle>
                            </svg>

                            <svg class="shape-1 d-none d-sm-block" viewBox="0 0 240.83 240.83"
                                xmlns="http://www.w3.org/2000/svg">
                                <rect x="-32.54" y="78.39" width="315.92" height="84.05" rx="42.03"
                                    transform="translate(120.42 -49.88) rotate(45)"></rect>
                                <rect x="-32.54" y="78.39" width="315.92" height="84.05" rx="42.03"
                                    transform="translate(-49.88 120.42) rotate(-45)"></rect>
                            </svg>

                            <svg class="shape-2 d-none d-sm-block" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
                                <circle cx="50" cy="50" r="50"></circle>
                            </svg>
                            <div class="device-wrapper">
                                <div class="device bg-light" data-device="iPhoneX" data-orientation="portrait"
                                    data-color="black">
                                    <div class="screen ">
                                        <img style="max-width: 100%; height: 100%" src="../icons/im.png" />
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

        </header>
        <!-- History -->
        <article class="text-center bg-gradient-primary-to-secondary">
            <div class="container px-5">
                <div class="row gx-5 justify-content-center">
                    <div class="col-xl-8">
                        <div class="text-white mb-4">
                            <h3 class="text-center mt-5">
                                Hi!, I'm Jesus Emmanuel
                            </h3>
                            <span>
                                I am currently a software development engineering student. 1 year of experience in frontend. My adventure begins two and a half years ago in college, I have done distance work, social service and professional practices in autonomous places of government La Paz B.C.S.(Mexico). I am a calm and confident person, curious by nature, I work to improve the life of my wife and son.
                            </span>
                        </div>
                        <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" fill="white" class="bi bi-github m-5"
                            viewBox="0 0 16 16">
                            <path
                                d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.012 8.012 0 0 0 16 8c0-4.42-3.58-8-8-8z" />
                        </svg>
                    </div>
                </div>
            </div>
        </article>

        <!-- Skills -->
        <section id="skills">
            <div class="container px-5">
                <div class="row gx-5 align-items-center">
                    <div class="col-lg-8 order-lg-1 mb-5 mb-lg-0">
                        <h3 class="text-primary text-center">Skills</h3>
                        <hr class="bg-primary">

                        <div class="container-fluid px-5 ">
                            <div class="row gx-5 ">
                                <div class="col-md-6 mb-5">
                                    <!-- Feature item-->
                                    <div class="text-center">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="66" height="66" fill="blue"
                                            class="bi bi-laptop" viewBox="0 0 16 16">
                                            <path
                                                d="M13.5 3a.5.5 0 0 1 .5.5V11H2V3.5a.5.5 0 0 1 .5-.5h11zm-11-1A1.5 1.5 0 0 0 1 3.5V12h14V3.5A1.5 1.5 0 0 0 13.5 2h-11zM0 12.5h16a1.5 1.5 0 0 1-1.5 1.5h-13A1.5 1.5 0 0 1 0 12.5z" />
                                        </svg>
                                        <h3 class="font-alt">LANGUAGES</h3>

                                        <ul class="text-muted mb-0">
                                            <li>JAVA</li>
                                            <li>PHP</li>
                                            <li>PYTHON</li>
                                            <li>C++</li>
                                            <li>HTML</li>
                                            <li>CSS</li>
                                            <li>JAVASCRIPT</li>
                                            <li>KOTLIN</li>
                                            
                                        </ul>

                                    </div>
                                </div>
                                <div class="col-md-6 mb-5">
                                    
                                    <div class="text-center">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="66" height="66" fill="blue"
                                            class="bi bi-database" viewBox="0 0 16 16">
                                            <path
                                                d="M4.318 2.687C5.234 2.271 6.536 2 8 2s2.766.27 3.682.687C12.644 3.125 13 3.627 13 4c0 .374-.356.875-1.318 1.313C10.766 5.729 9.464 6 8 6s-2.766-.27-3.682-.687C3.356 4.875 3 4.373 3 4c0-.374.356-.875 1.318-1.313ZM13 5.698V7c0 .374-.356.875-1.318 1.313C10.766 8.729 9.464 9 8 9s-2.766-.27-3.682-.687C3.356 7.875 3 7.373 3 7V5.698c.271.202.58.378.904.525C4.978 6.711 6.427 7 8 7s3.022-.289 4.096-.777A4.92 4.92 0 0 0 13 5.698ZM14 4c0-1.007-.875-1.755-1.904-2.223C11.022 1.289 9.573 1 8 1s-3.022.289-4.096.777C2.875 2.245 2 2.993 2 4v9c0 1.007.875 1.755 1.904 2.223C4.978 15.71 6.427 16 8 16s3.022-.289 4.096-.777C13.125 14.755 14 14.007 14 13V4Zm-1 4.698V10c0 .374-.356.875-1.318 1.313C10.766 11.729 9.464 12 8 12s-2.766-.27-3.682-.687C3.356 10.875 3 10.373 3 10V8.698c.271.202.58.378.904.525C4.978 9.71 6.427 10 8 10s3.022-.289 4.096-.777A4.92 4.92 0 0 0 13 8.698Zm0 3V13c0 .374-.356.875-1.318 1.313C10.766 14.729 9.464 15 8 15s-2.766-.27-3.682-.687C3.356 13.875 3 13.373 3 13v-1.302c.271.202.58.378.904.525C4.978 12.71 6.427 13 8 13s3.022-.289 4.096-.777c.324-.147.633-.323.904-.525Z" />
                                        </svg>
                                        <h3 class="font-alt">DATABASE</h3>
                                        <ul class="text-muted mb-0">                            
                                            <li>PHP_MY_ADMIM</li>
                                            <li>SQL</li>
                                            <li>MONGODB</li>
                                        </ul>

                                    </div>
                                </div>
                            </div>
                            <div class="row">
                                <div class="col-md-6 mb-5 mb-md-0">
                                    <!-- Feature item-->
                                    <div class="text-center">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="66" height="66" fill="blue" class="bi bi-box-fill" viewBox="0 0 16 16">
                                        <path fill-rule="evenodd" d="M15.528 2.973a.75.75 0 0 1 .472.696v8.662a.75.75 0 0 1-.472.696l-7.25 2.9a.75.75 0 0 1-.557 0l-7.25-2.9A.75.75 0 0 1 0 12.331V3.669a.75.75 0 0 1 .471-.696L7.443.184l.004-.001.274-.11a.75.75 0 0 1 .558 0l.274.11.004.001 6.971 2.789Zm-1.374.527L8 5.962 1.846 3.5 1 3.839v.4l6.5 2.6v7.922l.5.2.5-.2V6.84l6.5-2.6v-.4l-.846-.339Z"/>
                                        </svg>
                                        <h3 class="font-alt">Frame Works</h3>
                                        <ul class="text-muted mb-0">
                                            <li>VUE JS</li>
                                            <li>BOOTSTRAP</li>
                                            <li>LARAVEL</li>
                                        </ul>
                                    </div>
                                </div>
                                <div class="col-md-6">
                                    <!-- Feature item-->
                                    <div class="text-center">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="56" height="53" fill="blue"
                                            class="bi bi-tools" viewBox="0 0 16 16">
                                            <path
                                                d="M1 0 0 1l2.2 3.081a1 1 0 0 0 .815.419h.07a1 1 0 0 1 .708.293l2.675 2.675-2.617 2.654A3.003 3.003 0 0 0 0 13a3 3 0 1 0 5.878-.851l2.654-2.617.968.968-.305.914a1 1 0 0 0 .242 1.023l3.27 3.27a.997.997 0 0 0 1.414 0l1.586-1.586a.997.997 0 0 0 0-1.414l-3.27-3.27a1 1 0 0 0-1.023-.242L10.5 9.5l-.96-.96 2.68-2.643A3.005 3.005 0 0 0 16 3c0-.269-.035-.53-.102-.777l-2.14 2.141L12 4l-.364-1.757L13.777.102a3 3 0 0 0-3.675 3.68L7.462 6.46 4.793 3.793a1 1 0 0 1-.293-.707v-.071a1 1 0 0 0-.419-.814L1 0Zm9.646 10.646a.5.5 0 0 1 .708 0l2.914 2.915a.5.5 0 0 1-.707.707l-2.915-2.914a.5.5 0 0 1 0-.708ZM3 11l.471.242.529.026.287.445.445.287.026.529L5 13l-.242.471-.026.529-.445.287-.287.445-.529.026L3 15l-.471-.242L2 14.732l-.287-.445L1.268 14l-.026-.529L1 13l.242-.471.026-.529.445-.287.287-.445.529-.026L3 11Z" />
                                        </svg>
                                        <h3 class="font-alt">Tools</h3>
                                        <ul class="text-muted mb-0">
                                            <li>GIT</li>
                                            <li>GITHUB</li>
                                            <li>POSTMAN</li>
                                            <li>API'S</li>

                                        </ul>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4 order-lg-0">
                        <!-- Features section device mockup-->
                        <div class="features-device-mockup">
                            <svg class="circle" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
                                <defs>
                                    <linearGradient id="circleGradient" gradientTransform="rotate(45)">
                                        <stop class="gradient-start-color" offset="0%"></stop>
                                        <stop class="gradient-end-color" offset="100%"></stop>
                                    </linearGradient>
                                </defs>
                                <circle cx="50" cy="50" r="50"></circle>
                            </svg><svg class="shape-1 d-none d-sm-block" viewBox="0 0 240.83 240.83"
                                xmlns="http://www.w3.org/2000/svg">
                                <rect x="-32.54" y="78.39" width="305.92" height="84.05" rx="42.03"
                                    transform="translate(120.42 -49.88) rotate(45)"></rect>
                                <rect x="-32.54" y="78.39" width="305.92" height="84.05" rx="42.03"
                                    transform="translate(-49.88 120.42) rotate(-45)"></rect>
                            </svg><svg class="shape-2 d-none d-sm-block" viewBox="0 0 100 100"
                                xmlns="http://www.w3.org/2000/svg">
                                <circle cx="50" cy="50" r="50"></circle>
                            </svg>
                            <div class="device-wrapper">
                                <div class="device">
                                    <div class="screen d-flex aling-items-center" style="height: 300px;">
                                        <img class="img-fluid" src="../icons/iomac.png" />
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <article id="works" class="text-center bg-gradient-primary-to-secondary">
            <div class="container px-5">
                <div class="row gx-5 justify-content-center">
                    <div class="col-xl-8">
                        <div class="text-white mb-4">
                        <h3 class="text-center mt-5">
                            My works
                        </h3>
                    </div>
                </div>
                
                <!-- my works -->
                <div class="row gx-0 mb-5 mb-lg-0 ">
                    <div class="col-lg-6 mt-5">
                        <a href="https://seseabcs.gob.mx/sesea/"
                            class="text-white m-5" 
                            target="_blank">
                            SECRETARIA EJECUTIVA DEL SISTEMA ESTATAL ANTICORRUPCIÓN
                        </a>
                        <img src="../icons/sesea.png" class="img-fluid  shadow-lg" 
                        style="border-radius:10px;width: 600px; height: 300px; padding-right:5px;" alt="">
                    </div>
                    <div class="col-lg-6 mt-5">
                        <a 
                            class="text-white m-5"
                            href="https://www.seabcs.gob.mx/"
                            target="_blank">
                            SISTEMA ESTATAL ANTICORRUPCIÓN
                        </a>
                        <img src="../icons/sea.png" class="img-fluid  shadow-lg" 
                        style="border-radius:10px;width: 600px; height: 300px; padding-left: 5px;" alt="">
                    </div>
                    <div class="col-lg-6 mt-5 mb-5">
                        <a 
                            class="text-white m-5"
                            href="https://moviesids.netlify.app/html/home.html"
                            target="_blank">
                            MOVIE DB
                        </a>
                        <img src="https://elangelcota.netlify.app/assets/moviedb-76d6d6a8.png" class="img-fluid  shadow-lg" 
                        style="border-radius:10px;width: 600px; height: 300px; padding-left: 5px;" alt="">
                    </div>
                    <div class="col-lg-6 mt-5 mb-5">
                        <a 
                            class="text-white m-5"
                            href="https://gabaeltylorportafolio.000webhostapp.com/"
                            target="_blank">
                            PORFILE TYLOR
                        </a>
                        <img src="../icons/gaba.png" class="img-fluid  shadow-lg" 
                        style="border-radius:10px;width: 600px; height: 300px; padding-left: 5px;" alt="">
                    </div>
                </div>
            </div>
        </div>
    </article>
    
</div></template>


<style scoped>
    @import '../../assets/estiloIcons.css';
    @import '../../assets/works.css';
</style>
