<script>
</script>

<style type="text/scss">
    
    main#Cover {
	height: 100vh;
	width: 100%;
	background: #222222;
	color: #fafafa;
	.container {
		height: 100%;
	}
	.row {
		height: 100%;
		.col-12 {
			height: 100%;
		}
	}

	div.cover-info {
		height: 100%;
		width: 100%;
		display: flex;
		flex-direction: column;
		justify-content: center;
		h1 {
			font-size: 3em;
		}
		p {
			font-size: 1.5em;
		}
	}
	div.contact-info {
		display: initial;
		ul {
			list-style: none;
			margin: 0;
			padding: 0;
			text-decoration: none;
			a {
				li {
					display: inline-block;
					margin-right: 1em;
					padding: 10px 15px;
					background: #fafafa;
					cursor: pointer;
					&:hover {
						background: #d4d4d4;
					}
				}
				color: #222222;
				text-decoration: none;
			}
		}
	}
}


</style>

<main id="Cover">

    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="cover-info">
                    <h1>Alejandro Medina</h1>
                    <p>Coding ideas into products, services, reality...</p>
                    <div class="contact-info">
                        <ul>
                            <a target="_blank" href="https://alejandromedina.xyz"><li>Website</li></a>
                            <a target="_blank" href="http://github.com/alejandro-medina"><li>Github</li></a>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>


</main>
