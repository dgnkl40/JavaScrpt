# JavaScrpt
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>
        JAVASCRIPT
        
</h1>
<h2 id="info"></h2>
<h3>
    SENİN OKUDUĞUN MEKTEBİN AAMINA KOYUM
</h3>


<script >
    let sinavNotu = prompt("Sınav Notunu Girin:")
let notHarfi;

if(sinavNotu=>0 && sinavNotu<=100){
    if(sinavNotu >=80){
        notHarfi = "AA"
    }
    else if(sinavNotu >=60){
        notHarfi = "BB"
    }
    else if(sinavNotu >=50){
        notHarfi = "CC"
    }
    else if(sinavNotu <50){
        notHarfi = "FF --> KALDIN"
    }
}
else  {
    notHarfi = "GEÇERSİZ PUAN GİRİŞİ"
}

let info = document.querySelector("#info")
info.innerHTML = `${notHarfi} ==> ${sinavNotu}`
</script>

</body>
</html>
