# Vragenlijst DCA-ICT
Lever de antwoorden in een git-repository aan; je kan deze repo 'clonen' en aanvullen indien gewenst. 


## Wat is het verschill tussen 0, NULL, ‘’ en undefined 
Leg dit uit in een (webdevelopment) taal naar keuze, bijvoorbeeld PHP of JavaScript. 

## Maak deze implementatie af
In deze PHP-implementatie hebben we een 'vast' wachtwoord (```$wachtwoord```) en een pseudo ingevuld wachtwoord door een gebruiker (```$gebruikerinvoer```). 
Uiteraard komen we in de exit; terecht, de variabelen ('wachtwoorden') zijn niet gelijk.

Herschijf deze implementatie; hash het ```$wachtwoord``` variabele en zorg dat deze gecontroleerd kan worden op basis van de plaintekst invoer (```$gebruikerinvoer```)


```php
<?php

#zorg dat deze variabele gehast is
$wachtwoord = 'Welkom01!';

$gebruikerinvoer = 'Doei02!';

#deze vergelijking moet uiteraard blijven werken, eventueel in gewijzigde vorm
if($wachtwoord === $gebruikerinvoer) {
    inloggen();
} else {
    throw new Exception('Wachtwoord onjuist');
    exit;
}
?>

```

## CSS specificity hierarchy
Leg van elk element in de ```<body>``` uit welke kleur de tekst en de achtergrond krijgt. 

**Doe dit uit je hoofd, draai deze code niet.** 

```html

<style>
  div, span{
    background: #ff0000;
    color: white;
  }
  div.geel{
    background: #ffff00;
    color: #ff0000;
  }
  div#head{
    background: #0000ff;
  }
  div#wrapper *{
    background :#ffffff;
    color: black;
  }
</style>
<body>
  <div class="geel" id="head">
    <span class="titel">Hoi</span>
    <span class="body">DCA-ICT</span>
  </div>
</body>

```

## Recursie 
Wat is recursie en geef een voorbeeld (of implementatie) waar dit nuttig kan zijn
![droste blik](https://www.hollandwinkel.nl/media/catalog/product/cache/831b25158591b46ca6e0d32ee6983c83/c/a/cacao-droste.png "recursie")

## Client-side vs server-side
Wat is het verschil tussen client-side code (denk aan JavaScript in de browser) en server-side code en geef aan hoe je interactie voorziet tussen die twee.

## Definitie van een loop
Geef drie voorbeelden van een loop en implementeer er een naar keuze;

- Toon de nummers 1 t/m 100
- Indien deelbaar door 3; toon de string "hoi" in plaats van het nummer
- Indien deelbaar door 5; toon de string "DCA" in plaats van het nummer
- Indien deelbaar door 3 en door 5; toon de string "DCA-ICT" in plaats van het nummer

## Lineair search 
Implementeer een lineaire zoekfunctie in een webdevelopment taal naar keuze; bijvoorbeeld PHP.
Zie het onderstaande voorbeeld:
```php
<?php
    function search($hooiberg, $speld) {
    #aanvullen; ik wil de positie terugkrijgen
    }
    $arr = array(4, 2, 5, 6, 14, 7, 15, 3);
    echo search($arr, 14);
?>
```
