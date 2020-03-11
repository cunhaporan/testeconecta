<template>
    <div>
        <div class="card" style="width: 50%;" v-for="contact in contacts" v-bind:key="contact">
            <img src="" class="card-img-top" alt="..."> 
            <div class="card-body">
                <h5 class="card-title">{{contact.name}}</h5>
                <p><strong>Telefone:</strong> {{contact.tell}}</p>
                <p><strong>Email:</strong> {{contact.email}}</p>
            </div> 
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            contacts: [
                {
                    name: 'Gamora',
                    tell: '999999999',
                    email: 'gamorita@gmail.com'
                },
                {
                    name: 'Remy',
                    tell: '999999999',
                    email: 'Remyzin@gmail.com'
                },
                {
                    name: 'Salem',
                    tell: '999999999',
                    email: 'salenzito@gmail.com'
                }
            ]
        }
    }
}
</script>


