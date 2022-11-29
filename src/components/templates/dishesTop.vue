<template>
<div class="salaty">Салаты
    <div class="menu-block">
        <div v-for="p of pictures" :key="p.id" class="bludo-block">
            <div class="name">{{p.title}}</div>
             <div class="image-blok">
                <img :src="`image/${p.image}`"/>
            </div>
            <div class="recept">
                {{p.description}}
            </div>
        </div> 
       <!-- <div class="bludo-block">
            <div class="name">Приморский салат с мятым лососем</div>
            <div class="image-blok">
                <img src="image/sal2.png"/>
            </div>
            <div class="recept">
                340 г • Мятое филе лосося с сыром, огурцы маринованные, микс салата, 
                картофель отварной, заправка соевая, 22 руб.
            </div>
        </div> 
        <div class="bludo-block">
            <div class="name">Теплый салат с домашними овощами и говядиной</div>
            <div class="image-blok">
                <img src="image/sal3.png"/>
            </div>
            <div class="recept">
                350 г • Говядина, свекла, перец сладкий, грибы, кабачок, 
                баклажан, сыр Пармезан, тыквенная заправка, 23 руб.
            </div>
        </div> 
        <div class="bludo-block">
            <div class="name">Цезарь по-литовски с курочкой</div>
            <div class="image-blok">
                <img src="image/sal4.png"/>
            </div>
            <div class="recept">
                380 г • Куриное филе, салат ромен, черри, яйцо, чипсы из бекона, 
                грудинка, сыр пармезан, ржаные чипсы, соус Цезарь, 17 руб.
            </div>
        </div> 
    </div>
</div>
<div>Горячие блюда</div>
    <div class="menu-block2">
        <div class="bludo-block">
            <div class="name"></div>
            <div class="image-blok">
                <img src="image/gor5.png"/>
            </div>
            <div class="recept">
                Карка по-литовски (рулька свиная),100 г • Если вы взяли рульку 
                больше 800 г — гарнир к ней за 1 коп.,5 руб.
            </div>
        </div> 
        <div class="bludo-block">
            <div class="name"></div>
            <div class="image-blok">
                <img src="image/gor6.png"/>
            </div>
            <div class="recept">
                Бабка по-домашнему
            600 г • Картофель, лук, грудинка, специи, сметана, 14 руб.
            </div>
        </div> 
        <div class="bludo-block">
            <div class="name"></div>
            <div class="image-blok">
                <img src="image/gor7.png"/>
            </div>
            <div class="recept">
                Стейк из вырезки с хрустящими овощами,270 г • Говяжья вырезка, микс из свежих 
                овощей, соус перечный, 28 руб.
            </div>
        </div> 
        <div class="bludo-block">
            <div class="name"></div>
            <div class="image-blok">
                <img src="image/gor8.png"/>
            </div>
            <div class="recept">
                Жаркое из судака
            450 г • Филе судака, кабачок, баклажан, грибы, мини морковь,
            базилик, соус, горошек зеленый,23 руб.
            </div>
        -->
        </div>
    </div>
    

</template>


<script setup>

const pictures = [
      {id: 1, image: "sal.png", title: "Овощной салат с мягким домашним сыром", description: "Помидор св., огурец св., перец сладкий св., лук красный св., маслины, сыр домашний, заправка, 350г., 15руб."},
      {id: 2, image: "sal2.png", title: "Приморский салат с мятым лососем", description: "Мятое филе лосося с сыром, огурцы маринованные, микс салата, картофель отварной, заправка соевая,340г., 22 руб. "},
      {id: 3, image: "sal3.png", title: "Теплый салат с домашними овощами и говядиной", description: "Говядина, свекла, перец сладкий, грибы, кабачок, баклажан, сыр Пармезан, тыквенная заправка, 350г., 23 руб. "},
      {id: 4, image: "sal4.png", title: "Цезарь по-литовски с курочкой", description: "Куриное филе, салат ромен, черри, яйцо, чипсы из бекона, грудинка, сыр пармезан, ржаные чипсы, соус Цезарь, 350г., 17 руб."},
      {id: 5, image: "gor5.png", title: "Карка по-литовски", description: "Рулька свиная 100г. и гарнир к ней за 1 коп., 5руб."},
      {id: 6, image: "gor6.png", title: "Бабка по-домашнему", description: "Картофель, лук, грудинка, специи, сметана,600г., 14 руб."},
      {id: 7, image: "gor7.png", title: "Стейк", description: "Говяжья вырезка, микс из свежих овощей, соус перечный, 270г., 28 руб."},
      {id: 8, image: "gor8.png", title: "Жаркое", description: "Филе судака, кабачок, баклажан, грибы, мини морковь, базилик, соус, горошек зеленый, 450г., 23 руб. "},
      
      
    ];
</script>