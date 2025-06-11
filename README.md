<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>K'9 Elite - Guilda Free Fire</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>K'9 Elite</h1>
    <p>Guilda oficial de Free Fire</p>
    <img src="assets/logo.png" alt="Leão de Judá - K'9 Elite" style="width: 100px;">
  </header>

  <main>
    <section id="cadastro">
      <h2>Inscreva-se para a Guilda</h2>
      <form id="formCadastro">
        <label>Nome completo:</label>
        <input type="text" name="nome" required><br>

        <label>Nick do Free Fire:</label>
        <input type="text" name="nick" required><br>

        <label>ID do Free Fire:</label>
        <input type="text" name="id" required><br>

        <label>Tipo de jogador:</label>
        <select name="tipo" required>
          <option value="Atirador">Atirador</option>
          <option value="Rushador">Rushador</option>
          <option value="Suporte">Suporte</option>
          <option value="Granadeiro">Granadeiro</option>
          <option value="Fuzileiro">Fuzileiro</option>
        </select><br>

        <label>Link do vídeo (melhores jogadas):</label>
        <input type="url" name="video" required><br>

        <button type="submit">Enviar inscrição</button>
      </form>
    </section>

    <section id="selecionados">
      <h2>Jogadores Selecionados</h2>
      <div id="listaSelecionados">Carregando...</div>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 K'9 Elite Guilda</p>
    <a href="painel.html">Painel do Líder</a>
  </footer>

  <script src="script.js"></script>
</body>
</html>
