# Profº Paulo Banho e Tosa

<!doctype html>
<html lang="pt-br">
<head>
<meta charset="utf-8">
<title>Meu amigo cão</title>
<script src="interacao/html5shiv.min.js"></script>    
</head>

<body id="banhoEtosa">
<a href="index.html">Home</a>
<main>    
<h1> Agendamento para banho e tosa </h1>
<h2> Faça o seu agendamento com pelo menos 48 horas de antecedência</h2>

<form method="post" id="contato" action="obrigado.html">
    <fieldset id="ident_dono">
        <legend>Identificação do dono do animal</legend>

<p><label for="nome_dono">Nome:</label> <input type="text" name="nome_dono" id="nome_dono" size = "50" placeholder="Digite o nome completo do dono do animal" maxlength="100"/></p>

<p><label for="endereco">Endereço:</label> <input type="text" name="endereco" id="endereco" size = "80" placeholder="Digite o endereço" maxlength="60"/></p>

<p><label for="cep">CEP:</label> <input type="text" name="cep" id="cep"  size = "10"  placeholder="XXXXX-XXX" maxlength="9"/></p>

<p><label for="email_dono">Email:</label> <input type="email" name="email_dono" id="email_dono" size = "80"  placeholder="Digite o endereço de email" maxlength="60"></p> 

<p><label for="tel_dono">Tel/Cel:</label> <input type="text" name="tel_dono" id="tel_dono" size = "12" placeholder="99 99999-9999" maxlength="13"/></p>
    </fieldset>
    <fieldset id="ident_animal">
        <legend>Identificação do animal</legend>
<p>
    <label for="nome_animal">Nome:</label> <input type="text" name="nome_animal" id="nome_animal"  size = "25"  placeholder="Digite o nome do animal" maxlength="40"/></p>
    <p>
        Porte do cão:
        <input type="radio" name="porte_animal" id="animal_pequeno" value="0">Pequeno
        <input type="radio" name="porte_animal" id="animal_medio" value="1">Medio
        <input type="radio" name="porte_animal" id="animal_grande" value="2" checked>Grande
    </p>
    <p>
        Tipo de Tosa:
        <select name="tipo_tosa" id="tipo_tosa">
            <option value="0">Nenhuma</option>
            <option value="1">Tosa Padrão</option>
            <option value="2">Tosa Higienica</option>
            <option value="3">Tosa na Tesoura</option>
            <option value="4">Tosa da Raça</option>
            <option value="5">Tosa Bebê</option>
        </select>
    </p>
    <p>
        Observações:
        <textarea name="q_obs" id="q_obs" placeholder="Digita alguma informação sobre o animal">

        </textarea>
    </p>
    </fieldset>
    <fieldset id="ident_marcacao">
        <legend>Horario - Não atendemos aos Domingos, Feriados e Segundas-Feiras</legend>
        <p>
            Indique os dias da semana de sua preferencia:<br>
            <input type="checkbox" name="dia_semana" id="terça-feira" value="0">Terça-feira
            <input type="checkbox" name="dia_semana" id="quarta-feira" value="1">Quarta-feira
            <input type="checkbox" name="dia_semana" id="quinta-feira" value="2">Quinta-feira
            <input type="checkbox" name="dia_semana" id="sexta-feira" value="3">Sexta-feira
            <input type="checkbox" name="dia_semana" id="sabado" value="4">Sabado
        </p>
        <p>
            Primeira opção de Horario
            <input type="date" name="pdata" id="pdata"> 
        </p>
        <p>
            Segunda opção de Horario
            <input type="date" name="sdata" id="sdata">
        </p>
    </fieldset>
<input type="submit" value="Enviar">

</form>
</main>
<footer>
    <p>Atendimento: <a href="mailto:atendimento@meuamigocao.com.br">atendimento@meuamigocao.com.br</a>
        - (0XX) 9999-9999 / (0XX) 8888-8888</p>
</footer>
</body>
</html>
