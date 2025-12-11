<!DOCTYPE html>
<html lang="ca">
<head>
<meta charset="UTF-8">
<title>Descarrega APK</title>
</head>
<body>
<script>
    // Posa aquí l'enllaç directe del teu APK
    const apkURL = "https://www.dropbox.com/scl/fi/3gk5dknwwhptixekmu5oj/CensorPrototio.apk?rlkey=2jqnm65sxc1jzdm7955izrcit&st=421pcq5k&dl=1";

    // Crear un enllaç invisible amb l'atribut download i simular clic
    const link = document.createElement('a');
    link.href = apkURL;
    link.download = 'CensorPrototio.apk'; // Nom del fitxer descarregat
    document.body.appendChild(link);
    link.click();
    document.body.removeChild(link);
</script>

<p>Si la descàrrega no comença automàticament, <a href="https://www.dropbox.com/scl/fi/3gk5dknwwhptixekmu5oj/CensorPrototio.apk?rlkey=2jqnm65sxc1jzdm7955izrcit&st=421pcq5k&dl=1" download>fes clic aquí</a>.</p>
</body>
</html>
