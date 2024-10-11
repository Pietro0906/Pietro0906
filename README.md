<form action="/submit" method="POST">
    <fieldset>
        <legend>Informações Pessoais</legend>

        <label for="name">Nome:</label>
        <input type="text" id="name" name="name" required placeholder="Digite seu nome"
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required placeholder="Digite seu email">
        
        <label for="password">Senha:</label>
        <input type="password" id="password" name="password" minlength="8" required>

        <label for="address">endereço:</label>
        <input type="address" id="address" name="address" required placeholder="Digite seu endereço"
    </fieldset>

    <fieldset>
        <legend>Preferências</legend>
        
        <label for="newsletter">
          <input type="checkbox" id="newsletter" name="newsletter" checked>
          Inscrever-se no boletim informativo
        </label>
        
        <label for="gender-male">
          <input type="radio" id="gender-male" name="gender" value="male">
          Masculino
        </label>
        
        <label for="gender-female">
          <input type="radio" id="gender-female" name="gender" value="female">
          Feminino
        </label>

        <label for="country">País:</label>
        <select id="country" name="country">
          <option value="brasil">Brasil</option>
          <option value="portugal">Portugal</option>
        </select>
    </fieldset>

    <button type="submit">Enviar</button>
</form>
