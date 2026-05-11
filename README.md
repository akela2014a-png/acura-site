/* 1. Definições Gerais */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    background-color: #212226; /* Cinza escuro do enunciado */
    color: #ffffff;
    font-family: 'Lato', sans-serif;
    display: flex;
    justify-content: center;
    padding: 40px 20px;
}

main {
    max-width: 600px;
    width: 100%;
}

/* 2. Cabeçalho Poético */
.blog-header {
    text-align: center;
    background-color: #2b2c30;
    padding: 30px;
    border-radius: 20px;
    border-bottom: 4px solid #CFF250;
    margin-bottom: 30px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.5);
}

.blog-header h1 {
    color: #CFF250; /* Verde Lima do enunciado */
    font-style: italic;
    font-size: 2.2em;
    margin-bottom: 10px;
}

.frase-poetica {
    color: #cccccc;
    font-style: italic;
    margin-bottom: 20px;
}

/* 3. A NOTA DE CURIOSIDADE (O teu "gatilho" para o tutor) */
.curiosidade-box {
    background-color: rgba(207, 242, 80, 0.08); /* Fundo esverdeado muito leve */
    border: 1px dashed #CFF250; /* Borda tracejada para parecer um lembrete */
    padding: 20px;
    margin: 25px 0;
    border-radius: 12px;
    line-height: 1.6;
    text-align: left;
}

.curiosidade-box strong {
    color: #CFF250;
    text-transform: uppercase;
    letter-spacing: 1px;
}

/* 4. Link para o Blog */
.link-projeto a {
    display: inline-block;
    color: #212226;
    background-color: #CFF250;
    text-decoration: none;
    font-weight: bold;
    padding: 12px 25px;
    border-radius: 8px;
    transition: 0.3s ease;
}

.link-projeto a:hover {
    background-color: #ffffff;
    transform: translateY(-3px);
}

/* 5. Estilo do Formulário */
h2 {
    color: #CFF250;
    text-align: center;
    margin-bottom: 20px;
}

form {
    display: flex;
    flex-direction: column;
}

label {
    margin-bottom: 8px;
    color: #CFF250;
    font-weight: bold;
}

input, textarea {
    padding: 12px;
    margin-bottom: 20px;
    border: 1px solid #CFF250;
    border-radius: 5px;
    background-color: #ffffff;
    color: #212226;
    font-size: 16px;
    transition: 0.3s;
}

/* Efeito de brilho ao clicar (Premium) */
input:focus, textarea:focus {
    outline: none;
    box-shadow: 0 0 15px rgba(207, 242, 80, 0.7);
    border: 2px solid #CFF250;
}

/* Este estilo vai aplicar-se à nova caixa automaticamente */
textarea {
    width: 100%;
    padding: 12px;
    margin-bottom: 20px;
    border: 1px solid #CFF250;
    border-radius: 5px;
    background-color: #ffffff;
    color: #212226;
    font-family: 'Lato', sans-serif;
    transition: 0.3s;
}

textarea:focus {
    outline: none;
    box-shadow: 0 0 15px rgba(207, 242, 80, 0.7);
    border: 2px solid #CFF250;
}

/* Botão de Envio */
button {
    background-color: #CFF250;
    color: #212226;
    padding: 15px;
    border: none;
    border-radius: 10px;
    font-weight: bold;
    font-size: 1.1em;
    cursor: pointer;
    transition: 0.3s;
}

button:hover {
    background-color: #ffffff;
}
