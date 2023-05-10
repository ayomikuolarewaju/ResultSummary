<script> 
import img1 from '../img/icon-memory.svg';
import img2 from '../img/icon-reaction.svg';
import img3 from '../img/icon-visual.svg';
import img4 from '../img/icon-verbal.svg';


   
</script>


<div class="flex flex-col md:flex md:flex-row mx-auto my-auto items-center w-3/3 text-white md:pt-36">
    <div class="flex flex-col rounded-3xl bg-blue-800 items-center text-center p-10 w-2/3 h-3/3">
        <h5 class="text-white text-2xl font-bold m-2">Your Result</h5>
        <div class="flex flex-col m-2 rounded-full bg-blue-950 shadow-lg shadow-blue-700 text-white text-center p-10">
            <h6 class="text-3xl font-bold mb-1">76 </h6>
            <p>of 100</p>
        </div>
        
        <h6 class="text-white text-2xl font-bold m-5">Great</h6>
        <p class="m-4 w-2/3">Your score higher than 65% of people that have taken this test</p>

    </div>
    <div class="flex flex-col rounded-3xl bg-white w-2/3 h-3/3 p-10">
        <h5 class="text-black text-2xl font-bold m-2 text-left">Summary</h5>
        <div class="flex flex-col text-white mb-3 space-y-5">
            <div class = "flex flex-row rounded-md bg-red-100 p-3 justify-between">
                <div class="flex flex-row text-red-400 space-x-5">
                    <img src="{img2}" alt="" srcset="">
                    <p>Reaction</p>
                </div>
                <div class="flex flex-col text-black text-center">  
                    <p>80/100</p>
                </div>
            </div>
            <div class = "flex flex-row rounded-md bg-yellow-100 p-3 justify-between">
                <div class="flex flex-row text-yellow-400 space-x-5">
                    <img src="{img1}" alt="" srcset="">
                    <p>Memory</p>
                </div>
                <div class="flex flex-col text-black text-center">  
                    <p>92/100</p>
                </div>
            </div>
            <div class = "flex flex-row rounded-md bg-green-100 p-3 justify-between">
                <div class="flex flex-row text-green-400 space-x-5">
                    <img src="{img4}" alt="" srcset="">
                    <p>Verbal</p>
                </div>
                <div class="flex flex-col text-black text-center">  
                    <p>62/100</p>
                </div>
            </div>
            <div class = "flex flex-row rounded-md bg-blue-100 p-3 justify-between">
                <div class="flex flex-row text-blue-400 space-x-5">
                    <img src="{img3}" alt="" srcset="">
                    <p>Visual</p>
                </div>
                <div class="flex flex-col text-black text-center">  
                    <p>72/100</p>
                </div>
            </div>
            <div class = "flex flex-row rounded-lg bg-blue-800 p-3 text-center text-white items-center">
               <p>Continue</p>
            </div>
           
        </div>   

    </div>


</div>
