<main>
	<p>
		Typography is an <em>essential element of modern web design </em> . Good typography helps to create
		a visually appealing and easy-to-read website. This is especially important for websites that have
		a lot of text, such as news websites or online publications.
	</p>

	<p>
		Another important aspect of typography in web design is that it helps to create a consistent and
		cohesive visual aesthetic. By carefully selecting fonts and using them consistently throughout a
		website, designers can create a cohesive design that reinforces the brand and helps to create a
		more professional and polished look. This can help to improve the overall user experience, as
		well as making the website more appealing to potential customers or clients.
	</p>

	<p>
		Finally, typography can also be used to create visual hierarchy and emphasis on a website. By
		using different font sizes, styles, and weights, designers can draw attention to important
		elements of a website and make it easier for users to navigate. This can help to guide users
		through the website and ensure that they can find the information they are looking for quickly
		and easily.
	</p>

	<div class="menu">
        <h2>MENU OF TOPICS</h2>
		<ul class="links-container">
			<li><a class="link-principal" href="/what-is-type">WHAT IS TYPE?</a></li>
			<li><a class="link-principal" href="/stroke-and-proportion">STROKE AND PROPORTION</a></li>
			<li><a class="link-principal" href="/type-anatomy">TYPE ANATOMY</a></li>
			<li><a class="link-principal" href="/choosing-type">CHOOSING TYPE</a></li>
			<li><a class="link-principal" href="/typeface-and-their-histories">TYPEFACES AND THEIR HISTORIES</a></li>
			<li><a class="link-principal" href="/bembo">BEMBO: HUMANIST LETTERS</a></li>
			<li><a class="link-principal" href="/didot">DIDOT: ENLIGHTENED REFINEMENT</a></li>
			<li><a class="link-principal" href="/futura">FUTURA: THE TYPOGRAPHYC AVANT-GARDE</a></li>
			<li><a class="link-principal" href="/helvetica">HELVETICA: INTERNATIONAL MODERN</a></li>
			<li><a class="link-principal" href="/typographic-space">TYPOGRAPHIC SPACE</a></li>
			<li><a class="link-principal" href="/page-space">PAGE SPACE</a></li>
			<li><a class="link-principal" href="/the-grid">THE GRID</a></li>
			<li><a class="link-principal" href="/creating-hierarchy">CREATING HIERARCHY</a></li>
			<li><a class="link-principal" href="/typographic-conventions">TYPOGRAPHIC CONVENTIONS</a></li>
			<li>
				<a class="link-principal" href="/typesetting-with-expression">TYPESETTING WITH EXPRESSION</a
				>
			</li>
			<li><a class="link-principal" href="/beyond-typesetting">BEYOND TYPESETTING</a></li>
		</ul>
        
	</div>
</main>

<style>
    .menu{
        background-color: bisque;
        padding: 1rem;
        margin-bottom: 3rem;
    }
    .menu >h2{
        text-align: center;
        color: #555;
        letter-spacing: 0.5rem;
        background-color: coral;
        padding-block: 0.3rem;
        margin-inline: 1rem;
    }
	.links-container {
		display: flex;
		flex-direction: column;
		gap: 1rem;
        margin-left: -1.5rem;
	}

	ul > li > a {
		text-decoration: none;
		color: black;
		letter-spacing: 0.03rem;
        padding: 0.5rem;
       
	}

	ul > li > a:hover {
	
        background-color: coral;
	
	}
    li{
        list-style: none;
    }
    @media(max-width:900px) {
        .links-container{
            margin-left: -2.5rem;
            font-size: 1.3rem;
            line-height: 1.1rem;
        }
        .menu > h2{
            margin-inline: 0.34rem;
        }
    }
</style>
