## Vue Interview Questions

1. VueJS, what are the advantages of using this framework when you work as a frontend developer?
2. Do you have any experience with VueX? What are the advantages of using VueX? What implementations have you used in your career as a VueJS Developer.

3. V If and V For Usage Issues

```
[vue/no-use-v-if-with-v-for]
The 'textModules' variable inside 'v-for' directive should be replaced with a computed property that returns filtered array instead. You should not mix 'v-for' with 'v-if'.
```

Explain in plain English what this issue is and how you would resolve this

4. What was a VueJS setup you made in the past that you would do differently today and how so?


5. `Elements in iteration expect to have 'v-bind:key' directives.eslintvue/require-v-for-key` referring to 

```html
<li v-for="(something, index) in someStructure" @mouseenter="mouseEntered(something)" @mouseleave="mouseLeft(something)" 
                :class="activePreset(something)" :style="level1Style(something, index)">`
```

How would you deal with this issue?

6. What are common VueJS Optimizations one can do in most applications you encountered? How so?
7.  How do you normally add docblocks to VueJS hooks and methods? Please share an example.