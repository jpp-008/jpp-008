```js
import { Desenvolvedor, Contatos } from "jpp-008";

class SobreMim extends Desenvolvedor {
  nome = "João Pedro";
  area = "Ciência da Computação";
  emFaculdade = true;
  periodo = 1;

  interesses = ["Game Dev", "Front end"];

  projetos = {
    "existentes": 15;
    "emDesemvolvimentoAtivo": 2;
    "finalizados": 0;
  }
}

class Skills extends Desenvolvedor {
  linguagens = ["LuaU", "Typescript", "Python"];
}

Contatos.email = "jpportela_2008@outlook.com"
Contatos.linkedin = "https://www.linkedin.com/in/jpp-dev/"
```
