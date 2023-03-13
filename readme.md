<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>test-Cadastro</title>
</head>
<body>
    <div>
        <h1>Cadastro de DEVS</h1>
        <p>Complete suas informações;</p>
        <br>
    </div>
<form>
        <fieldset>
            <div>
                <label>Nome</label>
                <input type="text" name="nome" id="nome">
            </div>
            <div>
                <label>Sobrenome</label>
                <input type="text" name="sobrenome" id="sobrenome">
            </div>   
        </fieldset>   
        <div>
            <label>Email</label>
            <input type="email" name="email" id="email">
        </div>
        <div>
            <label>De qual lado da aplicação você desenvolve?</label>
            <label>
            <input type="radio" name="devweb" value="frontend" checked>Front-End
            </label>
            <label>
                <input type="radio" name="devweb" value="backend">Back-End
            </label>
            <label>
                <input type="radio" name="devweb" value="fullstack">Fullstack
            </label>
        </div>
        <div>
            <label>Senioridade</label>
            <select id="senioridade">
                <option selected disabled value="">Selecione</option>
                <option>Junior</option>
                <option>Pleno</option>
                <option>Senior</option>
            </select>
        </div>
        <fieldset>
            <label>Selecione a tecnologia que utiliza:</label><br><br>
            <input type="checkbox" id="tecnologia1" name="tecnologia1" value="HTML">
            <label for="tecnologia1">HTML</label>
            <input type="checkbox" id="tecnologia2" name="tecnologia2" value="CSS">
            <label for="tecnologia2">CSS</label>
            <input type="checkbox" id="tecnologia3" name="tecnologia3" value="Javascript">
            <label for="tecnologia3">Javascript</label>
            <input type="checkbox" id="tecnologia4" name="tecnologia4" value="PHP">
            <label for="tecnologia4">PHP</label>
            <input type="checkbox" id="tecnologia5" name="tecnologia5" value="Python">
            <label for="tecnologia5">Python</label>
        </fieldset>
</form> 
</body>