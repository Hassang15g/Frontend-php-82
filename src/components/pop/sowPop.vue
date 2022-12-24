<template>
    
            <div  class="col">
        <div id="elzero-app" class="card-2">
            <ul class="list-group list-group-flush">
                <li class="list-group-item fw-bold text-info">What is the source of the virus? <span @click="show = !show" ><i class='bx bx-plus'></i></span> </li>
                    <div v-if="show" class="clck1">
                        <span @click="show = !show" ><i class='bx bx-minus'></i></span>
                            <h2 class="text-primary">What is the source of the virus?</h2>
                                <p>
                                    What is the source of the virus?
                                    Coronaviruses are a large family of viruses_ Some cause illness in people, and
                                    others, such as canine and feline coronaviruses; only infect animals. Rarely, animal
                                    coronaviruses that infect animals have   emerged to infect can spread
                                    between people.
                                  
                                </p>
                                <p>
                                This is suspected to have occurred for the virus that causes
                                COVID-19. Middle East Respiratory Syndrome (MERS) and Severe Acute
                                Respiratory Syndrome (SARS) are two other examples of coronaviruses that
                                originated from animals and then spread to people. More information about the
                                source and spread of COVID-19 is <span class="text-primary">available on the Situation Summary: Source and
                                Spread of the Virus.
                                </span> 
                                </p>
            </div>
<hr>
        <li class="list-group-item fw-bold text-success">How does the virus spread?
                <span @click="active = !active"><i class='bx bx-plus'></i></span>
            </li>
                <div v-show="active" class="clck1">
                    <span @click="active = !active" ><i class='bx bx-minus'></i></span>
                        <h2 class="text-primary">How does the virus spread?</h2>
                            <p>
                                
This virus was first detected in Wuhan City, Hubei Province, China. The first
infections were linked to a live animal market, but the virus is now spreading from
person-to-person. It's important to note that person-to-person spread can happen
on a continuum. Some viruses are highly contagious (like measles), while other
viruses are less so.
                            </p>
                            <p>
                            The virus that causes COVID-19 seems to be spreading easily and sustainably in
the community ("community spread") in some affected geographic areas.
Community spread means people have been infected with the virus in an area,
including some who are not sure how or where they became infected.
Learn what is known about the spread of newly emerged coronaviruses.
                            </p>
            </div>
<hr>
        <li class="list-group-item fw-bold text-success">Can someone who has had COVID-19 spread the illness to others? 
                <span @click="actives = !actives"><i class='bx bx-plus'></i></span>
            </li>
                <div v-show="actives" class="clck1">
                    <span @click="actives = !actives" ><i class='bx bx-minus'></i></span>
                        <h2 class="text-primary">Can someone who has had COVID-19 spread the illness to others?</h2>
                            <p>
                            The virus that causes COVID-19 is spreading from person-to-person. Someone
                            who is actively sick with COVID-19 can spread the illness to others_ That is why
                            CDC recommends that these patients be isolated either in the hospital or at home
                            (depending on how sick they are) until they are better and no longer pose a risk of
                            infecting others.
                            </p>
                        <p>
                        How long someone is actively sick can vary so the decision on when to release
                        someone from isolation is made on a case-by-case basis in consultation with
                        doctors, infection prevention and control experts, and public health officials and
                        involves considering specifics of each situation including disease severity, illness
                        </p>
                        <p>
                            signs and symptoms, and results of laboratory testing for that patient
                            Current CDC guidance for when it is 0K to release someone from isolation is made
                            on a case by case basis and includes meeting all of the following requirements.
                        </p>
                        <p>
                            The patient is free from fever without the use of fever-reducing medications.
                            The patient is no longer showing symptoms, including cough.
                            The patient has tested negative on at least two consecutive respiratory specimens
                            collected at least 24 hours apart
                        </p>
                        <p>
                            Someone who has been released from isolation is not considered to pose a risk of
                            infection to others.
                        </p>
                </div>
<hr>
                        <li class="list-group-item fw-bold text-success">Will warm weather stop the outbreak of COVID-19?
                            <span @click="activec = !activec"><i class='bx bx-plus'></i></span>
                            </li>
                            <div v-show="activec" class="clck1">
                                            <span @click="activec = !activec" ><i class='bx bx-minus'></i></span>
                                                <h2 class="text-primary">Will warm weather stop the outbreak of COVID-19?</h2>
                                                <p>
                                                    It is not yet known whether weather and temperature impact the spread of COVID-
                                                    19. Some other viruses, like the common cold and flu, spread more during cold
                                                    weather months but that does not mean it is impossible to become sick with these
                                                    viruses during other months. At this time, it is not known whether the spread of
                                                    COVID-19 will decrease when weather becomes warmer. There is much more to
                                                    learn about the transmissibility severity, and other features associated with COVID-
                                                    19 and investigations are ongoing

                                                </p>
                                                <p>
                                                        It is not yet known whether weather and temperature impact the spread of COVID-
                                                        19. Some other viruses, like the common cold and flu, spread more during cold
                                                        weather months but that does not mean it is impossible to become sick with these
                                                        viruses during other months. At this time, it is not known whether the spread of
                                                        COVID-19 will decrease when weather becomes warmer. There is much more to
                                                        learn about the transmissibility severity, and other features associated with COVID-
                                                        19 and investigations are ongoing

                                                </p>
                                            </div>
<hr>
            <li class="list-group-item fw-bold text-success">Can the virus that causes COVID-19 be spread through food including
                            refrigerated or frozen food? 
                    <span @click="box4 = !box4"><i class='bx bx-plus'></i></span>
                        </li>
                            <div v-show="box4" class="clck1">
                                            <span @click="box4 = !box4" ><i class='bx bx-minus'></i></span>
                                                <h2 class="text-primary">Can the virus that causes COVID-19 be
                                                        spread through food including
                                                        refrigerated or frozen food?
                                                </h2>
                                                <p>
                                                    Coronaviruses are generally thought to be spread from person-to-person through
                                                    respiratory droplets. Currently there is no evidence to support transmission of
                                                    COVID-19 associated with food. Before preparing or eating food it is important to
                                                    always wash your hands with soap and water for 20 seconds for general food
                                                    safety. Throughout the day wash your hands after blowing your nose, coughing or
                                                    sneezing or going to the bathroom.
                                                </p>
                                                <p>
                                                    It may be possible that a person can get COVID-19 by touching a surface or object
                                                    that has the virus on it and then touching their own mouth, nose, or possibly their
                                                    eyes, but this is not thought to be the main way the virus spreads.
                                                    In general, because of poor survivability of these coronaviruses on surfaces, there
                                                    is likely very low risk of spread from food products or packaging that are shipped
                                                    over a period of days or weeks at ambient, refrigerated, or frozen temperatures.
                                                    
                                                    </p>
                                                    <p class="text-primary">Learn what is known about the spread of COVID-19.</p>
                                            </div>
<hr>
                                            
                        <li class="list-group-item fw-bold text-success">What is community spread?
                            <span @click="box5 = !box5"><i class='bx bx-plus'></i></span>
                            </li>
                            <div v-show="box5" class="clck1">
                                            <span @click="box5 = !box5" ><i class='bx bx-minus'></i></span>
                                                <h2 class="text-primary">What is community spread?</h2>
                                                <p>
                                                    
                                                    Community spread means people have been infected with the virus in an area,
                                                    including some who are not sure how or where they became infected.
                                                </p>
                                               
                                            </div>

                                        
                                        </ul>
                                    </div>
                                </div> 
</template>



<script>
export default {
    name:'sowPop',
  data() {
    name:"Modal"
    return {
      show: false,
      active: true,
      actives:false,
      activec:false,
      box4:false,
      box5:false,

      
    }
  }
}
</script>

<style>
.card-2{
    padding: 10px;
    width: 50rem;
    margin-right: 20px;
    background: rgba( 255, 255, 255, 0.15 );
    box-shadow: 0 8px 32px 0 rgba( 31, 38, 135, 0.37 );
    backdrop-filter: blur( 2.5px );
    -webkit-backdrop-filter: blur( 2.5px );
    border-radius: 10px;
    border: 1px solid rgba( 255, 255, 255, 0.18 );
}
.card-2 h4{
    padding: 10px;
    border: solid 2px rgb(7, 115, 222);

}
.card-2 span i{
   padding-left: 45rem;
    font-size: 25px;
   
}
.card-2 span i:hover{
    color:#0f42e8;
}
.clck1 p{
    padding: 10px;
}
.clck1 h2{
    padding: 20px;
    font-size: 18px;
    font-weight: bold;
}
</style>