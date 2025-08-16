# Input-
Criar um input em HTML é simples!

Aqui está um exemplo básico de como criar um input:
<input type="text" name="nome" placeholder="Digite seu nome">

Nesse exemplo, estamos criando um input do tipo "text" com o nome "nome" e um placeholder que sugere ao usuário o que ele deve digitar.

*Tipos de input*

Existem vários tipos de input que você pode criar, incluindo:

- `text`: input de texto
- `password`: input de senha
- `email`: input de email
- `number`: input de número
- `checkbox`: input de caixa de seleção
- `radio`: input de botão de rádio
- `date`: input de data
- `time`: input de hora

*Atributos*

Você pode adicionar atributos ao input para personalizá-lo, como:

- `name`: nome do input
- `placeholder`: texto que aparece no input antes do usuário digitar
- `value`: valor inicial do input
- `required`: indica se o input é obrigatório
- `disabled`: desabilita o input

*Exemplos*

- Input de texto: `<input type="text" name="nome" placeholder="Digite seu nome">`
- Input de senha: `<input type="password" name="senha" placeholder="Digite sua senha">`
- Input de checkbox: `<input type="checkbox" name="concordo" value="sim"> Concordo com os termos`

Se você estiver usando uma biblioteca ou framework como React ou Angular, a sintaxe pode ser diferente. Por exemplo, em React, você pode criar um input usando o componente `input`:
import React, { useState } from 'react';

function MeuInput() {
  const [nome, setNome] = useState('');

  return (
    <input
      type="text"
      value={nome}
      onChange={(event) => setNome(event.target.value)}
      placeholder="Digite seu nome"
    />
  );
}

Espero que isso ajude! 😊
