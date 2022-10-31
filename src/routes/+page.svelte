<h1>Svelte 3: Rethinking reactivity</h1>
<p>It's finally here</p>
<hr>
<br>
<p>After several months of being just days away, we are over the moon to announce the stable release of Svelte 3. This is a huge release representing hundreds of hours of work by many people in the Svelte community, including invaluable feedback from beta testers who have helped shape the design every step of the way.</p>
<p>We think you're going to love it.</p>
<h3>What is Svelte?</h3>
<p>Svelte is a component framework — like React or Vue — but with an important difference. Traditional frameworks allow you to write declarative state-driven code, but there's a penalty: the browser must do extra work to convert those declarative structures into DOM operations, using techniques like <a href="https://svelte.dev/blog/virtual-dom-is-pure-overhead">virtual DOM diffing</a>   that eat into your frame budget and tax the garbage collector.</p>

<p>Instead, Svelte runs at build time, converting your components into highly efficient imperative code that surgically updates the DOM. As a result, you're able to write ambitious applications with excellent performance characteristics.</p>

<style>
	hr {
		border: 1px solid black;
	}
    a{
        text-decoration: none;
        color: white;
        cursor: pointer;
    }
    a:hover{
        text-decoration:underline;
    }
</style>