---
permalink: /404.html
---
<html>
	<head>
		<meta charset="utf-8" />
		<title>My first Form Juan pablo, styled</title>
		<style>
			form {
				/* Just to center the form on the page */
				margin: 0 auto;
				width: 400px;
				/* To see the outline of the form */
				padding: 1em;
				border: 1px solid #ccc;
				border-radius: 1em;
			}

			ul {
				list-style: none;
				padding: 0;
				margin: 0;
			}

			form li + li {
				margin-top: 1em;
			}

			label {
				/* To make sure that all labels have the same size and are properly aligned */
				display: inline-block;
				width: 90px;
				text-align: right;
			}

			input,
			textarea {
				/* To make sure that all text fields have the same font settings By default, textareas have a monospace font */
				font: 1em sans-serif;
				/* To give the same size to all text fields */
				width: 300px;
				box-sizing: border-box; /* To harmonize the look & feel of text field border */
				border: 1px solid #999;
			}

			input:focus,
			textarea:focus {
				/* To give a little highlight on active elements */
				border-color: #000;
			}

			textarea {
				/* To properly align multiline text fields with their labels */
				vertical-align: top;
				/* To give enough room to type some text */
				height: 5em;
			}

			.button {
				/* To position the buttons to the same position of the text fields */
				padding-left: 90px;
				/* same size as the label elements */
			}

			button {
				/* This extra margin represent roughly the same space as the space between the labels and their text fields */
				margin-left: 0.5em;
			}
		</style>
	</head>

	<body>
		<form action="https://docs.google.com/forms/u/2/d/e/1FAIpQLSc6DsyZwrcBukzqpqogLClY1lBBH-wXMnaVWcTpEnrwj3_BFQ/formResponse" method="post">
			<ul>
				<li>
					<label for="name">Nombre:</label>
					<input type="text" id="name" name="entry.476547996" />
        </li>
        <li>
					<label for="Phone">Telefono:</label>
					<input type="number" id="phone" name="entry.1945514498" />
				</li>
				<li>
					<label for="mail">E-mail:</label>
					<input type="email" id="mail" name="emailAddress" />
				</li>
				<li>
					<label for="msg">Message:</label>
					<textarea id="msg" name="entry.440022380"></textarea>
				</li>
				<li class="button">
					<button type="submit">Enviar</button>
				</li>
			</ul>
		</form>
	</body>
</html>
