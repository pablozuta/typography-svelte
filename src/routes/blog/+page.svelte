 <center><h1>Blog</h1></center>
<div class="dos-parrafos">
    <div>
      <h3>What is SvelteKit?</h3>
      <p class="dos-parrafos-texto">SvelteKit is a framework for building extremely high-performance web apps.

        Building an app with all the modern best practices is fiendishly complicated. Those practices include build optimizations, so that you load only the minimal required code; offline support; prefetching pages before the user initiates navigation; and configurable rendering that allows you to render your app on the server or in the browser at runtime or at build-time. SvelteKit does all the boring stuff for you so that you can get on with the creative part.
        
        It uses Vite with a Svelte plugin to provide a lightning-fast and feature-rich development experience with Hot Module Replacement (HMR), where changes to your code are reflected in the browser instantly.
        
        You don't need to know Svelte to understand the rest of this guide, but it will help. In short, it's a UI framework that compiles your components to highly optimized vanilla JavaScript. Read the introduction to Svelte blog post and the Svelte tutorial to learn more.</p>
    </div>
    <div>
        <h3>Accessibility</h3>
      <p class="dos-parrafos-texto">SvelteKit strives to provide an accessible platform for your app by default. Svelte's compile-time accessibility checks will also apply to any SvelteKit application you build.

        Here's how SvelteKit's built-in accessibility features work and what you need to do to help these features to work as well as possible. Keep in mind that while SvelteKit provides an accessible foundation, you are still responsible for making sure your application code is accessible. If you're new to accessibility, see the "further reading" section of this guide for additional resources.
        
        We recognize that accessibility can be hard to get right. If you want to suggest improvements to how SvelteKit handles accessibility, please open a GitHub issue.</p>
    </div>
  
  </div>
<br>
  <center><a class="link-button" href="/">Back to Home</a></center>
  <br>
  <br>

  <style>

    h1{
        letter-spacing: 0.3rem; 
    }
    h3{
        font-family: 'Arapey', serif;
        margin-inline: 3%;
        font-size: 2rem;
        letter-spacing: 0.3rem;
    }

    .dos-parrafos {
    font-family: 'Playfair Display', serif;
    text-align: left;
    text-justify: auto;
    padding-inline: 2%;
    color: black;
    font-size: 1rem;
    display: grid;
    grid-gap: 35px;
    margin-inline: 3%;
    grid-template-columns: repeat(auto-fit, minmax(19rem, 0.5fr));
  }
  
  .dos-parrafos-texto {
    font-size: 1.2rem;
    line-height: 120%;
    padding-inline: 3%;
    font-weight: 500;
    width: auto;
  }

  .link-button{
    text-decoration: none;
    background-color: black;
    color: white;
    padding: 1rem;
    padding-inline: 3rem;
    border-radius: 5%;         
}
a:hover{
        color: coral;
    }
  </style>