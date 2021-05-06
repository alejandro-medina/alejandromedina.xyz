<script>
</script>

<style type="text/scss">
    
    main#Cover {
	height: 100vh;
	width: 100%;
	background: #333;
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

	div.cover-sections {
	
		width: 100%;
		height: 100%;

		display: flex;
		flex-direction: column;
		justify-content: center;

		div.sections {
			width: 100%;
			height: 70%;	
			
			display: flex;
			flex-flow: row wrap;
			justify-content: space-around;
			
			div.card {

				width: 45%;

				margin-bottom: 1rem;
				padding: 1rem;


				border-radius: 10px;
				box-sizing: border-box;
				box-shadow: 0px 10px 10px -6px #222;
				
				cursor: pointer;

				&.card-green {
					background-color: #27ae60;
					&:hover {
						background-color: #2ecc71;
					}
				}

				&.card-blue {
					background-color: #2980b9;
					&:hover {
						background-color: #3498db;
					}
				}

				&.card-yellow {
					background-color: #f39c12;
					&:hover {
						background-color: #f1c40f;
					}
				}

				&.card-red {
					background-color: #c0392b;
					&:hover {
						background-color: #e74c3c;
					}
				}
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
					<p>Mi sitio web está en remodelación...puedes contactarme a través de</p>
					
					<ul style="list-style:none; padding:0; font-size:18px; color: #fafafa">
						<li>Email: <a style="color:inherit;" href="mailto:rodrigo.medinacetz@gmail.com">rodrigo.medinacetz@gmail.com</a></li>
						<li>Phone: <a style="color:inherit;" href="tel:+529991087473">9991-08-74-73</a></li>
						<li>Whatsapp: <a target="_blank" style="color:inherit;" href="https://web.whatsapp.com/send?phone=529991087473&text=Hola,%20me%20gustar%C3%ADa%20conocer%20m%C3%A1s%20sobre...">Click para enviarme un mensaje</a></li>
					</ul>
					

                </div>
			</div>

		</div>
		
    </div>

</main>
