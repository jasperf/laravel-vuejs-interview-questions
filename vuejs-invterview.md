Here a few questions to get started

1. Do you have any experience with VueX? What are the advantages of using VueX? What implementations have you used in your career as a VueJS Developer

2. V If and V For Usage Issues

```
[vue/no-use-v-if-with-v-for]
The 'textModules' variable inside 'v-for' directive should be replaced with a computed property that returns filtered array instead. You should not mix 'v-for' with 'v-if'.
```

3. Explain in plain English what this issue is and how you would resolve this

4. What was a VueJS setup you made in the past that you would do differently today and how so?


5. `Elements in iteration expect to have 'v-bind:key' directives.eslintvue/require-v-for-key` referring to 

```html
<li v-for="(something, index) in someStructure" @mouseenter="mouseEntered(something)" @mouseleave="mouseLeft(something)" 
                :class="activePreset(something)" :style="level1Style(something, index)">`
```

Explain in plain English what this means and What to do?

6. What are common VueJS Optimizations one can do in most applications you encountered? How so?