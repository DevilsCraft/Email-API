# Email-API
C'est une api gratuite qui vous permet d'envoyé des mails, juste avec le html (SANS PHP)

#<a href="http://https://github.com/DevilsCraft/Email-API/exemple/html">Exemple de formulaire</A>

`
<form action="http://petitbonhomme.co/api/mail.php" method="POST"> <!-- OBLIGATOIRE -->

	<link rel="stylesheet" type="text/css" href="http://petitbonhomme.co/api/email.css" />

	<input type="hidden" name="to" value="tonadressemail@gmail.com" /> <!-- Adresse ou le mail va être envoyé -->
	<input type="hidden" name="site" value="http://tonsite.com" /> <!-- Url de la page de contact de votre site -->

	<label for="pseudo">Pseudo : </label>
	<input type="text" name="pseudo" placeholder="Pseudo" /> <!-- Le pseudo du client (NE PAS OUBLIER LE NAME) -->

	<br /><br />

	<label for="email">Email : </label>
	<input type="email" name="from" placeholder="Email" />  <!-- Adresse mail du client (NE PAS OUBLIER LE NAME ) -->

	<br /><br />

	<label for="subject">Subject : </label>
	<input type="text" name="subject" placeholder="Subject" /> <!-- Sujet du message (NE PAS OUBLIER LE NAME ) -->

	<br /><br />

	<label for="message">Message : </label>
	<textarea name="message" placeholder="Message"></textarea> <!-- Son message ... (NE PAS OUBLIER LE NAME) -->

	<br /><br />

	<input type="submit" />
	
</form>

`


