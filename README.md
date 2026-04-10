<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" href="style.css"> 
    <meta http-equiv="content-type" content="text/html; charset=utf-8">
</head>
<style>
    body {
        background-color: #99f0b0;
    }
    div {
        padding: 5%;
        width: 50%;
        margin: 0 auto;
    
    }

    #comment {
    margin-left: 10px;
    margin-top: 10px;
    }
</style>
<body>
    <h1 style="text-align: center;">Psychologisches Experiment</h1>

    <label>Alle im Rahmen dieser Umfrage eingegebenen Daten werden anonym behandelt. 
        Es werden keine personenbezogenen Daten erhoben, gespeichert oder weitergegeben. 
        Die Angaben dienen ausschließlich zu der visualisierung einer graphischen Darstellung</label>

    
    <h2>Du bist in einer 5-köpfigen Freundesgruppe in einer Bar/einem Restaurant/ einer Party.
        Einer deiner Freundinnen bringt eine weitere Freundin mit, welche dir schon bekannt ist.
        Die Freundin ist sichtlich müde/schlecht gelaunt (ist in sich gekehrt, redet wenig, wirkt abwesend). Ihre 
        Stimmung verändert sich nicht, wenn man dannach fragt / sie anspricht.
        
    </h2>
    <!-- Create Form -->
    <form id="form" action="https://formsubmit.co/tsoup68@gmail.com" method="POST">
        <div class="form-control">
            <label>Was denken Sie über die Person?</label><br>
             <textarea name="frage1" id="comment" placeholder="Ihr Kommentar"></textarea>


        </div>


        <!-- Details -->
         <div class="form-control">
            <label>Stört Sie das Verhalten der Person?
                <small>(0 - garkein Problem, 10 - sehr störend, versaut den Abend)</small><br>
            </label>
            <label><input type="radio" name="rating1" value="0"> 0</label>
            <label><input type="radio" name="rating1" value="1"> 1</label>
            <label><input type="radio" name="rating1" value="2"> 2</label>
            <label><input type="radio" name="rating1" value="3"> 3</label>
            <label><input type="radio" name="rating1" value="4"> 4</label>
            <label><input type="radio" name="rating1" value="5"> 5</label>
            <label><input type="radio" name="rating1" value="6"> 6</label>
            <label><input type="radio" name="rating1" value="7"> 7</label>
            <label><input type="radio" name="rating1" value="8"> 8</label>
            <label><input type="radio" name="rating1" value="9"> 9</label>
            <label><input type="radio" name="rating1" value="10"> 10</label>
        </div>

        <div class="form-control-2">
            <label>Wie stark beeinflusst die schlechte Stimmung ihren Abend?</label>
                <small>(0 - garnicht, 10 - sehr, versaut den Abend)</small><br>
            <label><input type="radio" name="rating2" value="0"> 0</label>
            <label><input type="radio" name="rating2" value="1"> 1</label>
            <label><input type="radio" name="rating2" value="2"> 2</label>
            <label><input type="radio" name="rating2" value="3"> 3</label>
            <label><input type="radio" name="rating2" value="4"> 4</label>
            <label><input type="radio" name="rating2" value="5"> 5</label>
            <label><input type="radio" name="rating2" value="6"> 6</label>
            <label><input type="radio" name="rating2" value="7"> 7</label>
            <label><input type="radio" name="rating2" value="8"> 8</label>
            <label><input type="radio" name="rating2" value="9"> 9</label>
            <label><input type="radio" name="rating2" value="10"> 10</label>
        </div>

        <div class="form-control-3">
            <label>Wenn Sie mehr als 5 eingegeben haben, in welche Richtung beeinflusst
            Sie das Verhalten?</label><br>
            <textarea name="bonusfrage" id="comment" placeholder="Ihre Antwort"></textarea>
            

        

        <div class="form-control-3">
            <label>Würden Sie die Person zur nächsten Party/ Treffen einladen?</label><br>
            <label for="recommed-1">
                <input type="radio" id="recommed-1" name="frage2">Ja
            </label>
            <label for="recommed-2">
                <input type="radio" id="recommed-2" name="frage2">Nein
            </label>
            <label for="recommed-3">
                <input type="radio" id="recommed-3" name="frage2">Vielleicht
            </label>
        </div>

        <div class="form-control-4">
            <label>Würde sich ihr Interesse, die Person besser kennenzulernenVerhalten, durch diese Situation verändern?
            </label><br>
            <label for="recommed-4">
                <input type="radio" id="recommed-4" name="frage3">Ja
            </label>
            <label for="recommed-5">
                <input type="radio" id="recommed-5" name="frage3">Nein
            </label>
            <textarea name="frage3" id="comment" placeholder="Andere Antwort"></textarea>
            
        </div>

        <div class="form-control-5">
            <label for="comment">Sonstige Bemerkungen</label><br>
            <textarea name="kommentar" id="comment" placeholder="Ihr Kommentar"></textarea>
        </div>

        <div>
        <!-- Submit Button -->
        <button type="submit" value="submit">Abschicken</button>
        </div>
    </form>
</body>
</html>
