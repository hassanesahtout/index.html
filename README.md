# index.html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Reservations</title>
</head>
<body>

<form action="service.html" method="post">

    <fieldset>
        <legend>Informations client</legend>

        <p>
            <label for="nom">Nom</label>
            <input type="text" name="nom" id="nom" placeholder="Votre nom">
        </p>

        <p>
            <label for="prenom">Prénom</label>
            <input type="text" name="prenom" id="prenom" placeholder="Votre prénom">
        </p>

        <p>
            <label for="email">Email</label>
            <input type="email" name="email" id="email" placeholder="Votre email">
        </p>
    </fieldset>

    <fieldset>
        <legend>Détails de rendez-vous</legend>

        <p>
            <label for="date">Date</label>
            <input type="date" name="date" id="date">
        </p>

        <p>
            <label for="heure">Heure</label>
            <input type="time" name="heure" id="heure">
        </p>
    </fieldset>

    <fieldset>
        <legend>Type de service</legend>

        <p>
            <input type="radio" name="type_service" value="consultation_medicale" checked>
            <label>Consultation médicale</label>
        </p>

        <p>
            <input type="radio" name="type_service" value="coiffure">
            <label>Coiffure</label>
        </p>

        <p>
            <input type="radio" name="type_service" value="formation">
            <label>Formation</label>
        </p>
    </fieldset>

    <button type="submit">Réserver</button>

</form>

</body>
</html>
