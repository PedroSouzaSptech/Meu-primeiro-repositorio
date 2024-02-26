# Meu-primeiro-repositorio
alteração feita no repositório remoto
<!DOCTYPE html>
<html lang="Pt-Br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ex 05 Faculdade</title>
</head>
<body>
    <h1>Nota do aluno</h1>
    Digite a nota que você tirou na CONTINUADA: <input type="text" id="input_con"> <br><br>

    Digite a nota que você tioru na SEMESTRAL: <input type="text" id="input_sem"><br><br>

    Digite seu nome: <input type="text" id="input_nome"><br><br>

    <button onclick= media()>Calcule sua média</button>
</body>

<script>
    function media() {
        var con = input_con.value;
        var sem = input_sem.value;
        var calc_con =  con * 0.4;
        var calc_sem = sem * 0.6;
        var calc_med = calc_con + calc_sem;
    
        alert ("A média de " + input_nome.value + " será de " + calc_med );
    }
</script>
</html>
