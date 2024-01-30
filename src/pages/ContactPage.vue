<script>
export default {
    data() {
        return {

        };
    }
}
</script>

<template>
    <div id="contact">
        <div class="container  text-white ">
            <div class="row">
                <div class="col-12 d-flex justify-content-between align-item-center p-4">
                    <div>
                        Home >> contact us
                    </div>
                    <div>
                        contact us
                    </div>

                </div>
                <div class="col-12 p-0">
                    <iframe class="w-100" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3154.955820555072!2d-122.42403852424613!3d37.74418067199307!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x808f7e42e0f00001%3A0xdc05e70a8276cc77!2s60%2029th%20St%20%23343%2C%20San%20Francisco%2C%20CA%2094110%2C%20Stati%20Uniti!5e0!3m2!1sit!2sit!4v1706554491559!5m2!1sit!2sit"  height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
                    

                </div>

            </div>

        </div>
        <div class="container text-white bg-dark p-4">
            <div class="row">
                <div class="col-12">
                    <h2 class="text-center ">Contact us</h2>
                    <div class="text-center py-2">Get in touch with us for inquiries or business proposals.we'll get back to you!</div>

                    
                    <div class="my-4">
                        <span class="text-white-50 py-1">Subject</span>
                        <input class="col-12 text-white bg-dark " type="text">
                    </div>
                    <div class="my-4">
                        <span class="text-white-50 py-1">Your Name (required)</span>
                        <input class="col-12 text-white bg-dark " type="text">
                    </div>
                    <div class="my-4">
                        <span class="text-white-50 py-1">Your Email (required)</span>
                        <input class="col-12 text-white bg-dark " type="text">
                    </div>
                    <div class="my-4">
                        <span class="text-white-50 py-1">Your Message</span>
                        <input class="col-12 text-white bg-dark message" type="text">
                    </div>

                    <button type="button" class="btn btn-secondary">Send</button>

                   

                </div>

            </div>

        </div>
        
        <div class="container text-white py-1 my-0 p-0">
            <div class="text-white py-1">
                Codezeel Web Service Pvt. Ltd.
            </div>
            <div class="text-white-50 py-1">
                We Possess Within Us Two Minds. So Far I Have Written Only Of The Conscious Mind. I Would Now Like To Introduce You To Your Second Mind, The Hidden And Mysterious Subconscious. Our Subconscious Mind Contains Such Power And Complexity That It Literally Staggers The Imagination.
            </div>
            <div class="row py-3 justify-content-around">
                <div class="col-3 border p-0 d-flex align-items-center justify-content-center direttive">
                    <div class="w-25 bg-dark d-flex justify-content-center align-items-center h-100 text-warning">
                        <i class="fa-solid fa-location-dot"></i>

                    </div>
                    <div class="w-75 border-start p-3 h-100">
                        <div class="h-100">
                            <span>Address:</span>
                            <div class="text-white-50">60, 29th Street #343, San Francisco, CA</div>
                            <div class="text-white-50">94110, United States Of America</div>
                        </div>

                    </div>

                </div>
                <div class="col-3 border p-0 d-flex align-items-center justify-content-center direttive">
                    <div class="w-25 bg-dark d-flex justify-content-center align-items-center h-100 text-warning" >
                        <i class="fa-solid fa-phone"></i>

                    </div>
                    <div class="w-75 border-start p-3 h-100">
                        <div class="h-100">
                            <span>Phone Numbers:</span>
                            <div class="text-white-50">+91 1234567898</div>
                        </div>

                    </div>

                </div>
                <div class="col-3 border p-0 d-flex align-items-center justify-content-center direttive">
                    <div class="w-25 bg-dark d-flex justify-content-center align-items-center h-100 text-warning">
                        <i class="fa-solid fa-envelope"></i>

                    </div>
                    <div class="w-75 border-start p-3 h-100">
                        <div class="h-100">
                            <span>Email:</span>
                            <div ><a class="text-white-50" href="">Demo@Example.Com</a></div>
                            <div class="text-white-50">Monday – Friday 10 AM – 8 PM</div>
                        </div>

                    </div>

                </div>
                

            </div>
            

        </div>

        <a href="" class="up text-white rounded-circle">
            ^

        </a>

        
    </div>
</template>

<style lang="scss" scoped>

#contact{
    position: relative;

    background-image: url('../assets/body-bg.jpg');
    .container{
        margin-top: 50px;
        margin-bottom: 50px;
        .message{
            height: 150px;
        }
        .direttive{
            height: 150px;
            margin-left: 25px;
            margin-bottom: 35px;
            width: 350px;
            a{
                text-decoration: none;
            }
        }
    }
    .up{
        position: fixed;
        background-color: rgb(208, 159, 24);
        display: inline;
        padding: 25px;
        bottom: 10px;
        right: 10px;
        text-decoration: none;
        

    }
    
}
</style>