# A simple reveal.js based image carousel hosted by GitHub pages

### 1. Create a new repository using this template 

### 2. Update `index.html` 

Locate the following line

https://github.com/agahkarakuzu/carousel/blob/7a71f9bf80d447d7557cb5dc2f71871fdbbef956/index.html#L33

and update it with the new `owner/repo`

```diff
- img.src = `https://raw.githubusercontent.com/agahkarakuzu/carousel/refs/heads/main/img/${fileName}`;
+ img.src = `https://raw.githubusercontent.com/{{NEW_GITHUB_OWNER}}/{{NEW_REPO_NAME}}/refs/heads/main/img/${fileName}`;
```

### 3. Add new images under the `img` folder

### 4. Update `images.json` 

To contain the list of new images, pay attention to the image extensions. Images will appear in the order you provided in this file:

```json
[
"my_new_image.png",
"my_new_image_2.jpg"
]
```

### 5. Repository settings

* Make sure that the pages are enabled with GitHub actions, using the "static website" template.

### That's it 

Your image carousel should be available at `https://{{NEW_GITHUB_OWNER}}.github.io/{{NEW_REPO_NAME}}`
