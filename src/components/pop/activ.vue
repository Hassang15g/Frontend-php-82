<template>
     <div  class="col">
        <div id="elzero-app" class="card-2">
            <ul class="list-group list-group-flush">
                <li class="list-group-item fw-bold">What can I do to protect myself and prevent the spread of disease? <span @click="show = !show" ><i class='bx bx-plus'></i></span> </li>
                    <div v-if="show" class="clck1">
                        <span @click="show = !show" ><i class='bx bx-minus'></i></span>
                            <h2 class="text-primary">Protection measures for everyone
                            </h2>
                                <p>
                                    Household members, intimate partners, and caregivers in a nonhealthcare setting
may have close contact2 with a person with symptomatic; laboratory-confirmed
COVID-19 or a person under investigation. Close contacts should monitor their
health, they should call their healthcare provider right away if they develop
symptoms suggestive of COVID-19 (e.g., fever, cough, shortness of breath)
Close contacts should also follow these recommendations:
                                </p>
                                <p>
                                        • Regularly and thoroughly clean your hands with an alcohol&sed hand rub or
                                        wash them with soap and water
                                        Why? Washing your hands with soap and water or using alcohol-based hand
                                        rub kills viruses that may be on your hands
                                </p>
                                <p>
                                    Why? Washing your hands with soap and water or using alcohol-based hand
                                    rub kills viruses that may be on your hands
                                </p>
                                <p>
                                    • Maintain at least 1 metre (3 feet) distance between yourself and anyone who is
                                            coughing or sneezing.
                                </p>
                                <p>
                                    Why? When someone coughs or sneezes they spray small liquid droplets from
their nose or mouth which may contain virus. If you are too close, you can
breathe in the droplets, including the COVID-19 virus if the person coughing has
the disease.
• Avoid touching eyes, nose and mouth.
</p>
<p>
    Why? Hands touch many surfaces and can pick up viruses. Once contaminated,
hands can transfer the virus to your eyes, nose or mouth. From there, the virus
can enter your body and can make you sick.
</p>
<p>
    • Make sure you, and the people around you, follow good respiratory hygiene.
This means covering your mouth and nose with your bent elbow or tissue when
you cough or sneeze. Then dispose of the used tissue immediately.
Why? Droplets spread virus. By following good respiratory hygiene you protect
the people around you from viruses such as cold, flu and COVID-I g.
</p>
<p>
• Stay home if you feel unwell. If you have a fever, cough and difficulty breathing:
seek medical attention and call in advance. Follow the directions of your local
health authority 
</p>

                                
            </div>
<hr>
        <li class="list-group-item fw-bold">What should I do if I had close contact with someone who has COVID-19?
                <span @click="active = !active"><i class='bx bx-plus'></i></span>
            </li>
                <div v-show="active" class="clck1">
                    <span @click="active = !active" ><i class='bx bx-minus'></i></span>
                        <h2 class="text-primary">Protection measures for everyone</h2>
                        
                            <p>
                              Household members, intimate partners, and caregivers in a nonhealthcare setting
may have close contact2 with a person with symptomatic, laboratory-confirmed
COVID-19 or a person under investigation. Close contacts should monitor their
health; they should call their healthcare provider right away if they develop
symptoms suggestive of COVID-19 (e.g., fever, cough, shortness of breath)
Close contacts should also follow these recommendations:
• Make sure that you understand and can help the patient follow their healthcare
provider's instructions for medication(s) and care. You should help the patient
with basic needs in the home and provide support for getting groceries,
prescriptions, and other personal needs.
                            </p>
                            <p>
                                • Monitor the patient's symptoms. If the patient is getting sicker, call his or her
healthcare provider and tell them that the patient has laboratory-confirmed
COVID-19. This will help the healthcare provider's office take steps to keep other
people in the office or waiting room from getting infected. Ask the healthcare
provider to call the local or state health department for additional guidance. If the
                    </p>
                    <p>
                        • Monitor the patient's symptoms. If the patient is getting sicker, call his or her
healthcare provider and tell them that the patient has laboratory-confirmed
COVID-19. This will help the healthcare provider's office take steps to keep other
people in the office or waiting room from getting infected. Ask the healthcare
provider to call the local or state health department for additional guidance. If the

                    </p>
                    <p>
                        • Monitor the patient's symptoms. If the patient is getting sicker, call his or her
healthcare provider and tell them that the patient has laboratory-confirmed
COVID-19. This will help the healthcare provider's office take steps to keep other
people in the office or waiting room from getting infected. Ask the healthcare
provider to call the local or state health department for additional guidance. If the
                    </p>
            </div>
<hr>
        <li class="list-group-item fw-bold">How can people help stop stigma related to COVID-19? 
                <span @click="actives = !actives"><i class='bx bx-plus'></i></span>
            </li>
                <div v-show="actives" class="clck1">
                    <span @click="actives = !actives" ><i class='bx bx-minus'></i></span>
                        <h2 class="text-primary">Why is the disease being called coronavirus disease 2019,COVID-19?</h2>
                            <p>
                                Lorem, ipsum dolor sit amet consectetur adipisicing elit. 
                                Qui inventore neque voluptatum vel libero. Maxime, molestiae saepe tenetur eius itaque maiores
                                quidem laborum aliquam fuga ipsa repellendus culpa eveniet corporis!
                            </p>
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ratione repellendus 
                            id inventore fuga, eaque eius sed. A qui provident esse vel aperiam laborum? Eligendi
                            eos voluptatum voluptates inventore porro ducimus.
                        </p>
                </div>
<hr>
                        <li class="list-group-item fw-bold">Why might someone blame or avoid individuals and groups? 
                            <span @click="activec = !activec"><i class='bx bx-plus'></i></span>
                            </li>
                            <div v-show="activec" class="clck1">
                                            <span @click="activec = !activec" ><i class='bx bx-minus'></i></span>
                                                <h2 class="text-primary">Why is the disease being called coronavirus disease 2019,COVID-19?</h2>
                                                <p>
                                                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. 
                                                    Qui inventore neque voluptatum vel libero. Maxime, molestiae saepe tenetur eius itaque maiores
                                                    quidem laborum aliquam fuga ipsa repellendus culpa eveniet corporis!
                                                </p>
                                                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ratione repellendus 
                                                id inventore fuga, eaque eius sed. A qui provident esse vel aperiam laborum? Eligendi
                                                eos voluptatum voluptates inventore porro ducimus.
                                                </p>
                                            </div>
                                        </ul>
                                    </div>
                                </div> 
</template>



<script>
export default {
    name:'pop',
  data() {
    name:"Modal"
    return {
      show: false,
      active: true,
      actives:false,
      activec:false,
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