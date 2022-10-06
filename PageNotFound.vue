<template>
    <div class="not_found">

        

        <section class="wrapper">
            

            <div class="container">

                

                <div id="scene" class="scene" data-hover-only="false">

                    <span class="ball"></span>
                    <span class="ball_f"></span>
                    <span class="ball_three"></span>
                    <span class="ball_two"></span>
                    <span class="ball_d"></span>
                    <span class="ball_f_d"></span>
                    <span class="ball_three_d"></span>
                    <span class="ball_two_d"></span>


                    

                    <div class="round" data-depth="1.2"></div>

                    <div class="one" data-depth="0.9">

                        <div class="content">
                            
                        </div>
                        
                    </div>
               

                    <p class="plogo" data-depth="0.50">404</p>
                    <p class="plogo" data-depth="0.10">404</p>

                </div>

                <div class="text">
                    <article>
                        <p>Oh oh! Sembra che ti sia perso <br>Torna nella HomePage</p>
                        <button @click="home()" class="btn my_btn btn_fe">HomePage</button>
                    </article>
                </div>

            </div>
            
        </section>
        
    </div>
</template>

<script>
    export default {
        methods: {
            home() {
                this.$router.push('/');
            }
        }
    }
</script>
