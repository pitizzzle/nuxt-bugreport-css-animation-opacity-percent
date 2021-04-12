### initial keyframes
```css
@keyframes test-animation {
  from { opacity: 0%; }
  to { opacity: 95%; }
}
```

<br>

### `nuxt dev` (script: `yarn start-dev`)
+ the css animation keyframes are still correct
+ ![chrome_phOeK4FcoF](https://user-images.githubusercontent.com/36761687/114428152-21504e00-9bbc-11eb-89bf-043eae940bee.png)

<br>

### `nuxt generate && nuxt start` (script: `yarn start-prod`)
+ the `to` keyframe becomes absurdly wrong xD
+ ![chrome_AtIZWIv7Ye](https://user-images.githubusercontent.com/36761687/114428176-290ff280-9bbc-11eb-84c4-c34f15d85a83.png)
