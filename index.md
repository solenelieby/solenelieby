<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width">
		<title>Wououuu</title>
		<style>
		/**********************/
		/* Flex */
		/**********************/
			.coteACote{
				display: flex;
				border: 1px solid black;
				margin: 2px;
			}
			.boite{
				border: 1px solid black;
				margin: 5px;
				padding: 5px;
				background: #09C;
				color: #FFF;
			}

			.partie2{
				justify-content: space-between;
			}
			.partie3{
				flex: 1;
			}
			.partie4{
				margin-left: auto;
			}

		/**********************/
		/* Grid */
		/**********************/
			.grid{
				border: 1px solid black;
				background: #0C9;
				margin-top: 50px;

				display: grid;

				/* grid-template-columns: 50% 50%; */ /* Question 12 */

				grid-template-columns: 1fr 1fr; /* Question 13 */

				/* grid-template-columns: 1fr 1fr 1fr; */ /* Question 14 */
			}
		</style>
	</head>
	<body>

<!-- ------------------------------- -->
<!-- Flexbox -->
<!-- ------------------------------- -->
		<div class="coteACote">
			<div class="boite">bla bla bla</div>
			<div class="boite">bla bla bla</div>
			<div class="boite">bla bla bla</div>
		</div>
		<div class="coteACote partie2">
			<div class="boite">bla bla bla</div>
			<div class="boite">bla bla bla</div>
			<div class="boite">bla bla bla</div>
		</div>
		<div class="coteACote">
			<div class="boite partie3">bla bla bla</div>
			<div class="boite partie3">bla bla bla</div>
			<div class="boite partie3">bla bla bla</div>
		</div>
		<div class="coteACote">
			<div class="boite">bla bla bla</div>
			<div class="boite">bla bla bla</div>
			<div class="boite partie4">bla bla bla</div>
		</div>

<!-- ------------------------------- -->
<!-- Grid -->
<!-- ------------------------------- -->		
		<div class="grid">
			<div class="boite">bla bla bla</div>
			<div class="boite">bla bla bla</div>
			<div class="boite">bla bla bla</div>
			<div class="boite">bla bla bla</div>
			<div class="boite">bla bla bla</div>

			<div class="boite">bla bla bla</div>
			<div class="boite">bla bla bla</div>
			<div class="boite">bla bla bla</div>
			<div class="boite">bla bla bla</div>
			<div class="boite">bla bla bla</div>
		</div>
	</body>
</html>
