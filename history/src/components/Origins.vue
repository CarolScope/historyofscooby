<template>
    <section id="history">
        <div class="flex justify-center mt-10">
            <div id="container" class="w-10/12 rounded-lg pb-10 mt-5 mr-4 flex justify-center items-center bg-sd-green h-550">
                <input hidden type="radio" name="carousel-navigation" id="first-button" checked>
                <input hidden type="radio" name="carousel-navigation" id="second-button">
                <input hidden type="radio" name="carousel-navigation" id="third-button">         
                
                <div class="carousel overflow-hidden w-11/12 h-full text-white font-bold">
                    <div class="slides relative ease-in-out duration-500 w-full h-full">
                        <section class="first-slide overflow-hidden relative px-10 pt-16 pb-10 w-inherit h-inherit">
                            <p class="mt-5 font-bold text-white text-3xl pb-2">Origins</p>
                            <p class="mt-1 font-bold text-white z-0">It all began in 1968 when parent-run organizations, particularly Action for 
                            Children's Television (ACT), began protesting what they perceived as excessive violence in Saturday-morning 
                            cartoons. Most of these shows were Hanna-Barbera action cartoons such as <span class="img-text font-black text-purple-400 cursor-pointer">Space Ghost<img alt="Space Ghost" class="z-10 hidden absolute border-4 border-purple-400 rounded-lg -mt-5 w-48 h-48" src="@/assets/img/slides/space_ghost.jpg"></span>, <span class="img-text font-black text-purple-400 cursor-pointer">The Herculoids<img alt="The Herculoids" class="z-10 hidden absolute border-4 border-purple-400 rounded-lg -mt-5 w-48 h-48 ml-20" src="@/assets/img/slides/the_herculoids.jpg"></span>, and 
                            <span class="img-text font-black text-purple-400 cursor-pointer">Birdman and the Galaxy Trio<img alt="Birdman and the Galaxy Trio" class="z-10 hidden absolute border-4 border-purple-400 rounded-lg -mt-5 w-48 h-48 ml-64" src="@/assets/img/slides/birdman_and_the_galaxy_trio.jpg"></span>, in the end all of them were canceled by 1969 by pressure from the parent 
                            groups. Members of these watchgroups served as advisers to <span class="img-text font-black text-purple-400 cursor-pointer">Hanna-Barbera<img alt="Hanna-Barbera" style="margin-left: 480px;" class="z-10 hidden absolute border-4 border-purple-400 rounded-lg -mt-5 w-48 h-48 float-right" src="@/assets/img/slides/hanna_barbera.jpg"></span> and other animation studios to ensure 
                            that new programs would be suitable for children.</p>
                            <p class="mt-2 font-bold text-white"><span class="img-text font-black text-purple-400 cursor-pointer">Fred Silverman<img alt="Fred Silverman" class="z-10 hidden absolute border-4 border-purple-400 rounded-lg -mt-5 w-48 h-48" src="@/assets/img/slides/fred_silverman.jpg"></span>, executive for daytime programming at CBS, was then looking for a
                            show that would both revitalize his Saturday-morning line and please the watch groups. The result was <span class="img-text font-black text-purple-400 cursor-pointer">The Archie Show<img alt="The Archie Show" style="margin-left: 400px;" class="z-10 hidden absolute border-4 border-purple-400 rounded-lg -mt-5 w-48 h-48" src="@/assets/img/slides/the_archie_show.jpg"></span>,
                            based on Bob Montana's teenage humor comic book <span class="img-text font-black text-purple-400 cursor-pointer">Archie<img alt="Archie" class="z-10 hidden absolute border-4 border-purple-400 rounded-lg -mt-5 w-48 h-48" src="@/assets/img/slides/archie.jpg"></span>. Also successful were the musical numbers <span class="img-text font-black text-purple-400 cursor-pointer">The Archies<img alt="The Archies" style="margin-left: 320px;" class="z-10 hidden absolute border-4 border-purple-400 rounded-lg -mt-5 w-48 h-48" src="@/assets/img/slides/the_archies.jpg"></span> performed
                            during each program (one of which, "Sugar, Sugar", was the most successful Billboard number-one hit of 1969). Eager to
                            build upon this success, Silverman contacted producers William Hanna and Joseph Barbera about creating another show
                            based on a teenage rock group, this time featuring teens who solved mysteries between gigs. Silverman envisioned the 
                            show as a cross between the popular <span class="img-text font-black text-purple-400 cursor-pointer">I Love a Mystery<img alt="I Love a Mystery" style="margin-left: 600px;" class="z-10 hidden absolute border-4 border-purple-400 rounded-lg -mt-48 w-48 h-48" src="@/assets/img/slides/iloveamystery.jpeg"></span> radio serials of the 1940s and either the Archie characters or the 
                            popular early 1960s television series <span class="img-text font-black text-purple-400 cursor-pointer">The Many Loves of Dobie Gillis<img alt="The Many Loves of Dobie Gillis" style="margin-left: 750px;" class="z-10 hidden absolute border-4 border-purple-400 rounded-lg -mt-24 w-64 h-48" src="@/assets/img/slides/dobie_gillis_cast.jpg"></span>.</p>
                        </section>
                                
                        <section class="second-slide overflow-hidden relative px-10 pt-20 pb-10 w-inherit h-inherit">
                            <p class="mt-1 font-bold text-white">After attempting to develop his own version of the show, called House of Mystery,
                            <span class="img-text font-black text-purple-400 cursor-pointer">Joseph Barbera<img alt="Joseph Barbera" style="margin-left: 570px;" class="z-10 hidden absolute border-4 border-purple-400 rounded-lg -mt-5 w-48 h-48" src="@/assets/img/slides/joseph_barbera.jpg"></span>, who developed and sold Hanna-Barbera shows while <span class="img-text font-black text-purple-400 cursor-pointer">William Hanna<img alt="William Hanna" class="z-10 hidden absolute border-4 border-purple-400 rounded-lg -mt-5 w-48 h-48 ml-32" src="@/assets/img/slides/william_hanna.jpg"></span> produced them, passed the task along to storywriters 
                            <span class="img-text font-black text-purple-400 cursor-pointer">Joe Ruby<img alt="Joe Ruby" style="margin-left: 550px;" class="z-10 hidden absolute border-4 border-purple-400 rounded-lg -mt-5 w-48 h-48" src="@/assets/img/slides/joe_ruby.jpg"></span> and <span class="img-text font-black text-purple-400 cursor-pointer">Ken Spears<img alt="Ken Spears" style="margin-left: 750px;" class="z-10 hidden absolute border-4 border-purple-400 rounded-lg -mt-5 w-48 h-48" src="@/assets/img/slides/ken_spears.jpg"></span>, as well as artist/character designer <span class="img-text font-black text-purple-400 cursor-pointer">Iwao Takamoto<img alt="Iwao Takamoto" class="z-10 hidden absolute border-4 border-purple-400 rounded-lg -mt-5 w-56 h-48 ml-40" src="@/assets/img/slides/iwao_takamoto.jpg"></span>. Their treatment, based in part on The Archie 
                            Show, was titled Mysteries Five and featured five teenagers: Geoff, Mike, Kelly, Linda, and Linda's brother W.W., along 
                            with their bongo-playing dog, Too Much, who collectively formed the band Mysteries Five. When The Mysteries Five were not 
                            performing at gigs, they were out solving spooky mysteries involving ghosts, zombies, and other supernatural creatures. 
                            Ruby and Spears were unable to decide whether Too Much would be a large cowardly dog or a small feisty one. When the 
                            former was chosen, Ruby and Spears wrote Too Much as a <span class="img-text font-black text-purple-400 cursor-pointer">Great Dane<img alt="Great Dane" style="margin-left: 750px;" class="z-10 hidden absolute border-4 border-purple-400 rounded-lg -mt-5 w-48 h-48" src="@/assets/img/slides/great_dane.jpg"></span> but revised the dog character to a large <span class="img-text font-black text-purple-400 cursor-pointer">sheepdog<img alt="sheepdog" class="z-10 hidden absolute border-4 border-purple-400 rounded-lg -mt-5 w-56 h-48 ml-40" src="@/assets/img/slides/sheepdog.jpg"></span> 
                            (similar to the Archies' sheepdog, <span class="img-text font-black text-purple-400 cursor-pointer">Hot Dog<img alt="Hot Dog" style="margin-left: 470px;" class="z-10 hidden absolute border-4 border-purple-400 rounded-lg -mt-5 w-56 h-48" src="@/assets/img/slides/hot_dog.jpg"></span>) just before their presentation to Silverman, as Ruby feared the character 
                            would be too similar to the comic strip character Marmaduke. Silverman rejected their initial pitch, and after 
                            consulting with Barbera on next steps, got Barbera's permission to go ahead with Too Much being a Great Dane instead 
                            of a sheepdog.</p>
                            <p class="mt-2 font-bold text-white">During the design phase, lead character designer Takamoto consulted a studio 
                                colleague who was a breeder of Great Danes. After learning the characteristics of a prize-winning Great Dane from 
                                her, Takamoto proceeded to break most of the rules and designed Too Much with overly bowed legs, a double chin, 
                                and a sloped back, among other abnormalities.</p>
                        </section>
                                
                        <section class="third-slide overflow-hidden relative p-10 w-inherit h-inherit">
                            <p class="mt-1 font-bold text-white">Ruby and Spears' second pass at the show used Dobie Gillis as the template 
                            for the teenagers rather than Archie. The treatment retained the dog Too Much, while reducing the number of 
                            teenagers to four, removing the Mike character and retaining Geoff, Kelly, Linda, and W.W. As their personalities
                            were modified, so were the characters' names: Geoff became "Ronnie" – later renamed "Fred" (at Silverman's behest),
                            Kelly became "Daphne", Linda "Velma", and W.W. "Shaggy". The teens were now based on four teenage characters from
                            The Many Loves of Dobie Gillis: <span class="img-text font-black text-purple-400 cursor-pointer">Dobie Gillis (Dwayne Hickman)<img alt="Dobie Gillis" style="margin-left: 400px;" class="z-10 hidden absolute border-4 border-purple-400 rounded-lg -mt-5 w-56 h-48" src="@/assets/img/slides/dobie.jpg"></span>, <span class="img-text font-black text-purple-400 cursor-pointer">Thalia Menninger(Tuesday Weld)<img alt="Thalia Menninger" style="margin-left: 580px;" class="z-10 hidden absolute border-4 border-purple-400 rounded-lg -mt-5 w-48 h-48" src="@/assets/img/slides/thalia_menninger.jpg"></span>, <span class="img-text font-black text-purple-400 cursor-pointer">Zelda Gilroy (Sheila James)<img alt="Zelda Gilroy" class="z-10 hidden absolute border-4 border-purple-400 rounded-lg -mt-5 w-48 h-48 -ml-5" src="@/assets/img/slides/zelda.jpg"></span> 
                            and <span class="img-text font-black text-purple-400 cursor-pointer">Maynard G. Krebs (Bob Denver)<img alt="Maynard G. Krebs" class="z-10 hidden absolute border-4 border-purple-400 rounded-lg -mt-5 w-48 h-48 ml-40" src="@/assets/img/slides/maynard.jpg"></span>, respectively.
                            </p>
                            <p class="mt-2 font-bold text-white">The revised show was re-pitched to Silverman, who liked the material but, disliking the title Mysteries Five, 
                            decided to call the show Who's S-S-Scared? Silverman presented Who's S-S-Scared? to the CBS executives as the
                            centerpiece for the upcoming 1969–70 season's Saturday morning cartoon block. CBS president <span class="img-text font-black text-purple-400 cursor-pointer">Frank Stanton<img alt="Frank Stanton" style="margin-left: 380px;" class="z-10 hidden absolute border-4 border-purple-400 rounded-lg -mt-5 w-64 h-48" src="@/assets/img/slides/frank_stanton.jpg"></span> felt 
                            that the presentation artwork was too scary for young viewers and, thinking the show would be the same, decided 
                            to pass on it.</p>
                            <p class="mt-2 font-bold text-white">Now without a centerpiece for the upcoming season's programming, Silverman 
                            had Ruby, Spears, and the Hanna-Barbera staff revise the treatments and presentation materials to tone down the 
                            show and better reflect its comedy elements. The rock band element was dropped, and more attention was focused 
                            upon Shaggy and Too Much. According to Ruby and Spears, Silverman was inspired by <span class="img-text font-black text-purple-400 cursor-pointer">Frank Sinatra's<img alt="Frank Sinatra" class="z-10 hidden absolute border-4 border-purple-400 rounded-lg -mt-32 w-48 h-48" src="@/assets/img/slides/frank_sinatra.jpg"></span> scat 
                            "doo-be-doo-be-doo" at the end of his recording of "Strangers in the Night" on a red-eye flight to one of the 
                            development meetings, and decided to rename the dog "Scooby-Doo" and retitled the show Scooby-Doo, Where Are You! 
                            The revised show was re-presented to CBS executives, who approved it for production.</p>
                        </section>
                    </div>
                </div>           

                <div id="navigation" class="flex-initial block mt-10">
                    <label for="first-button" class="transition-all ease-linear duration-300 block">
                        <span @click="firstCircle()" class="first-circle cursor-pointer rounded-full h-3 w-3 mr-6 mb-5 bg-purple-500 hover:bg-purple-500 border-2 border-purple-500 float-right flex items-center justify-center"></span> 
                    </label>
                    <label for="second-button" class="transition-all ease-linear duration-300 block">
                        <span @click="secondCircle()" class="second-circle cursor-pointer rounded-full h-3 w-3 mr-6 mb-5 bg-purple-400 hover:bg-purple-500 border-2 border-purple-500 float-right flex items-center justify-center"></span>
                    </label>
                    <label for="third-button" class="transition-all ease-linear duration-300 block">
                        <span @click="thirdCircle()" class="third-circle cursor-pointer rounded-full h-3 w-3 mr-6 bg-purple-400 hover:bg-purple-500 border-2 border-purple-500 float-right flex items-center justify-center"></span>
                    </label>
                </div>              
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Origins',
    methods: {
        firstCircle: function() {
            document.querySelector('.first-circle').classList.remove('bg-purple-400')
            document.querySelector('.first-circle').classList.add('bg-purple-500')

            document.querySelector('.second-circle').classList.add('bg-purple-400')
            document.querySelector('.second-circle').classList.remove('bg-purple-500')

            document.querySelector('.third-circle').classList.add('bg-purple-400')
            document.querySelector('.third-circle').classList.remove('bg-purple-500')
        },
        secondCircle: function() {
            document.querySelector('.first-circle').classList.add('bg-purple-400')
            document.querySelector('.first-circle').classList.remove('bg-purple-500')

            document.querySelector('.second-circle').classList.remove('bg-purple-400')
            document.querySelector('.second-circle').classList.add('bg-purple-500')

            document.querySelector('.third-circle').classList.add('bg-purple-400')
            document.querySelector('.third-circle').classList.remove('bg-purple-500')
        },
        thirdCircle: function() {
            document.querySelector('.first-circle').classList.add('bg-purple-400')
            document.querySelector('.first-circle').classList.remove('bg-purple-500')

            document.querySelector('.second-circle').classList.add('bg-purple-400')
            document.querySelector('.second-circle').classList.remove('bg-purple-500')

            document.querySelector('.third-circle').classList.remove('bg-purple-400')
            document.querySelector('.third-circle').classList.add('bg-purple-500')
        }
    }
}
</script>

<style scoped>
    #first-button:checked ~ .carousel .slides {
        -webkit-transform: translateY(0);
        transform: translateY(0); 
    }
                
    #second-button:checked ~ .carousel .slides {
        -webkit-transform: translateY(-100%);
        transform: translateY(-100%); 
    }

    #third-button:checked ~ .carousel .slides {
        -webkit-transform: translateY(-200%);
        transform: translateY(-200%); 
    }
</style>