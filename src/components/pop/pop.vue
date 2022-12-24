<template>
    
            <div class="col">
        <div id="elzero-app" class="card-2">
            <ul class="list-group list-group-flush">
                <li class="list-group-item fw-bold">What is a novel coronavirus? <span @click="show = !show" ><i class='bx bx-plus'></i></span> </li>
                    <div v-if="show" class="clck1">
                        <span @click="show = !show" ><i class='bx bx-minus'></i></span>
                            <h2 class="text-primary">Why is the disease being called coronavirus disease 2019,COVID-19?</h2>
                                <p>
                                    On February 11: 2020 the World Health Organization announced atl official name
                                    for the disease that is causing the 2019 novel coronavirus outbreak, first identified
                                    in Wuhan China. The new name of this disease is coronavirus disease 2019,
                                    abbreviated as COVID-19_ In COVID-19, 'CO' stands for 'corona,' 'VI' for 'virus,' and
                                    'D' for disease. Formerly this disease was referred to as "2019 novel coronavirus"
                                    or "2019-ncoV".
                                </p>
                            <p>
                                    A novel coronavirus is a new coronavirus that has not been previously identified.
                                    The virus causing coronavirus disease 2019 (COVID-19), is not the same as the
                                    coronaviruses that commonly circulate among humans and cause mild illness, like
                                    the common cold.
                            </p>
            </div>
<hr>
        <li class="list-group-item fw-bold">Why is th disease being called called coronavirus disease 2019,COVID-19?
                <span @click="active = !active"><i class='bx bx-plus'></i></span>
            </li>
                <div v-show="active" class="clck1">
                    <span @click="active = !active" ><i class='bx bx-minus'></i></span>
                        <h2 class="text-primary">Why is the disease being called coronavirus disease 2019,COVID-19?</h2>
                            <p>
                               On February 11 , 2020 the World Health Organization announced an official name
                                    for the disease that is causing the 2019 novel coronavirus outbreak, first identified
                                    in Wuhan China. The new name of this disease is coronavirus disease 2019,
                                    abbreviated as COVID-19 In COVID-19, 'CO' stands for 'corona,' 'VI' for 'virus,' and
                                    'D' for disease. Formerly this disease was referred to as "2019 novel coronavirus"
                                    or "2019-nCoV'
                            </p>
                            <p>
                                There are many types of human coronaviruses including some that commonly
                                cause mild upper-respiratory tract illnesses_ COVID-19 is a new disease, caused
                                be a novel (or new) coronavirus that has not previously been seen in humans_ The
                                name of this disease was selected following the World Health Organization (WHO)
                                best practiceexternal icon for naming of new human infectious diseases
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
                                People can fight stigma and help, not hurt, others by providing social support
                                Counter stigma by learning and sharing facts. Communicating the facts that viruses
                                do not target specific racial or ethnic groups and how COVID-19 actually spreads
                                can help stop stigma.
                            </p>
                        <p>
                           People can fight stigma and help, not hurt, others by providing social support
                                Counter stigma by learning and sharing facts. Communicating the facts that viruses
                                do not target specific racial or ethnic groups and how COVID-19 actually spreads
                                can help stop stigma.
                        </p>
                </div>
<hr>
                        <li class="list-group-item fw-bold">Why might someone blame or avoid individuals and groups? 
                            <span @click="activec = !activec"><i class='bx bx-plus'></i></span>
                            </li>
                            <div v-show="activec" class="clck1">
                                            <span @click="activec = !activec" ><i class='bx bx-minus'></i></span>
                                                <h2 class="text-primary">Why is the disease being called coronavirus disease 2019,COVID-19?</h2>
                                                <p>People in the U.S. may be worried or anxious about friends and relatives who are
                                                    living in or visiting areas where COVID-19 is spreading. Some people are worried
                                                    about the disease. Fear and anxiety can lead to social stigma, for example, towards
                                                    Chinese or other Asian Americans or people who were in quarantine.</p>

                                                <p>Stigma is discrimination against an identifiable group of people, a place, or a
                                                    nation. Stigma is associated with a lack of knowledge about how COVID-19
                                                    spreads: a need to blame someone, fears about disease and death, and gossip
                                                    that spreads rumors and myths.
                                                    </p>

                                                <p>Stigma hurts everyone by creating more fear or anger towards ordinary people
                                                    instead of the disease that is causing the problem.
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