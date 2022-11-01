<h1>Svelte 3: Rethinking reactivity</h1>
<p>It's finally here</p>
<hr>
<br>
<p>After several months of being just days away, we are over the moon to announce the stable release of Svelte 3. This is a huge release representing hundreds of hours of work by many people in the Svelte community, including invaluable feedback from beta testers who have helped shape the design every step of the way.</p>
<p>We think you're going to love it.</p>
<h3>What is Svelte?</h3>
<p>Svelte is a component framework — like React or Vue — but with an important difference. Traditional frameworks allow you to write declarative state-driven code, but there's a penalty: the browser must do extra work to convert those declarative structures into DOM operations, using techniques like <a href="https://svelte.dev/blog/virtual-dom-is-pure-overhead">virtual DOM diffing</a>   that eat into your frame budget and tax the garbage collector.</p>

<p>Instead, Svelte runs at build time, converting your components into <strong>highly efficient</strong>  imperative code that surgically updates the DOM. As a result, you're able to write ambitious applications with excellent performance characteristics.</p>
<p>The first version of Svelte was all about <a href="https://svelte.dev/blog/frameworks-without-the-framework">testing a hypothesis</a>  — that a purpose-built compiler could generate rock-solid code that delivered a great user experience. The second was a small upgrade that tidied things up a bit.</p>
<p>Version 3 is a significant overhaul. Our focus for the last five or six months has been on <em>delivering an outstanding developer experience.</em>  It's now possible to write components with significantly less boilerplate than you'll find elsewhere. Try the brand new tutorial and see what we mean — if you're familiar with other frameworks we think you'll be pleasantly surprised.</p>
<br>
<center><a class="link-button" href="/blog">Blog</a></center>
<br>
<br>

<style>
	hr {
		border: 1px solid black;
	}
  

   
</style>