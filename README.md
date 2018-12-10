# Vattenfall-Example-Project

## Step 1

Setup a new Yarn project with 

```sh
yarn init
```

Install the Horizon design system by running

```sh
yarn add @vf-alchemy/vattenfall-design-system
```

Create a new [index.html](./index.html) and fill it with the content from the link.

Open the page in your browser:
```sh
open index.html
```

Great, that should now show a page with a headline using the Horizon title font.

## Step 2 

Now let's add a component!

Open up the component library documentation in your browser. http://vattenfall.alchemystudio.se/

Find the `Button` component under the `CSS Library` section.

Show the source code for the button component, and pick one you prefer, copy and paste the code.
For example:
```html
<button type="button" class="vf-btn vf-btn--lg vf-btn--primary">Yellow button</button>
```

Paste the code into your [index.html](./index.html) after the `<h1>` tag.
