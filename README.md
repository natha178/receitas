<div class="form-container">
  <h2>Faça sua Encomenda</h2>
  <form action="#" method="post">

    <!-- Dados do Cliente -->
    <label for="nome">Nome:</label>
    <input type="text" id="nome" name="nome" required>

    <label for="endereco">Endereço:</label>
    <input type="text" id="endereco" name="endereco" required>

    <label for="telefone">Telefone:</label>
    <input type="tel" id="telefone" name="telefone" required>

    <label for="whatsapp">WhatsApp:</label>
    <input type="tel" id="whatsapp" name="whatsapp" required>

    <!-- Tipo de Produto -->
    <label for="produto">O que deseja encomendar?</label>
    <select id="produto" name="produto" required>
      <option value="">Selecione uma opção</option>
      <option value="bolos">Bolos</option>
      <option value="salgados">Salgados</option>
      <option value="sobremesa">Sobremesa</option>
      <option value="outros">Outros</option>
    </select>

  
