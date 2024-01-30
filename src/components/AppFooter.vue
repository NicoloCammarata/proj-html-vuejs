<script>
export default {
    data() {
        return {
            footerMenu: [
                
                {
                    title:'Information',
                    voci:[
                        'Bookmark',
                        'Features',
                        'Sitemap',
                        'Lists',
                        'Contact Us',
                        

                    ]
                
                    
                
                },
                {
                    title:'Extras',
                    voci:[
                        'Delivery',
                        'Cart',
                        'Terms conditions',
                        'My account',
                        'About us',
                        
                    ]
                
                    
                
                },
                
                   
               
            ],

        };
    },
    methods: {

    }
}
</script>

<template>
    <footer class="h-100 w-100 py-4 ">
        <div class="container">
            <div class="row">
                <ul class="address text-white col-4">
                    <h4 >
                        Address Info
                    </h4>
                    <li class="text-white-50">
                        <i class="fa-solid fa-location-dot text-warning"></i> 60 29th Street San Francisco, CA 94110 507-Union Trade Center, United States of America 
                    </li>
                    <li class="text-white-50">
                        <i class="fa-solid fa-phone text-warning"></i> (+00) 123-456-789
                    </li>
                    <li class=" link ">
                        <router-link class="text-white-50 text-decoration-none" :to="{ name: 'contact' }">
                            <i class="fa-solid fa-envelope text-warning"></i> <span>demo@example.com</span>
                            </router-link>
                        
                    </li>

                </ul>
                <ul class="text-white col-2" >
                    <h4 >
                        {{ footerMenu[0].title }}
                    </h4>
                    <li class="text-white-50"  v-for="(voce, y) in footerMenu[0].voci">
                        <router-link class="text-white-50 text-decoration-none link" :to="{ name: 'contact' }">
                            <span class="">{{  voce }}</span>
                            </router-link>
                      
                    </li>
                    
                    
                

                </ul>
                <ul class="text-white col-2" >
                    <h4 >
                        {{ footerMenu[1].title }}
                    </h4>
                    <li class="text-white-50"  v-for="(voce, y) in footerMenu[1].voci">
                        <router-link class="text-white-50 text-decoration-none link" :to="{ name: 'about' }">
                            <span class="">{{  voce }}</span>
                            </router-link>
                      
                    </li>
                    
                    
                

                </ul>
                <ul class="text-white col-4">
                    <h4 >
                        Our Newsletter
                    </h4>
                    <li class="text-white-50">
                        There are many variations of passages of form humour or randomised
                    </li>
                    <li class="text-white-50">
                        <input type="text" class="w-100">
                    </li>
                    <li class="text-white-50 link">
                        <router-link class="text-white-50 text-decoration-none" :to="{ name: 'contact' }">
                            <i class="fa-brands fa-facebook px-2"></i><i class="fa-solid fa-phone px-2"></i><i class="fa-brands fa-google-plus px-2"></i><i class="fa-brands fa-skype px-2"></i><i class="fa-brands fa-instagram px-2"></i>
                            </router-link>
                        
                    </li>

                </ul>
                

            </div>
            
            

        </div> 
        <hr class="text-white">
        <div class="container bottom-footer">
            <div class="row justify-content-between h-100">
                <div class="col-4 text-white d-flex align-items-center">
                    Copyright © 2024 Codezeel

                </div>
                <div class="col-4 text-white ">
                    <img class="w-100" src="../assets/payments.2.jpg" alt="">

                </div>
                
                


            </div>

        </div>
        
        
    </footer>
    
</template>

<style lang="scss" scoped>
footer{
    background-image: url('../assets/footer-bg.png');
    li{
        list-style: none;
        padding: 5px 0;
        
        
    }
    ul{
        
        .link :hover{
            color: yellow;
        }
        
    }
    
    
}
</style>
