<!DOCTYPE html >
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="X-UA-Compatible" content="ie=edge">
    <title> Aula 01 - VueJS do jeito ninja! </title>
</head>

<body>
    <div id="app">
        {{ titulo }}
    </div>

    <script src="https://unpkg.com/vue"></script>
    <script>
        var app = new Vue({
            el: "#app",
            data: {
                titulo: "Aula 01s2 "
            }
        })

    </script>
</body>


</html>
