# vue-credit-card

### Vue.js credit card component

jessepollak's [Card](http://github.com/jessepollak/card) make credit card forms look awesome.
The vue-credit-card is a Vue.js component that aims to do the same for Vue.js(vue2.0)

### Usage

``npm i vue-credit-card``

then 

``import Card from 'vue-credit-card';``

add your component by using component attribute

You can use card component like that now:

``<card :value="{number, name, expiry, cvc}"></card>``

Also, don't forget to bind your form to this models... Also, you should give your input's name like that: name="cvc"


